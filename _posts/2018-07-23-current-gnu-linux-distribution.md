---
layout: post
title: current GNU/Linux distribution
date: 2018-07-23
---

# How do I determine which GNU/Linux distribution I am using?

Open a shell (terminal). Below are three commands which you can try, and their output.

* lsb_release --all

```
root@kali:~# lsb_release --all

No LSB modules are available.
Distributor ID:    Kali
Description:    Kali GNU/Linux Rolling
Release:    kali-rolling
Codename:    kali-rolling
```

* uname --all

```
root@kali:~# uname --all

Linux kali 4.15.0-kali2-amd64 #1 SMP Debian 4.15.11-1kali1 (2018-03-21) x86_64 GNU/Linux
```

* cat /etc/os-release

```
root@kali:~# cat /etc/os-release

PRETTY_NAME="Kali GNU/Linux Rolling"
NAME="Kali GNU/Linux"
ID=kali
VERSION="2018.2"
VERSION_ID="2018.2"
ID_LIKE=debian
ANSI_COLOR="1;31"
HOME_URL="https://www.kali.org/"
SUPPORT_URL="https://forums.kali.org/"
BUG_REPORT_URL="https://bugs.kali.org/"
```
