# Отслеживание изменений в Git

Отслеживание изменений в Git позволяет вам контролировать, что происходит в вашем проекте, включая добавление, изменение и удаление файлов. В этой инструкции мы рассмотрим основные команды и концепции, связанные с отслеживанием изменений в Git.

## git status

Команда `git status` используется для проверки текущего состояния вашего репозитория. Она показывает, какие файлы были изменены и находятся в стейдже (подготовлены к коммиту) и какие файлы не отслеживаются Git.

  ```shell
  it status
  ```

## git diff

Команда git diff позволяет сравнить изменения между рабочей директорией и стейджем (индексом) или между стейджем и последним коммитом. Это полезно, чтобы понять, какие изменения будут включены в следующий коммит.

Для сравнения изменений между рабочей директорией и стейджем:

  ```shell
  git diff
  ```

Для сравнения изменений между стейджем и последним коммитом:

  ```shell
  git diff --staged
  ```

Теперь вы знаете основные команды для отслеживания изменений в Git. Постоянное использование этих команд поможет вам эффективно управлять вашими проектами и следить за изменениями в коде.

[7. Работа с ветками](branch.md)

[Вернусться на главную страницу](../readme.md)