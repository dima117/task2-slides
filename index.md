---

layout: yandex2

style: |
    /* собственные стили можно писать здесь!! */


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

## Что вас ждет

1. {:.next}О задании
2. {:.next}Как сверстать
3. {:.next}Дополительные критерии
4. {:.next}Ответы на вопросы

## О задании
{:.section}

## 0. Нужно сверстать по макетам две страницы сервиса "Переговорки"
{:.fullscreen}

![](pictures/specs-01.png)

## 1. Адаптивная верстка
{:.fullscreen}

![](pictures/specs-00.png)

## 2. Кроссбраузерность
{:.fullscreen}

![](pictures/browsers-00.png)

## 2. Кроссбраузерность
{:.fullscreen}

![](pictures/browsers-01.png)

<!-- ## 2. Кроссбраузерность
{:.fullscreen}

![](pictures/vk-00.png)
-->

## Почему переговорки?
{:.section}

## Почему переговорки?
{:.fullscreen}

![](pictures/meeting-01.jpg)

## Почему макеты?
{:.section}

## Дизайнеры
{:.images .three}

![](pictures/oshans.jpg)
*Ольга Шанцева*

![](pictures/dashamrt.jpg)
*Даша Мартынюк*

![](pictures/regsmirnova.jpg)
*Регина Смирнова*

## Черновики - десктоп
{:.fullscreen}

![](pictures/draft-00.png)

## Черновики - мобилки
{:.fullscreen}

![](pictures/draft-01.png)

## В итоге &mdash; сложные качественные макеты.
{:.blockquote}

## Как сверстать
{:.section}

## Смотрим макет - desktop
{:.fullscreen}

![](pictures/scheme-02.png)

## Смотрим макет - touch
{:.fullscreen}

![](pictures/scheme-03.png)

## 1. Разметка страницы
{:.section}

### Как сверстать

## Схема решения - X - 00
{:.fullscreen}

![](pictures/x-scheme-00.png)

## Схема решения - X - 01
{:.fullscreen}

![](pictures/x-scheme-01-1.png)

## [ngrok.com](https://ngrok.com/)<br/><br/>[localtunnel.github.io](https://localtunnel.github.io/www/)
{:.shout}

## Схема решения - X - 02
{:.fullscreen}

![](pictures/x-scheme-02.png)

## Схема решения - X - 03
{:.fullscreen}

![](pictures/x-scheme-03.png)

## [CSS и iOS Safari](https://habrahabr.ru/post/332872/)
{:.shout}

## 2. Шкала времени
{:.section}

### Как сверстать

## Шкала - 00
{:.fullscreen}

![](pictures/scale-00-1.png)

## Шкала - 01
{:.fullscreen}

![](pictures/scale-01-1.png)

## 3. Названия переговорок
{:.section}

### Как сверстать

## Смотрим макет - touch
{:.fullscreen}

![](pictures/scheme-03.png)

## Навешиваем класс при скролле
{:.fullscreen}

```js
// область, в которой происходит скролл
var page = document.querySelector('.page');

// панель с названиями переговорок
var aside = document.querySelector('.aside');

page.addEventListener('scroll', function () {
    // если позиция скролла больше ширины панели,
    // добавляем класс 'aside--float'
    aside.classList.toggle('aside--float', page.scrollLeft > 120);
}); 
```

## Стили для панели с названиями
{:.fullscreen}

```cs
.aside--float {

  position: sticky;

  visibility: hidden;
}

.aside--float .room-name {

  display: inline-block;
  
  visibility: visible;
}
```

## 4. Timeline
{:.section}

### Как сверстать

## Иллюстрация

## Классы

## Цикл в CSCC

## [example](https://www.sassmeister.com/gist/59bc49df90effefe881d9b70cedac9ce)
{:.shout}

## 5. Форма
{:.section}

### Как сверстать



## Дополнительные критерии
{:.section}

## Организация и оформление кода

- разбить на части
- одинаковое оформление + прикрутить линтеры

## Автоматизация

автопрефиксер, препроцессоры и конкатенация, режимы для разработки и прода.

## Вопросы?
{:.section}

## Спасибо
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
- {:.skype}dima117a
- {:.mail}dima117a@yandex-team.ru
- {:.github}dima117

<!-- right -->


<!-- 
- {:.twitter}@author
- {:.facebook}author
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
