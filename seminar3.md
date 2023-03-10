# Зачем нужны ветви. Начало работы. Повторение пройденных команд

**Ветки позволяют легко управлять черновиками и чистовиками в *Git*.**

Например, преподаватель создает для второй лекции рабочую папку с названием lesson 2. Во время лекции он пишет инструкцию для Markdown, а затем вызывает команды git init, git stasus, git add, git commit.

Работу с ветками начинаем с запуска Git в репозитории. 

* Вводим *git init* и *git status*, чтобы убедиться, что репозиторий создан.
* Повторяем команды *git add, git log, git status*.

Затем преподаватель вносит изменения в редактируемый файл и дает команду *git commit*.

# Работа с черновиками

* **git branch**

Если у нас несколько версий черновика, мы можем вывести на экран ветку, где находимся, командой *git branch*.

Создать ветку можно командой *git branch*.
Делать это надо в папке с репозиторием: 

* *git branch <название новой ветки>*

# Совмещение двух вариантов текста

* **git merge**

Чтобы слить любую ветку с текущей, вызываем *git merge <имя ветки для слияния с текущей>*

# Удаление веток

* **git branch -d branch_to_delete**

сли ветка больше не нужна, ее можно удалить

# Добавление изображения

В Git не принято добавлять файлы изображений, их хранят на сторонних носителях. Чтобы исключить ненужные файлы из загрузки, есть команда *git ignore*.

# Конфликт изменений

При работе в двух ветках одновременно может возникнуть ситуация, когда в одной и другой ветке мы по-разному изменили блок текста. Если затем мы попробуем слить эти ветки, *Git* сообщит о конфликте и предложит выбрать, какие же изменения записать. 

# Визуализация всех веток

* **git log --graph**

Ключ *-graf* в связке с командой *log* позволяет отобразить коммиты в виде дерева.

Параметр, который позволяет видеть историю в виде графа/дерева

# Third seminar, remote repository

Эта строка добавлена из удаленного репозитория
