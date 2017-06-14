---

layout: yandex2

style: |
    /* собственные стили можно писать здесь!! */

    .slide code .nt,    /* html tags */
    .slide code .nc,    /* css class */
    .slide code .nf     /* id */
    {   
        font-weight: normal !important;
        color: red !important;
    }
    
    .slide code .na     /* html attribute name */
    {
        color: #FF0000 !important;
    }  
    
    .slide code .nx     /* variables */      
    {
        color: #3878BE !important;
    }

    .slide code .s,    /* string */
    .slide code .s1    /* string */
    {
        color: #9E64A9 !important;
    }

    .slide code .mi,   /* number */
    .slide code .mf    /* number */
    {
        color: #3878BE !important;
    }

    .slide code .c,    /* comments */
    .slide code .c1    /* comments */
    {
        color: #7F7F7F !important;
    }

    .slide code .k,     /* keywords */
    .slide code .kd,    /* keywords */
    .slide code .kc,    /* keywords */
    .slide code .nb     /* keywords */
    {
        color: #5BCD9D !important;
        font-weight: normal !important;
    }    
    
    .slide code .nl     /* css property */
    {
        color: #3878BE !important;
    }

    .slide code .no,     /* css property value */
    .slide code .sx      /* css property value */
    {
        color: red !important;
    }
    
    /*** для темных слайдов ***/
    
    .slide.black,
    .slide.black h2
    {
        background-color: #333;
        color: white !important;
        font-weight: normal !important;
    }

    .slide.black code .nt,    /* html tags */
    .slide.black code .nc,    /* css class */
    .slide.black code .nf     /* id */
    {   
        font-weight: normal !important;
        color: lime !important;
    }
    
    .slide.black code .na     /* html attribute name */
    {
        color: #FFCC00 !important;
    }  
    
    .slide.black code .nx     /* variables */      
    {
        color: #9E64A9 !important;
    }

    .slide.black code .s,    /* string */
    .slide.black code .s1    /* string */
    {
        color: #72C3E0 !important;
    }
    
    .slide.black code .mi,   /* number */
    .slide.black code .mf    /* number */
    {
        color: #5BCD9D !important;
    }

    .slide.black code .c,    /* comments */
    .slide.black code .c1    /* comments */
    {
        color: #FC6767 !important;
    }

    .slide.black code .k,     /* keywords */
    .slide.black code .kd,    /* keywords */
    .slide.black code .kc,    /* keywords */
    .slide.black code .nb     /* keywords */
    {
        color: #9E64A9 !important;
        font-weight: normal !important;
    } 
    
    .slide.black code .nl     /* css property */
    {
        color: white !important;
    }

    
    .slide.black code .no,     /* css property value */
    .slide.black code .sx      /* css property value */
    {
        color: #FFCC00 !important;
    }
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
{% if site.author %}
<p>{{ site.author.name }}{% if site.author.position %}, {{ site.author.position }}{% endif %}</p>
{% endif %}

{% if site.author2 %}
<p>{{ site.author2.name }}{% if site.author2.position %}, {{ site.author2.position }}{% endif %}</p>
{% endif %}

</div>

## Название раздела
{:.section}

### Верхний колонтитул

## Длинная цитата с переносом на несколько строк
{:.blockquote}

### Источник

## Заголовок

Основной текст

**Главная мысль на две строки.**

- маркированный список
- маркированный список

1. Нумерованный список
2. Нумерованный список

### Источник

## Список

Элементы появляются по очереди

1. {:.next}Нумерованный список
2. {:.next}Нумерованный список
3. {:.next}Нумерованный список
4. {:.next}Нумерованный список

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

## Таблицы

|  Locavore     |  Umami       |  Helvetica |  Vegan     |
+---------------|--------------|------------|------------+
|  Fingerstache<br/>The second line |  Kale        |  Chips     |  Keytar    |
|  Sriracha     |  Gluten-free |  Ennui     |  Keffiyeh  |
|  Thundercats  |  Jean        |  Shorts    |  Biodiesel |
|* Terry        |* Richardson  |* Swag      |* Blog      |

Дополнительный текст под таблицей.

### Источник

## Исходный код (html)

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

## Исходный код (js)

Пояснение для кода.

```js
var i, j, over, data = new Array(2, 34.12, 4.7, 0, 234, 5);
var test = false;

for(i = 1; i < data.length; i++) {
    over = data[i]; 
    for(j = i - 1; j >= 0 && data[j] > over; j--) {
        data[j + 1] = data[j];
    }
    data[j+1] = over;
}
alert(data.join(','));
```

## Исходный код (css)

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

## Исходный код (html)
{:.black}

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

## Исходный код (js)
{:.black}

Пояснение для кода.

```js
var i, j, over, data = new Array(2, 34.12, 4.7, 0, 234, 5);
var test = false;

for(i = 1; i < data.length; i++) {
    over = data[i]; 
    for(j = i - 1; j >= 0 && data[j] > over; j--) {
        data[j + 1] = data[j];
    }
    data[j+1] = over;
}
alert(data.join(','));
```

## Исходный код (css)
{:.black}

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
// исходный код (на весь экран)

var x = 10;
for (var i = 0; i < x; i++) {
    console.log('hello!');
}
```

## Контакты 
{:.contacts}

{% if site.author %}

<figure markdown="1">

### {{ site.author.name }}

{% if site.author.position %}
{{ site.author.position }}
{% endif %}

</figure>

{% endif %}

{% if site.author2 %}

<figure markdown="1">

### {{ site.author2.name }}

{% if site.author2.position %}
{{ site.author2.position }}
{% endif %}

</figure>

{% endif %}

<!-- разделитель контактов -->
-------

<!-- left -->
- {:.skype}author
- {:.mail}author@yandex-team.ru
- {:.github}author

<!-- right -->
- {:.twitter}@author
- {:.facebook}author

<!-- 

- {:.mail}author@yandex-team.ru
- {:.phone}+7-999-888-7766
- {:.github}author
- {:.bitbucket}author
- {:.twitter}@author
- {:.telegram}author
- {:.skype}author
- {:.instagram}author
- {:.facebook}author
- {:.vk}@author
- {:.ok}@author

-->
