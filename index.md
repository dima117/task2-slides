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

## 2. Кроссбраузерность
{:.fullscreen}

![](pictures/vk-00.png)

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

## Общая разметка - схема1
{:.fullscreen}

![](pictures/scheme-01.png)

## Общая разметка - схема2
{:.fullscreen}

![](pictures/scheme-02.png)

## Общая разметка - схема3
{:.fullscreen}

![](pictures/scheme-03.png)

## Схема решения - 00
{:.fullscreen}

![](pictures/solution-00.png)

## Схема решения - 01
{:.fullscreen}

![](pictures/solution-01.png)

## Схема решения - 02
{:.fullscreen}

![](pictures/solution-02.png)

## Схема решения - 03
{:.fullscreen}

![](pictures/solution-03.png)

## Схема решения - 04
{:.fullscreen}

![](pictures/solution-04.png)

## 2 способа
{:.fullscreen}

![](pictures/2-ways-00.png)

## Стили - 00
{:.fullscreen}

![](pictures/styles-00.png)

## Стили - 01
{:.fullscreen}

![](pictures/styles-01.png)

## [ngrok.com](https://ngrok.com/)<br/><br/>[localtunnel.github.io](https://localtunnel.github.io/www/)
{:.shout}

## Стили - 02 (моб)
{:.fullscreen}

![](pictures/styles-02.png)


## Шкала

## Названия переговорок

## Сотображение событий

## Страница редактирования

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
