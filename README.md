[advicerBot]
===============

Бот для мессенджера Telegram, созданный для удобства поиска информации о фильмах, рекомендации, лучших фильмов по общей статистике и т.п.

===============

Бот:
Название - advicerBot
Создатель - Евшина Яна
Платформа - Telegram
Парсер - BeautifulSoup4
Язык программирования - Python 3.6.2
База Данных - www.kinopoisk.ru, www.afisha.ru

===============

Список команд:

/start - Начало работы бота

Список основных триггеров:

Поиск - Осуществление поиска информации по фильму
Совет - Вызов меню со следующими за ним пунктами
Из топа - Случайный фильм из топ-500 списка сайта www.kinopoisk.ru
Случайный - Случайный фильм из БД www.afisha.ru
Фильтры - Вызов меню для выбора фильтров для рекомендации фильма
К началу - Возврат к стартовому меню (Идентично команде '/start')
По новой "Рандом" - повторный триггер "Случайный" (Идентично триггеру 'Случайный')

===============

Конечный результат представлет собой сообщение от бота, содержащее:
-Изображение фильма
-Название фильма
-Год выпуска фильма
-Жанры фильма
-Режисёр фильма
-Оригинальное название фильма
-Длительность фильма
-Страна фильма
-Ссылка на (www.kinopoisk.ru / www.afisha.ru) - страницу фильма
-Ссылка на трейлер фильма на сайте www.youtube.com
-Ссылка на возможный просмотр фильма на сайте www.hdrezka.ru
