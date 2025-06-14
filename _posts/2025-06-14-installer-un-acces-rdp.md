---
layout: post
title:  "Installer un accès RDP sur une machine linux"
date:   2025-06-14 23:00:00 +0200
categories: [linux]
tags: [linux, rdp, debian]
---

# Installer un accès RDP sur une machine linux

Sur une machine Debian ou dérivée. Il faut installer le service "xrdp" avec les commandes suivantes :

```bash
sudo apt-get -y install xrdp
sudo systemctl enable xrdp
sudo adduser xrdp ssl-cert
```