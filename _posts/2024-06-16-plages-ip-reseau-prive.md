---
layout: post
title:  "Plages d'adresses IP dans un réseau privé"
date:   2025-06-16 18:00:00 +0200
categories: [informatique,reseau]
tags: [reseau]
---

Certaines plages d’adresses IP sont réservées pour une utilisation locale. Ainsi, pour configurer un réseau local quand on n’a pas de plage d’adresses publiques à disposition, on doit utiliser ces plages d’adresses privées. Vous pouvez les utiliser comme bon vous semble.

| Préfixe | Plage IP |  Nombre d'adresses |
|---------|----------|------------|
| 10.0.0.0/8 | 10.0.0.0 – 10.255.255.255 | 2<sup>32-8</sup> = 16 777 216 |
| 172.16.0.0/12 | 172.16.0.0 – 172.31.255.255 | 2<sup>32-12</sup> = 1 048 576 |
| 192.168.0.0/16 | 192.168.0.0 – 192.168.255.255  | 2<sup>32-16</sup> = 65 536 |


Source : [Wikipédia](https://fr.wikipedia.org/wiki/R%C3%A9seau_priv%C3%A9)


