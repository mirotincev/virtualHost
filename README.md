# virtualHost
Создание виртуальных хостов на mac под nginx,
путь для сайта можно изменить в createVirtualHost.sh опционально находится в /Users/$USER/Sites

version 1.0.0:

1. Запуск скрипта
./createVirtualHost.sh 

2 Будет задано не сколько вопросов
- Название проекта без домена первого уровня
- Далее домен первого уровня, исключительно для удобства
- Потом спросит какой проект будет на данный момент всего 4 вариант [symfony, laravel, html, php]
- Запрос root пароля

3 Что делает скрипт
- Скрипт создаст папки
- Пропишет конфиги в nginx
- Пропишет host в etc/hosts

И на этом все закончится, можно продолжить разработку :)
И радоваться жизни



