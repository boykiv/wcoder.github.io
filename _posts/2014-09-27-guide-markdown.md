---
layout: post
title: Памятка по markdown
date: 2014-09-27 19:44
tags:
- памятка
- markdown
---

## Онлайн-редакторы

* [https://stackedit.io/](https://stackedit.io/)
* [http://gist.github.com/](http://gist.github.com/)
* [http://markable.in/editor/](http://markable.in/editor/)

## Заголовки

Заголовки обособляются хешами (хеш справа для красоты)
От количества хешей зависит уровень заголовка:

```
# Заголовок первого уровня (<h1/>) #
## Заголовок второго уровня (<h2/>) ##
### Заголовок третьего уровня (<h3/>) ###
```

Главный заголовок можно не выделять хешами, а подчеркнуть двойной линией:

```
Погружение в маркдаун
================================================================================
```

Второй по главности заголовок можно не выделять хешами, а подчеркнуть простой линией:

```
Заголовки
--------------------------------------------------------------------------------
```

## Форматирование текста

### Абзацы и переносы

Новый абзац в markdown определяется по наличию пустой строки перед блоком текста.
Для того, чтобы сделать перенос внутри строки, достаточно добавить два пробела перед переносом строки.

### Стилизация текста

* `**Жирный текст**` — **Жирный текст**
* `*Курсивный текст*` — *Курсивный текст*
* `***Жирный курсивный текст***` — ***Жирный курсивный текст***

### Горизонтальная линия

-------------------------------------------
Горизонтальная линия в маркдауне до смешного проста
```
--------------------------------------------------------------------------------

Горизонтальная линия в маркдауне до смешного проста
```

### Вставка ссылок и картинок

* `[Ссылка на котиков](http://placekitten.com/)` — [Ссылка на котиков](http://placekitten.com/)
* `![Картинка с котиком](http://placekitten.com/g/200/300)`

**В большом тексте** удобно вставлять ссылки [сносками][1] как в книгах:

----
[1]: http://placekitten.com/ "Cat happens"

```
**В большом тексте** удобно вставлять ссылки [сносками][1] как в книгах:

----
[1]: http://placekitten.com/ "Cat happens"
```

## Списки

### Обычный ненумерованный список

* один
* два

```
* один
* два
```

### Обычный нумерованный список

1. один
2. два

```
1. один
2. два
```

## Форматирование кода

### Блочное форматирование кода

Для блочного выделения кода достаточно сделать отступ в 4 пробела или один таб. Для такого представления:

```html
<ul class="nav">
    <li><a href="/atom.xml">RSS</a></li>
</ul>
```

Нужно вставить в редактор такой код:

```
<ul class="nav">
    <li><a href="/atom.xml">RSS</a></li>
</ul>
```


## Цитаты

> Мы не поможем людям, делая за них то, что они могли бы сделать сами.

```
> Мы не поможем людям, делая за них то, что они могли бы сделать сами.
```

## Обычный HTML

Если что-то нельзя сделать в маркдауне, то используйте обычный HTML.