---
layout: default
title: Home
nav_order: 1
description: "Руководство по созданию блона на Evo 3, автор Андрей Казунин"
permalink: /
---

# Уроки по созданию блога на Evolution CMS 3

[![CMS Evolution](https://img.shields.io/badge/CMS-Evolution-brightgreen.svg)](https://github.com/evocms-community/evolution) ![PHP version](https://img.shields.io/badge/PHP->=v7.4-green.svg?php=7.4) [![Documentation](https://img.shields.io/badge/Documentation-ready-green)](https://github.com/0test/lessons-evolution-blog)

Демо: [demoblog.kazunin.ru](http://demoblog.kazunin.ru/)

Курс для начинающих, порог входа — знать html/css/php. Желательно в общих чертах понимать, что такое классы.
Разбираем всё, начиная от установки OpenServer/VSCode до финала.

Что на выходе:

- Получите простой, быстрый бложег.
- Поймёте, что такое blade
- Поработаете с контроллерами
- Чуток освоите апи Evolution CMS
- Получите классную основу для сакраментального «уйти в Ларавел»

_Тема дизайна — free for personal and commercial use. Т.е. можно собирать на ней сайты на продажу._

<button class="btn js-toggle-dark-mode">На темную сторону</button>

<script>
const toggleDarkMode = document.querySelector('.js-toggle-dark-mode');

jtd.addEvent(toggleDarkMode, 'click', function(){
  if (jtd.getTheme() === 'dark') {
    jtd.setTheme('light');
    toggleDarkMode.textContent = 'На темную сторону';
  } else {
    jtd.setTheme('dark');
    toggleDarkMode.textContent = 'Вернуться на светлую';
  }
});
</script>

{% link docs/001_Введение. Нужные программы.md %}
{% post_url 001_Введение. Нужные программы %}
[001_Введение. Нужные программы]({% post_url 001_Введение. Нужные программы %})
