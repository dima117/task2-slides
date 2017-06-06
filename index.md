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

1. {:.next}Нумерованный список
2. {:.next}Нумерованный список
3. {:.next}Нумерованный список
4. {:.next}Нумерованный список

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

![](themes/yandex2/images/image-right.svg)
{:.image-right}

Это дополнительный текст. Он переносится на вторую строку.

**Главная мысль**

- это список - элемент 1
- элемент 2
- элемент 3

### Источник

## Заголовок

<!-- библиотека пиктограмм https://patterns.yandex-team.ru/presentations?typeIn=icons -->

![](themes/yandex2/images/icons.svg)
{:.icon-left}

Это дополнительный текст. Он переносится на вторую строку.

- это список - элемент 1
- элемент 2
- элемент 3

### Источник

## Заголовок
{:.icons}

<!-- библиотека пиктограмм https://patterns.yandex-team.ru/presentations?typeIn=icons -->

![](themes/yandex2/images/icons.svg)
*Текст*

![](themes/yandex2/images/icons.svg)
*Текст*

![](themes/yandex2/images/icons.svg)
*Текст*

### Источник

## Заголовок
{:.icons .four}

<!-- библиотека пиктограмм https://patterns.yandex-team.ru/presentations?typeIn=icons -->

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

<!-- библиотека пиктограмм https://patterns.yandex-team.ru/presentations?typeIn=icons -->

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

![](themes/yandex2/images/images-fullscreen.svg)

<figure markdown="1">
Первый абзац текста

Второй абзац текста - более длинный, чем первый для переноса на несколько строк
</figure>

## Even Tables

|  Locavore     |  Umami       |  Helvetica |  Vegan     |
+---------------|--------------|------------|------------+
|  Fingerstache<br/>The second line |  Kale        |  Chips     |  Keytar    |
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

Пояснение для кода.

```js
var i, j, over, data = new Array(2, 34, 4, 0, 234, 5);

for(i = 1; i < data.length; i++) {
    over = data[i]; 
    for(j = i - 1; j >= 0 && data[j] > over; j--) {
        data[j + 1] = data[j];
    }
    data[j+1] = over;
}
alert(data.join(','));
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

## Этот заголовок будет скрыт
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

</figure>

<figure markdown="1">

### Author Name 2

Разработчик интерфейсов

</figure>

<!-- left -->
- {:.skype}author
- {:.mail}author@yandex-team.ru
- {:.github}author

<!-- right -->
- {:.twitter}@author
- {:.facebook}author
