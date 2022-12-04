# Git Education. First semenar
*Git - система контроля версий*

1. сохранение версий
2. коллективная работа
3. контроль изменений
4. распределенная система
5. инкрементное хранение изменений

## Git commands

git init - создание локального репозитария. В каталоге появляет скрытый подкаталог .git, в нем хранится инфа по репозитарию

git add .\FileName - добавить файл в репозитарий, файл сменит статус с untracked (неотслеживаемого) на tracked

git add * - добавить все файлы

git status - вывод текущего статуса (что ожидает commit)

git log - просмотр лога с выводом version_id

**git checkout version_id** - переход к версии

git checkout master - возврат к актуальной версии

git diff - сравнение текущего сохранения файлов с версией файлов в master

# Second lesson

git branch - просмотр веток

git branch branch_name - создание ветки

git checkout branch_mane - переход в ветку

git add .\FileName - добавить измененный файл в репозитарий

git commit -m "commit name"  - сохранение изменение

.gitignore - специальный файл со список игнорируемых (невключенных в репозитарий файлов) 

git merge branch_name - объединение веток, к текущей присоединяется branch_name

git branch -d branch_name - удаление ветки

git log --graph - показ лога в виде дерева

git config --global user.name "user_name" - задание имени владельца репозитария или ветки

git config --global user.email "user_email" - задание email владельца репозитария или ветки


## язык разметки MarkDown

**Bold

#Header

*Italics

~cross out

