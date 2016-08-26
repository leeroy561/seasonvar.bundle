Seasonvar Премиум
=================

Plex медиа плагин для сайта http://www.seasonvar.ru.
Позволит вам смотреть ТВ сериалы доступные на сайте и как результат прожить свою жизнь в пустую...

__Требуется активная премиум подписка__ и дейсвующий API ключ.
> Смотри секцию "Настройка" для более подробной информации.

Текущая версия: 1.4
-------------------

Установка
---------

1. Скачать git репозиторий и скопировать его в папку Plug-ins на вашем Plex медиа сервере.
> Library/Application Support/Plex Media Server/Plug-ins

2. Запустить Plex, новый канал 'Seasonvar: Премиум' должен появиться в меню.
> Возможно будет на английском языке. Зависит от локализации.

Установка закончина, далее нужно сконфигурировать плагин.

Конфигурация
------------

Данный плагин __требует__ премиум акаунт и __не будет__ работать без API ключа.

После окончании подписки плагин __перестанет__ работать, так-как сервер перестанет выдавать данные по просроченному ключу.

При повторной активации __премиум__ акаунта конфигурацию проводить не нужно, так как API ключ не изменятся.
> Но на всякий случай рекомендую проверить.

1. Находим API ключ перейдя по ссылке [http://seasonvar.ru/?mod=api](http://seasonvar.ru/?mod=api)
2. Вводим значение ключа в поле ввода "API Key" в настройках канала
3. Последний шаг, активация IP адреса на сайте. Запускаем канал и выбираем 'Latest Serials' / 'Последние сериалы'. Выскакивает сообщение об ошибке - это нормально.
4. Открываем ссылку [http://seasonvar.ru/?mod=api](http://seasonvar.ru/?mod=api) и нажимаем на "Разрешить" возле вашего IP адреса.
5. Перезапускаем канал (Выйти и запустить заного).

На этом конфигурация завершина и все должно работать.