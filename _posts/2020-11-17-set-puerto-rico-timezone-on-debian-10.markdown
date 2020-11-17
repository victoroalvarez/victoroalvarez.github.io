---
layout: post
title:  "Set Puerto Rico's timezone on Debian 10"
date:   2020-11-17 13:50:50 -0400
categories: linux
---
To set the correct timezone for Puerto Rico, run:

```bash
$ sudo timedatectl set-timezone America/Puerto_Rico
```
To list all timezones run:
```bash
$ timedatectl list-timezones
```

