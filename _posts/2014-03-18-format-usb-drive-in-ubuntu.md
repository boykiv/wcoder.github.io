---
layout: post
title: Форматирование USB-флешки в Ubuntu
date: 2014-03-18 0:52
tags:
- ubuntu
- linux
- usb
---

Поискать съемный диск можно с помощью команды:

```
sudo fdisk -l
```

Среди информации обо всех дисках, наверняка увидите и вашу флешку (например, по объему она будет явно отличаться от жестких дисков).

Если флешка примонтировалась автоматически, чего и происходит по умолчанию, то сначала нужно её отмонтировать (примонтированный раздел система форматировать не даст):

```
sudo umount /dev/sdg1 
```

А затем можно и форматировать:

```
sudo mkdosfs -F 32 /dev/sdg1
```

Готово, пользуйтесь.

Если хочется проделать всё тоже самое, но с использованием графической утилиты, то [GParted](http://aboutubuntu.ru/content/gparted-i-pysdm-legkaya-installyatsiya-novogo-zhestkogo-diska-v-ubuntu) вам в помощь.
