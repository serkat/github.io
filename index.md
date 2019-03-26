---
layout: page
title: 11 апреля 2019
excerpt:
comments: true
---

Мы расскажем, как уместили в одном решении 20 различных приложений, которыми пользуется каждая 2-я российская компания! А также, как добились высокого коэффициента «переиспользования» кода… Научим, как расставить приоритеты и выполнить все задачи в срок в условиях многозадачности!

Ведущие JS разработчики компании «Тензор» поделятся уникальным опытом на KlTF 19!

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


<script type="text/javascript" charset="utf-8" async src="https://api-maps.yandex.ru/services/constructor/1.0/js/?um=constructor%3A36ddcdf780866d24a555f5e8156384d51f42ad5c6c33ffb7a74a4f0bbe78e4ed&amp;width=100%25&amp;height=636&amp;lang=ru_RU&amp;scroll=true"></script>


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
