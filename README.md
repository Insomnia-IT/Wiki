# Insomnia и её проекты

В данный момент происходит реализация двух будущих проектов для фестиваля "Бессонница".
Здесь будет описана информация о них, а так же API для использования FrontEnd-разработчиками и разработчиками других проектов бессонницы.

## 1. Intronet (Интронет)
### Что это?
Проект предназначен для использования гостями фестиваля. Интронет позволит снабдить гостей необходимой инфоормацией, а так же разгрузить инфоцентр.
### Задачи
1. Обеспечение гостей фестиваля постоянным доступом к необходимым ресурсам:
>Карте фестиваля, информацией о расписании лекториев, мастер классов, меню кафе и иной информации о локациях фестиваля
2. Электронная доска объявлений с поступающими оповещениями гостям фестиваля. А так же, возможность гостям фестиваля самим добавлять необходимые уведомления (посредством обращения в инфоцентр).
3. Обеспечение фестиваля электронным способом голосования за понравившуюся им анимацию, для последующего конкурса зрительских симпатий.

### API
+ [Локации](https://github.com/Insomnia-IT/Wiki/blob/main/intronet-backend/locations.md#%D0%BB%D0%BE%D0%BA%D0%B0%D1%86%D0%B8%D0%B8-%D1%84%D0%B5%D1%81%D1%82%D0%B8%D0%B2%D0%B0%D0%BB%D1%8F)
+ [Тэги]
+ [Доска объявлений](https://github.com/Insomnia-IT/Wiki/blob/main/intronet-backend/noteboard.md#%D0%B4%D0%BE%D1%81%D0%BA%D0%B0-%D0%BE%D0%B1%D1%8A%D1%8F%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B9)
+ [Расписание]
+ [Голосование]

## 2. VP (Волонтёрский проект)
### Что это?
Организационное приложение, для контроля пребывания волонтёров, а так же, обеспечения кухни информацией о кормлении волонтёров с помощью QR-бейджиков.
### Задачи
1. Систематизация информармации о волонтёрах, принадлежности их к той или иной локации.
2. Сбор статистики о нахождении волонтёров на местах, а так же сбор статистики для кухни.
3. Предоставлении кухне информации о возможности кормления волонтёров и их близких родственников.

### API

???

## 3. AvatarGen (секретик)
_В разработке... информация будет дополнена._

## 4. AggreMod (Интеграция с ноушеном, билетёрским сайтом и аналитика)
### Задачи
1. Интеграция с ноушеном и его базами данных, для получения информации о волонтёрах и локациях.
2. Получение информации о билетах с сайта билетёра.
3. Заполнение базы данных полученными данными.
4. API для лёгкой выгрузки данных в иные сервисы бессонницы для последующего их использования.

### API

+ [Notion]
+ [Ticketscloud]
