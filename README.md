# Документация разработчика


## Функционал


- **Регистрация пользователя**

    Пользователь может заполнить свою анкету, выбирая из выпадающего списка откликающиеся интересы. Пользователь может добавить фотографию

- **Участие в матчинге**

    Пользователь может стать участником random coffee. Приложение будет искать ему подходящего собеседника

- **Обратная связь**

    Пользователь может дать обратную связь по матчингу: насколько ему понравился собеседник, каких собеседников он хочет видеть в будущем


## Технические требования
Минимальные требования к техническому оборудованию:

    ПК:
    Процессор — Intel или AMD, 1,5 ГГц или выше
    Оперативная память не менее 1гб
    Свободная память компьютера – не менее 7 Гб

ПО:

    Docker Engine
#

## Содержание репозитория
- main.py - модуль, отвечающий за обработку комманд и callback data, а также запуск бота
- matching.py - модуль, содержащий функции матчинга пользователей
- messages.py - содержит функции, формирующие сообщения для пользователя
- processing_functions.py - модуль, содержащий функции взаимодействия с данными, рассылок сообщений



Дополнительные файлы:
- photos - директория с хранящимися пользовательскими фотографиями
- dockerfile - файл для создания билда
- requirements.txt - список необходимых библиотек

Файлы-примеры:

    Эти файлы уже содержат данные реальных пользователей чтобы вы могли запустить матчинг без создания дополнительных аккаунтов. Если вы их удалите, будут созданы новые файлы при добавлении пользователей

- participants.csv - файл, содержащий участвующих пользователей
- matching_rate.csv - файл с оценками матчинга от пользователей
- matches.csv - файл с информацией о всех результатах матчинга
- all_users.csv - файл с информацией о всех пользователях, пользовавшихся ботом
#

## Установка
- Склонируйте репозиторий
- В файле main.py вставьте ключ своего бота в 13-ой строке
- Установите Docker engine и docker compose ИЛИ Docker desktop
- Запустите команду `docker-compose up`



#

