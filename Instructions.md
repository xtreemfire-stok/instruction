## Основные команды git

* __git status__ - проверка статуса репозитория
* __git --version__ - показывает версию ПО git
* __git add__ - добавление файлов в индекс
* __git commit__ - фиксация изменений в репозитории
* __git log__ - просмотр журнала коммитов
* __git branch__ - просмотр веток
* __git checkout__ - переключение между ветками
* __git merge__ - слияние веток репозитория
* __git diff__ - просмотр изменений до коммита

## Команды git для работы с удаленными репохиториями

* __git push__ - отправка изменений в удаленный репозиторий
* __git pull__ - получение изменений из удаленного репозитория
* __git clone__ - копирует репозиторий по заданной ссылке

## Рабаота с удаленным репозиторием

1. Создать аккаунт на Github.com
2. Создать локальный репозиторий
3. "Подружить" локальный и удаленный репозитории. Github при создании нового репозитория подскажет ка к это можно сделать.
4. Отправить (push) локальный репозиторий в удаленный (на GIthub), при этом (в первый раз) нужно будет авторизоваться нан удаленном репозитории.
5. Провести изменения "с другого компьютера".
6. Выкачать (pull) актуальное состояние из удаленного репозитория.

## Как сделать pull request

1. Делаем форк (fork) интересующего нас репозитория.
2. Делаем git clone для создания копии на локальном компьютере.
3. Создаем ветку с предлагаемыми изменениями.
4. Производим изменения только в этой ветке.
5. Отправляем эти изменения на сой аккаунт (push).
6. В окне на Github появляется возможность отправить pull request.
