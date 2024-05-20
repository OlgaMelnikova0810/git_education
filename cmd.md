# Tips about cmd

Команда смены директории
```sh
cd c:\folder_name
``` 

Команда отображения текущей директории. Для MacOs, Linux.
```sh
pwd
```

Листинг текущей директории для Windows
```sh
dir
```
linux or MacOs
```sh
ls
```
Удаление ненужного файла
```sh
del <filename>
```
в linux or MacOs
```sh
rm <filename>
```
Просмотр имеющихся веток
```sh
git branch
```
Добавление новой ветки
```sh
git branch name_branch
```
Переход к первоначальной ветке
```sh
git checkout master
```
слияние ветки c master
```sh
git merge new_name_branch
```
отображение всех добавленных изменений в файле
```sh
git log
```
Отображение всех добавленных изменений в файл в укороченном виде. А также для просмотра структуры с ветками
```sh
git log --graph
```
```sh
git log --oneline
```
Просмотр изменений, удаленное красным, новое зеленым
```sh
git diff
```
команда для удаления ненужной ветки
```sh
git branch -d branch_name
```