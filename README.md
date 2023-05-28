# WeatherProject
## Текст задания:
Вам необходимо написать ASP.NET Core MVC приложение для загрузки и отображения архивов погодных условий в городе Москве. Оно должно состоять из трёх страниц:
1.	Главная страница, на которой присутствует меню из двух пунктов:
a.	Просмотр архивов погодных условий в городе Москве
b.	Загрузка архивов погодных условий в городе Москве
2.	Страница просмотра архивов погодных условий в городе Москве. На данной странице присутствует постраничная навигация и возможность просмотра погодных условий по:
a.	Месяцам
b.	Годам
3.	Страница загрузки архивов погодных условий в городе Москве. На данной странице мы можем загружать архивы погодных условий в городе Москве. Архив погодных условий представляет собой файл Excel. После загрузки его необходимо разобрать и загрузить в базу данных для дальнейшего отображения на экране 2. Мы можем загружать как один файл Excel, так и несколько за раз. Если файл Excel не подлежит разбору, наше приложение не должно падать.
## Комментарии:
1.	В качестве библиотеки для работы с Excel файлами рекомендуется использовать NPOI.
2.	В качестве ORM для работы с базой данных можно использовать Entity Framework Core.
3.	В качестве базы данных необходимо использовать MSSQL Server 2008 и выше, либо PostgreSQL 9 и выше.
4.	Архивы погодных условий за последние 4 года прилагается к данному задание (Название файла – Weather.Moscow.2010-2014).
## Комментарии от автора:
1.	Не советую использовать Yandex браузер.
2.	На компьютерах с 8 ГБ оперативной памяти может возникать ошибка записи в Базу данных.
3.	В качестве базы данных использована Microsoft SQL Server 2022 (RTM) - 16.0.1000.6 (X64)   
4.	Были использованы библиотеки: NPOI, Microsoft.EntityFrameworkCore,Microsoft.EntityFrameworkCore.Tools, EFCore.BulkExtensions

