# Links.pt

Список ссылок которые могут потеряться, забыться. А также полезные при обучении/работе ссылки

<!-- ## Поиск

<div style="display: flex; gap: 10px">
<a href="#letter_ru_1">А</a>
<a href="#letter_ru_2">Б</a>
<a href="#letter_ru_3">В</a>
<a href="#letter_ru_4">Г</a>
<a href="#letter_ru_5">Д</a>
<a href="#letter_ru_6">Е</a>
<a href="#letter_ru_7">Ё</a>
<a href="#letter_ru_8">Ж</a>
<a href="#letter_ru_9">З</a>
<a href="#letter_ru_10">И</a>
<a href="#letter_ru_11">Й</a>
<a href="#letter_ru_12">К</a>
<a href="#letter_ru_13">Л</a>
<a href="#letter_ru_14">М</a>
<a href="#letter_ru_15">Н</a>
<a href="#letter_ru_16">О</a>
<a href="#letter_ru_17">П</a>
<a href="#letter_ru_18">Р</a>
<a href="#letter_ru_19">С</a>
<a href="#letter_ru_20">Т</a>
<a href="#letter_ru_21">У</a>
<a href="#letter_ru_22">Ф</a>
<a href="#letter_ru_23">Х</a>
<a href="#letter_ru_24">Ц</a>
<a href="#letter_ru_25">Ч</a>
<a href="#letter_ru_26">Ш</a>
<a href="#letter_ru_27">Щ</a>
<a href="#letter_ru_28">Э</a>
<a href="#letter_ru_29">Ю</a>
<a href="#letter_ru_30">Я</a>
</div>

<div style="display: flex; gap: 10px">
<a href="#letter_eng_1">A</a>
<a href="#letter_eng_2">B</a>
<a href="#letter_eng_3">C</a>
<a href="#letter_eng_4">D</a>
<a href="#letter_eng_5">E</a>
<a href="#letter_eng_6">F</a>
<a href="#letter_eng_7">G</a>
<a href="#letter_eng_8">H</a>
<a href="#letter_eng_9">I</a>
<a href="#letter_eng_10">J</a>
<a href="#letter_eng_11">K</a>
<a href="#letter_eng_12">L</a>
<a href="#letter_eng_13">M</a>
<a href="#letter_eng_14">N</a>
<a href="#letter_eng_15">O</a>
<a href="#letter_eng_16">P</a>
<a href="#letter_eng_17">Q</a>
<a href="#letter_eng_18">R</a>
<a href="#letter_eng_19">S</a>
<a href="#letter_eng_20">T</a>
<a href="#letter_eng_21">U</a>
<a href="#letter_eng_22">V</a>
<a href="#letter_eng_23">W</a>
<a href="#letter_eng_24">X</a>
<a href="#letter_eng_25">Y</a>
<a href="#letter_eng_26">Z</a>
</div>

# Russian

<a id="letter_ru_4"></a>
### Г

- [Git](/data/git.md)

<a id="letter_ru_5"></a>
### Д

- [Docker](/data/docker.md)

<a id="letter_ru_16"></a>
### О

- [Red Hat Openshift](/data/red-hat-openshift.md)

# English

<a id="letter_ru_4"></a>
### D

- [Docker](/data/docker.md)


<a id="letter_ru_7"></a>
### G

- [Git](/data/git.md)

<a id="letter_ru_15"></a>
### O

- [Red Hat Openshift](/data/red-hat-openshift.md) -->

## Содержание

Все ссылки разбиты на темы и разделы. Какие-то из них ведут на подстраницы, а какие-то сразу на необходимые порталы или сервисы.

### Основное

- [Документация всего](https://devdocs.io/)
- [Docker (раздел)](/data/docker.md)
- [Git (раздел)](/data/git.md)
- [Терминал (раздел)](/data/terminal.md)

### Обучение

- [Red Hat Openshift (раздел)](/data/red-hat-openshift.md)
- [Паттерны разработки (раздел)](/data/development-patterns.md)
- [Базы Данных (раздел)](/data/databases.md)
- [API (раздел)](/data/api.md)
- [Laravel (раздел)](/data/laravel.md)

## Добавление новых ссылок

Если у вас есть желание добавить какую-либо ссылку в репозиторий, это можно сделать самостоятельно, при помощи pull request. Это облегчит мне работу и гарантирует что ссылка будет добавлена, а не забыта и потеряна.

### Правила добавления ссылок

Все ссылки группируются в разделы (если таковы имеются). При добавлении ссылки ее необходимо поместить (или создать новый) в соответствующий раздел. Например: Ссылка на документацию к Docker входит в раздел docker.

#### Добавление раздела

Для добавления раздела создайте соответствующий `.md` файл в папке `/data/`, придерживаясь английского наименования. Затем добавьте туда необходимые ссылки. Последним действием, добавьте ссылку на раздел в общее содержание к наиболее подходящей теме (например "обучение"), с постфиксом `(раздел)`. Главный файл находится в корне, под названием `README.md`

#### Добавление одиночных ссылок

Если ссылку невозможно объеденить в какой-либо логический раздел, до добавьте ее сразу в корень, в `README.md` файл, не добавляя никаких постфиксов. Старайтесь отделять ссылки и разделы в главном файле, разделяя их на соответствующие разделы.

#### Форматирование

Все файлы в папке `/data/` начинаются с заголовка, который соответствует разделу. Заголовок в `.md ` файлах пишется через символ `#` (колличество символов соответствует весу заголовка). Затем идут разделы или темы (или сразу ссылки если таковых нет). 
Ссылки оформляются через немаркированные списки:

```md
# Тема

## Подтема

- [Текст ссылки](Сама ссылка)
```

Пример оформления:

```md
# Laravel

- [Официальный сайт](https://laravel.com)

## Документация

- [Перевод на русском языке](https://laravel.com)
```