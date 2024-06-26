<html lang="ru">
<head>
    <meta charset="UTF-8">
    <h1>Официальный производственный календарь РФ с 2013 года</h1>
</head>
<body>
    <p>В результате тестов python библиотеки holidays заметил нестыковки с официальным календарем РФ (<a href="holidays_library_test.ipynb">holidays_library_test.ipynb</a>).</p>
    <p>В итоге решил сделать свою таблицу дат на базе лучшего производственного календаря в рунете - это <a href="http://xmlcalendar.ru/" target="_blank">http://xmlcalendar.ru/</a>. Обновления на следующий год не задерживаются и выкатываются осенью текущего года.</p>
    <p>Holidays_list.ipynb - парсит данные из источника с 2013 года (включая следующий год, если уже выложены данные), дополнительно создает таблицу дат и сохраняет все в файлы:</p>
    <ul>
        <li>holidays_titles.csv - наименования официальных праздников</li>
        <li>holidays_list.csv - таблица праздничных, перенесенных и сокращенных рабочих дней</li>
        <li>dates_table.csv - расширенная таблица дат</li>
    </ul>
    <h2>Таблица дат с учетом праздников, выходных и перенесенных рабочих дней с 2013 года</h2>
    <p>Итоговая таблица дат доступна по <a href="dates_table.csv" download>этой ссылке</a>.</p>
    <p>Эти данные могут быть полезны для:</p>
    <ul>
        <li>Использования в качестве готовой российской таблицы дат</li>
        <li>Планирования рабочих и выходных дней в организациях и предприятиях</li>
        <li>Создания и поддержки актуальных производственных календарей в корпоративных системах</li>
        <li>Учета рабочего времени и отпусков</li>
        <li>Анализа исторических данных по рабочим и выходным дням</li>
    </ul>

</body>
</html>
