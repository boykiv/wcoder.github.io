---
layout: post
title: Изменение расположения стандартных папок пользователя
date: 2015-02-27 03:48
tags: памятка, linux, linux mint, elementary os, ubuntu
---

Редактируем файл:

``` bash
vim ~/.config/user-dirs.dirs
```

```
# This file is written by xdg-user-dirs-update
# If you want to change or add directories, just edit the line you're
# interested in. All local changes will be retained on the next run
# Format is XDG_xxx_DIR="$HOME/yyy", where yyy is a shell-escaped
# homedir-relative path, or XDG_xxx_DIR="/yyy", where /yyy is an
# absolute path. No other format is supported.
# 
XDG_DESKTOP_DIR="$HOME/Рабочий стол"
XDG_DOWNLOAD_DIR="$HOME/Загрузки"
XDG_TEMPLATES_DIR="$HOME/Шаблоны"
XDG_PUBLICSHARE_DIR="$HOME/Общедоступные"
XDG_DOCUMENTS_DIR="$HOME/Документы"
XDG_MUSIC_DIR="/media/data/Music"
XDG_PICTURES_DIR="/media/data/Pictures"
XDG_VIDEOS_DIR="$HOME/Видео"
```
