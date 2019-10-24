---

layout: yandex2

style: |
    /* собственные стили можно писать здесь!! */
    .pre-small pre code { font-size: 24px!important; line-height: 48px!important; }
    .pre-big pre code { font-size: 54px !important; line-height: 108px !important; } #  9 lines x 52 symbols
    .big-list { font-size: 80px!important; line-height: 160px!important; }
    .images-w { background-color: #fff !important; }
    .slide-red { border-left: 9px solid #f00 !important; }
    figure.short { width: 480px !important; }
    .text-center { text-align: center !important; }
    img.center { margin: auto !important; }
    img.title { width: 1000px !important; }
    .symfoniacs { background-color: white !important; }
---

# ![](pictures/symfoniacs-spb-logo-version-0.svg){:.logo.title}

## {{ site.presentation.title }}
{:.title}

### Symfoniacs 7 @ ITMO 24 oct 2019

## О докладчике

* Разработчик php 3-7, java 8
* Продвинутый пользователь Symfony 1-4, Zend Framework 1
* Докладчик и организатор митапов Symfoniacs, Москва и Санкт-Петербург

## План ##
{:.contacts}
-------
<!-- left -->

- Зачем исследовать
- Что такое фреймворк
- История
- Статистика
- Дитрибутивы
- Сообщество

<!-- right -->

- Конфигурация
- Инструментарий
- Использование в проде
- Ссылки
- Выводы

## Зачем исследовать ##

**Быстрее и качественнее решать "свои" и "чужие" задачи**
- {:.next}Поддержка кода
- {:.next}Передача другим разработчикам

## Фреймворк ##
{:.blockquote}
## Что такое фреймворк ##

**Платформа, определяющая структуру программной системы**{:.next}

**Платформа, облегчающее разработку и объединение разных компонентов большого программного проекта**{:.next}

**Программная среда**{:.next}

## Предназначение фреймворка ##

- {:.next}Web
- {:.next}RAD - Rapid Api Development
- {:.next}CLI - command line interface
- {:.next}Универсальный (?)

## Типы фреймворков ##

- {:.next}Монолитный
- {:.next}Модульный
- {:.next}Микро
- {:.next}No framework

## Противоречия между предназначением и типом ##

**Монолитный - не универсальный**

**Микро - не имеет определенного предназначения**

**Web - не микро**{:.next}

**No framework - не универсальный**{:.next}

## Зачем исследовать ##

**Архитектурые задачи**
- {:.next}Велосипедофобия
- {:.next}Костылефобия
- {:.next}Легасифобия
- {:.next}Минимальный технологический стэк
- {:.next}Поиск лучшего решения, на замену плохого
- {:.next}Поиск лучшего решения, нужно использовать самое лучшее решение (?)

## История Zend framework 1 vs Symfony 1 ##

**ZF Первый релиз - Март 2006**{:.next}

- {:.next}SF Первый релиз - Октябрь 2005 (-6 месяцев)

**ZF 1.12.20 (последний в 1.x) - Сентябрь 2016**{:.next}

- {:.next}SF 1.5.11 (последний в 1.x) - Март 2018 (+1.5 года)

## История Zend framework 2 vs Symfony 2 ##

**ZF 2.0 - Сентябрь 2012**{:.next}

- {:.next}SF 2.0 - Июль 2011 (-1 год)

**ZF 2.5.3 (последний в 2.x) - Январь 2016**{:.next}

- {:.next}2.8.51 (последний в 2.x) - Апрель 2019 (!) (+3 года)


## История Zend framework 3 vs Symfony 3, 4 ##
 
**ZF 3.0 - Июнь 2016**{:.next}
- {:.next}SF 3.0 - Ноябрь 2015 (-6 месяцев)

**ZF 3.x (последний в 3.x) - ?**{:.next}
- {:.next}SF 3.x - Ноябрь 2021
- {:.next}SF 4.x - Ноябрь 2023

## Скачивания Zend framework vs Symfony ##
 
**ZF ~400 M**{:.next}
**SF ~3.3 B**{:.next}

## Дистрибутивы ##

**zendframework/skeleton-application**{:.next}

- {:.next}Монолитный общего предназначения

**zendframework/zend-expressive-skeleton**{:.next}

- {:.next}микро?

**laminas**{:.next}

- {:.next}???

## Конфигурация zendframework/skeleton-application ##

**php-конфиги?!**{:.next}

**большой список прямых зависимостей**{:.next}

## Как делать выводы ##

**Структура - можно легко ориентироваться и расширять**
**Инструментарий - есть достаточной хороший**
**Среда - Подумали про devops**

## Выводы (про Symfony4) ##

**Структура - 8/10**

- front controller
- application
- kernel
- bundle

**Инструментарий - 9/10**
**Среда - 9/10**

## Выводы (про Zend Framework) ##

**Структура - 6/10?**
**Инструментарий - ?**
**Среда - вроде норм )**

## Пишите свои фреймворки, но и учиться не забывайте!
{.:blockquote}

## Спасибо!
{:.contacts}
-------
<!-- left -->

- {:.telegram} symfoniacs_spb - чат
- {:.telegram} symfoniacs_spb_live - канал

<!-- right -->

- {:.telegram} hanovruslan
- {:.mail} hanov.ruslan@gmail.com
- {:.twitter}@hanovruslan
- {:.vk}hanov.ruslan
- {:.facebook}hanov.ruslan

