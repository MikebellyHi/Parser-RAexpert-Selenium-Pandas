# Parser-RAexpert-Selenium-Pandas
small parser to parsing the emitents (obligations) and main information of these 

Этот парсер учебный (заказ с фриланса), но может оказаться полезным для некоторого рода специалистов, формирующих большие датасеты в финансовой сфере
Способ работы:
С помощью библиотеки Selenium парсер отбирает с сайта об эмитентах, выпустивших облигации такие данные, как:
Название эмитента
Рейтинг
Прогноз
Дата обновления рейтинга
ИНН
Регион
Отрасль

Так как библиотека Selenium работает в большинстве случае не стабильно, единственным решением проблемы является расширять открывающееся окно браузера для эмуляции действий пользователя
до полного окна (на весь экран)

Помимо этого,  с помощью Pandas формируется датафрейм из найденных данных + они записываются в csv-file
