---
layout: post
title:  "Git - Régles .gitignore pas prise en compte"
date:   2025-06-15 11:00:00 +0200
categories: [git]
tags: [git]
---

Si vous mettez à jour votre .gitignore et que ces modifications ne sont pas prise en compte alors il faut exécuter les commandes suivantes :

En premier, on supprime le contenu de l'index.
```bash
git rm -r --cached .
```
> Ne pas oublier le point final.
{: .prompt-warning }


On ajoute tous les fichiers dans l'index (en prenant en compte les règles de .gitgnore).
```bash
git add .
```

Un petit commit pour prendre en compte ces modifications.
```bash
git commit -m "prise en compte gitignore"
```
