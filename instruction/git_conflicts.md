# Работа с конфликтами в Git

Конфликты возникают в Git, когда две ветки содержат изменения в одной и той же части файла, и Git не может автоматически определить, какие изменения следует сохранить. В этой инструкции мы рассмотрим, как разрешать конфликты при слиянии веток.

## Шаг 1: Подготовка к слиянию

1. Перейдите на ветку, в которую вы хотите выполнить слияние:

   ```shell
   git checkout целевая_ветка
   ```

2. Выполните команду слияния для включения изменений из другой ветки:

   ```shell
   git merge исходная_ветка
   ```
   Например:

   ```shell
   git merge feature-branch
   ```

Это может вызвать конфликты, если есть изменения в обеих ветках.

## Шаг 2: Разрешение конфликтов

1. Откройте конфликтующий файл в текстовом редакторе. В конфликтующем файле вы увидите маркеры `<<<<<<<`, `=======` и `>>>>>>>`, которые обозначают разные версии изменений.

2. Решите, какие изменения следует сохранить. Пройдитесь по конфликту и выберите, какие изменения должны остаться. Удалите маркеры конфликта.

3. Сохраните файл.

## Шаг 3: Подтверждение разрешения конфликта

1. Добавьте измененный файл в индекс:

   ```shell
   git add конфликтующий_файл
   ```
   
2. Закоммитьте разрешение конфликта:

   ```shell
   git commit -m "Разрешение конфликта"
   ```

## Шаг 4: Завершение слияния
После разрешения конфликтов выполните команду:

   ```shell
   git merge --continue
   ```

Это завершит процесс слияния и создаст новый коммит, объединяя изменения из двух веток.

Теперь вы знаете, как разрешать конфликты при слиянии веток в Git. Работа с конфликтами требует внимания и решительности, но это необходимый этап при совместной разработке проектов с использованием Git.

[11. Дополнительные ресурсы и советы](add.md)

[Вернусться на главную страницу](../readme.md)