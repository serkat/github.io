---
layout: page
title: 11 апреля 2019
excerpt:
comments: true
---

Ждём тебя на нереальной тусовке - Kaliningrad Tensor Forum! 
Впервые мы собираемся в Калининграде с коллегами - единомышленниками и активно обсуждаем актуальные вопросы. 
А за плечами уже Рыбинск, Уфа, Тюмень, Казань и Кострома. 
В этот раз митап посвящён оптимизации запросов в PostgreSQL и ускорению JS кода. А “на закуску” поговорим о способах организации процесса разработки в двух крупных компаниях.

Для первых 30-ти зарегистрировавшихся after-party за счет компании!

[**Регистрируйся**][register] и приходи – мы ждем тебя!
	

Доклады
-------

<ul class="post-list">
{% for post in site.categories.talks %}
  {% if post.author %}
    {% capture authorslist %}
      {% for a in post.author %}
        {% assign author = site.data.authors[a] %}
        {% if author %} {{ author.name }}{% if author.company %}, {{ author.company }}{% endif %}{% endif %}{% unless forloop.last %};{% endunless %}
      {% endfor %}
    {% endcapture %}
  {% endif %}
  {% if post.announce %}
  <li><a href="{{ site.url }}{{ post.url }}"><b>{{ post.title }}</b><br/>{{ authorslist }}</a></li>
  {% endif %}
{% endfor %}
</ul>

Когда
-----

Итак, 11 апреля в 18:00 состоится первая встреча программистов в рамках KlTF 2019. На все доклады отведено 3 часа. Между выступлениями запланирован кофе-брейк, чтобы вы могли перекусить. Для первых 30-ти зарегистрировавшихся after-party за счет компании!

Дата: 11/04/2019, четверг.

Время: с 18.00 до 21.00.

__Вход – free.__


Где
---

Встреча пройдет в гостинице «Holiday Inn», Вход через отель, 1 этаж. По адресу: ул. Виктора Гюго, 1.

Маршрут от остановки общественного транспорта указан на карте.

Места для парковки автомобилей указаны на карте зеленым цветом.

Контактные телефоны: +7(909) 249-11-00 Мария



<iframe src="https://yandex.ru/map-widget/v1/?um=constructor%3A54bbc84b47dbbdba97076108d0f4a32cba9e621d88676d50523ad31942878da9&amp;source=constructor" width="100%" height="720" frameborder="0"></iframe>


<!--
<ul class="post-list">
{% for post in site.posts limit:10 %}
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span></a></article></li>
{% endfor %}
</ul>
-->

[register]: /register/
<!-- [place]:  -->
[tensor]: http://tensor.ru/
[speakers]: /speakers/
