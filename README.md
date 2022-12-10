# gb_1234
## hello

*hello, world*


qwertyu

# Git

*Git — распределённая система управления версиями*

* 1)Базовые команды


Для работы с Git через  Visual Studio Code мы используем упраление через команты в терминале. 

*Запуск и работа с Git*

Что бы начать работу необходимо создание репозитория. Для этого необходимо в терминале ввести ***git init***. 

Для добавления файла в систему отслеживания необходимо ввести ***git add name_file***(необходимо сохранение текущего файла в VS)

Для отслеживания информации о текущем состяонии необходимо ввести ***git status***.

* 2)Работа с логами 

Для создания нового коммита необходимо ввести **git commit -m "name"**

Отследить текущие коммиты и их код  мы можем используя команду **git log**

Что бы из текущего коммита перейти в следущий мы используем **git checkout (первые 4 цифры нужного коммита**

Для возвращения к исходному коммиту используем **git checkout master**

* 3)Работа с ветками


В Git можно создать отдельные ведтки для внесений изменений с работы с отделньым участком файла. 

Для создания ветки необходимо ввести **git branch name**

Для удаления ветки необходимо использовать **git branch -d Name**, если изменения не сохранены, но требуется удаление ветки изменяем на **git branch -D name**

Отследить текущие ветки можно используя команду **git branch**

При необхидмо слияния веток мы используем **git merge name(ветки которую необхоимо добавить)**, при этом необходимо проверить в какой ветке мы находимся т.к. слияние будет проихсодить с ней. 

При слиянии веток может возникать конфликт, если информация в одной и той же строке написана по разному. В данном случае мы можем выбрать:
 
 1)Заменить данные на изначальные

 2)Заменить на новые

 3)Сохранить оба

 4)сравнить версии

* 4)Работа с Git Hub

1. Создать аккаунт на GitHub.com
2. Создать локальный репозиторий
3. Подружить локальный и удаленный репозизиторий. GitHub при создании нового репозитория подскажет как это можно сделать.
4. Отправить (push) ваш локальный репозиторий в удаленный (на GitHub), при этом вам, возможно, нужно будет авторизоваться на удаленном репозитории.
5. Провести изменения с "другого компьютера"
6. Выкачать (Pull) актуальное состояние из удаленного репозитория.

* 5)Изменения в чужом репозитории.

1. Делаем форк(fork) интересуещего нас репозитория
2. Делаем git clone для нашегл репозитория
3. Создаем ветку для изменений
4. В данной ветке производим все изменения
5. Отправляем эти изменения н асвой аккаунт (push)
6. В окне на Git Hub появляется возможность отправки pull request
