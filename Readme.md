# Инструкция по работе с Git

## Что такое Git?
Git - это наиболее популярная реализация распределённой системы контроля версий. Наиболее популярной реализацией

## Подготовка репозитория
Для создания репозитория в папке предполагаемого репозитория необходимо написать команду *git init*. Для этого в терминале с открытой папкой-репозиторием пишем *git init*.

## Создание коммитов

### Добавление файлов к коммиту
Для добавления файлов к коммиту используется команда *git add*. Для того, чтобы добавить файлк новому коммиту, необходимо в терминале с открытой папкой-репозиторием написать *git add <имя файла>*.

### Создание коммитов
Для создания комимитов используется команда git commit. Для этого в папке с репозиторием в терминале с папкой-репозиторием необходимо написать команду *git commit -m "<Сообщение к коммиту>"*. Сообщение к коммиту писать ***обязательно***.

## Журнал изменений
Для просмотра истории изменений используется команда *git log*. Для этого в терминале с папкой-репозиторием необходимо набрать *git log*.

## Перемещение между коммитами
Для перемещения между коммитами используется команда *git checkout*. Для этого в терминале с открытой папкой-репозиторием необходимо написать *git checkout <номер коммита>*. Номера коммитов можно посмотреть в истории коммитов, описанной в предыдущем пункте.

## Ветки в Git
Для создания новой ветки используется команда *git branch*. Для этого в терминале с открытой папкой-репозиторием необходимо написать *git branch <название_ветки>*. Для перемещения между ветками используется команда *git checkout*. Для этого в терминале с открытой папкой-репозиторием необходимо написать *git checkout <название_ветки>*.

### Просмотр списка веток
Для просмотра списка веток используется команда *git branch*. Для этого в терминале с открытой папкой-репозиторием необходимо написать команду *git branch*.

### Переход между ветками
ДЛя перехода между веками используется команда *git checkout*. Для этого в терминале с открытой папкой-репозиторием необходимо написать команду *git checkout <название_ветки>*.

## Слияние веток 
Для слияния веток используется команда *git merge*. Для этого нужно перейти в ветку, в которую будем добавлять другую ветку и в терминале с открытой папкой-репозиторием необходимо написать *git merge <название_ветки,которую_будем_добавлять_в_основную_ветку>*.

## Разрешение конфликтов
Конфликт при слиянии веток может произойти, если в одной строке написана разная информация в двух ветках, тогда при конфликте можно выбрать одну из четырёх предложенных комманд: accept current change, accept incoming change, accept both changes или compare changes, либо решить конфликт вручную, отредактировав текст с клавиатуры самостоятельно.

## Удаление веток
Для удаления ветки используется команда *git branch -d*. Для этого в терминале с открытой папкой-репозиторием необходимо написать *git branch -d <название_ветки>*.

