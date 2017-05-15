---

layout: yandex2

style: |
    div {}
---

# ![](themes/yandex2/images/logo-{{ site.presentation.lang }}.svg){:.logo}

## {{ site.presentation.title }}
{:.title}

### ![](themes/yandex2/images/title-logo-{{ site.presentation.lang }}.svg){{ site.presentation.service }}

{% if site.presentation.nda %}
![](themes/yandex2/images/title-nda.svg)
{:.nda}
{% endif %}

<div class="authors">
	<p>{{ site.author.name }}, {{ site.author.position }}</p>
</div>

## Название раздела
{:.section}

### Верхний колонтитул

## Длинная цитата с переносом на несколько строк
{:.blockquote}

### Источник

## Заголовок

Основной текст

**Главная мысль на две строки. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod**

- маркированный список
- маркированный список

1. Нумерованный список
2. Нумерованный список

### Источник

## Пример уменьшения высоты нижнего блока из-за заголовка в две строки

Основной текст

**Главная мысль**

- маркированный список
- маркированный список

1. Нумерованный список
2. Нумерованный список

### Источник

## Список

Элементы появляются по очереди

1. *Нумерованный список*{:.next}
2. *Нумерованный список*{:.next}
3. *Нумерованный список*{:.next}
4. *Нумерованный список*{:.next}

### Источник


## Заголовок
{:.images}

![](themes/yandex2/images/images-one.svg)

### Источник

## Заголовок
{:.images .two}

![](themes/yandex2/images/images-two.svg)
*Текст*

![](themes/yandex2/images/images-two.svg)
*Текст*

### Источник

## Заголовок
{:.images .three}

![](themes/yandex2/images/images-three.svg)
*Текст*

![](themes/yandex2/images/images-three.svg)
*Текст*

![](themes/yandex2/images/images-three.svg)
*Текст*

### Источник

## Заголовок
{:.icons}

![](themes/yandex2/images/icons.svg)
*Текст*

![](themes/yandex2/images/icons.svg)
*Текст*

![](themes/yandex2/images/icons.svg)
*Текст*

### Источник

## Заголовок
{:.icons .four}

![](themes/yandex2/images/icons.svg)
*Текст*

![](themes/yandex2/images/icons.svg)
*Текст*

![](themes/yandex2/images/icons.svg)
*Текст*

![](themes/yandex2/images/icons.svg)
*Текст*

### Источник

## Заголовок
{:.icons .five}

![](themes/yandex2/images/icons.svg)
*Текст*

![](themes/yandex2/images/icons.svg)
*Текст*

![](themes/yandex2/images/icons.svg)
*Текст*

![](themes/yandex2/images/icons.svg)
*Текст*

![](themes/yandex2/images/icons.svg)
*Текст*

### Источник

## Заголовок будет скрыт
{:.fullscreen}

![](themes/yandex2/images/images-fullscreen.svg)

## Заголовок будет скрыт
{:.fullscreen}

![](themes/yandex2/images/images-fullscreen.jpg)

<figure markdown="1">
Первый абзац текста

Второй абзац текста - более длинный, чем первый для переноса на несколько строк
</figure>

## Even Tables

|  Locavore     |  Umami       |  Helvetica |  Vegan     |
+---------------|--------------|------------|------------+
|  Fingerstache |  Kale        |  Chips     |  Keytar    |
|  Sriracha     |  Gluten-free |  Ennui     |  Keffiyeh  |
|  Thundercats  |  Jean        |  Shorts    |  Biodiesel |
|* Terry        |* Richardson  |* Swag      |* Blog      |

It’s good to have information organized.

### Источник

## Code Samples (html)

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Shower</title> <!--Comment-->
    <link rel="stylesheet" href="screen.css">
</head>
<body>Hello!</body>
</html>
```

## Code Samples (js)

```js
var x = 10;
for (var i = 0; i < x; i++) {
    console.log('hello!');
}
```

## Code Samples (css)

```css
.head {
    background-color: yellow;
}

.head__logo {
    background-image: url(images/logo.svg);
}

#test, body {
    font-weight: bold;
}

```

## &nbsp;
{:.fullscreen}

```js
// fullscreen code

var x = 10;
for (var i = 0; i < x; i++) {
    console.log('hello!');
}
```

## Контакты 
{:.contacts}

<figure markdown="1">

### {{ site.author.name }}

{{ site.author.position }}

- *author*{:.skype}
- *author@yandex-team.ru*{:.mail}
- *@author*{:.twitter}
- author{:.vk}
- author{:.facebook}

</figure>

## Test

### Вводный текст (первый уровень текста)

*  Второй уровень текста
	* Третий уровень текста (буллиты)

	1. Четвертый уровень текста

## Shower Key Features

1. Built on HTML, CSS and vanilla JavaScript
2. All modern browsers are supported
3. Slide themes are separated from engine
4. Fully keyboard accessible
5. Printable to PDF

{:.note}
Shower ['ʃəuə] noun. A person or thing that shows.


## Plain Text on Your Slides

Lorem ipsum dolor sit amet, consectetur [adipisicing](#all-kind-of-lists) elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, *quis nostrud* exercitation ullamco laboris **nisi ut aliquip** ex ea commodo consequat. Duis aute irure <i>dolor</i> in reprehenderit in voluptate velit esse cillum <b>dolore</b> eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in `<culpa>` qui officia deserunt mollit anim id est laborum.

## All Kind of Lists

1. Simple lists are marked with bullets
2. Ordered lists begin with a number
3. You can even nest lists one inside another
    - Or mix their types
    - But do not go too far
    - Otherwise audience will be bored
4. Look, seven rows exactly!

## Serious Citations

<figure markdown="1">

> Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia.

<figcaption>Marcus Tullius Cicero</figcaption>
</figure>

## Pictures
{:.cover #Picture}

![](pictures/picture.jpg)
<!-- photo by John Carey, fiftyfootshadows.net -->

## **You can even shout this way**

## Inner Navigation

1. Lets you reveal list items one by one
2. …To keep some key points
3. …In secret from audience
4. …But it will work only once
5. …Nobody wants to see the same joke twice

## ![](http://shwr.me/pictures/logo.svg) [See more on GitHub](https://github.com/shower/shower/)
{:.shout #SeeMore}
