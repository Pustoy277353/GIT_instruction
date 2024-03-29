# Создание нового репозитория в Git

Создание нового Git-репозитория - это первый шаг к управлению версиями вашего проекта. В этой инструкции мы рассмотрим, как создать новый репозиторий с нуля.

## Шаг 1: Создание папки проекта

1. Создайте новую папку на вашем компьютере, которая будет содержать файлы вашего проекта.

2. Перейдите в эту папку в командной строке (терминале) с помощью команды `cd`, например:

   ```shell
   cd путь/к/вашей/папке
## Шаг 2: Инициализация Git-репозитория
В командной строке выполните следующую команду для инициализации Git-репозитория:

   ```shell
   git init
   ```
Эта команда создаст пустой Git-репозиторий в текущей папке проекта.

## Шаг 3: Добавление файлов
Добавьте файлы вашего проекта в рабочую директорию репозитория.

Например, чтобы добавить все файлы из текущей папки, используйте команду:

   ```shell
   git add .
   ```
Выполните команду `git status`, чтобы убедиться, что файлы были успешно добавлены для отслеживания.

## Шаг 4: Создание первого коммита
Выполните команду `git commit` с комментарием, описывающим ваш первый коммит:

   ```shell
   git commit -m "Первый коммит: начальная версия проекта"
   ```

Это создаст ваш первый коммит в Git-репозитории.

Теперь у вас есть новый Git-репозиторий, и ваш проект начал отслеживаться Git. Вы можете продолжить работу над проектом, создавая новые коммиты при необходимости.

[5. Основы коммитов](commit.md)

[Вернусться на главную страницу](../readme.md)