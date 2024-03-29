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

### Stack&Technology
*Backend*:
1. .NET 6
2. ASP.NET WebApi
3. EntityFramework Core
4. Automapper
5. Autofac
6. PostgreSQL

*FrontEnd*:
1. React 18;
2. TypeScript;
3. Sass;
4. Chakra-UI;
5. Cellx (state manager);
6. Dexie

### API
+ [Локации](https://github.com/Insomnia-IT/Wiki/blob/main/intronet-backend/locations.md#%D0%BB%D0%BE%D0%BA%D0%B0%D1%86%D0%B8%D0%B8-%D1%84%D0%B5%D1%81%D1%82%D0%B8%D0%B2%D0%B0%D0%BB%D1%8F-%D0%B8%D1%85-%D1%82%D1%8D%D0%B3%D0%B8-%D0%B8-%D0%BD%D0%B0%D0%BF%D1%80%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F)[, их тэги](https://github.com/Insomnia-IT/Wiki/blob/main/intronet-backend/locations.md#%D1%82%D1%8D%D0%B3%D0%B8-%D0%BB%D0%BE%D0%BA%D0%B0%D1%86%D0%B8%D0%B9)[ и направления](https://github.com/Insomnia-IT/Wiki/blob/main/intronet-backend/locations.md#%D0%BD%D0%B0%D0%BF%D1%80%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F-%D0%BB%D0%BE%D0%BA%D0%B0%D1%86%D0%B8%D0%B9)
+ [Доска объявлений](https://github.com/Insomnia-IT/Wiki/blob/main/intronet-backend/noteboard.md#%D0%B4%D0%BE%D1%81%D0%BA%D0%B0-%D0%BE%D0%B1%D1%8A%D1%8F%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B9) [и категории записей](https://github.com/Insomnia-IT/Wiki/blob/main/intronet-backend/noteboard.md#%D0%BC%D0%B5%D1%82%D0%BE%D0%B4%D1%8B-%D0%BA%D0%B0%D1%82%D0%B5%D0%B3%D0%BE%D1%80%D0%B8%D0%B9-%D0%B7%D0%B0%D0%BF%D0%B8%D1%81%D0%B5%D0%B9)
+ [Расписание](https://github.com/Insomnia-IT/Wiki/blob/main/intronet-backend/timetable.md#%D1%80%D0%B0%D1%81%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BB%D0%BE%D0%BA%D0%B0%D1%86%D0%B8%D0%B9)
+ [Статьи](https://github.com/Insomnia-IT/Wiki/blob/main/intronet-backend/pages.md#%D0%BC%D0%B5%D1%82%D0%BE%D0%B4%D1%8B-%D1%81%D1%82%D0%B0%D1%82%D0%B5%D0%B9)
+ [Голосование]
+ [Файлы](https://github.com/Insomnia-IT/Wiki/blob/main/intronet-backend/attachments.md#%D1%84%D0%B0%D0%B9%D0%BB%D0%B8%D0%BA%D0%B8)

## 2. Кормитель + админка
### Что это?
Организационное приложение, для контроля пребывания волонтёров, а так же, обеспечения кухни информацией о кормлении волонтёров с помощью QR-бейджиков.
### Задачи
1. Систематизация информармации о волонтёрах, принадлежности их к той или иной локации.
2. Сбор статистики о нахождении волонтёров на местах, а так же сбор статистики для кухни.
3. Предоставлении кухне информации о возможности кормления волонтёров и их близких родственников.

### API

???

## 3. AvatarGen (секретик)
Генератор аватарок. Берёт рамку и накладывает на отрпавленное фото. Фото сжимает или растягивает под ближайший экземпляр рамки.

Код команд КРАЙНЕ сырой и написан в спешке.

### Stack&Technology
*Backend*:
1. .NET 6
2. ASP.NET WebApi
3. Automapper
4. Autofac
5. VkNet
6. SixLabors.ImageSharp

## 4. AggreMod (Интеграция с ноушеном, билетёрским сайтом и аналитика)
### Задачи
1. Интеграция с ноушеном и его базами данных, для получения информации о волонтёрах и локациях.
2. Получение информации о билетах с сайта билетёра.
3. Заполнение базы данных полученными данными.
4. API для лёгкой выгрузки данных в иные сервисы бессонницы для последующего их использования.

### API

+ [Notion](https://github.com/Insomnia-IT/Wiki/blob/main/aggremod/notion.md#%D0%B8%D0%BD%D1%82%D0%B5%D0%B3%D1%80%D0%B0%D1%86%D0%B8%D1%8F-%D1%81-notion)
+ [Ticketscloud]
