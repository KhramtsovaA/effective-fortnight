## Подсказка по GIT 

# Создание репозитория:
```
git init

```
# Добавить содержимое файла в индекс

```
git add
```
# Записывать изменения в хранилище
```
git commit -m "Massege text"
```
# Показать коммиты
```
git log
```
# Выводит коммиты красивым списком
```
git log --oneline
```
## Переходить по веткам
```
git checkout <branch name>
```
## Разница между изменениями 

```
git diff
```
#  List, create, or delete branches

```
git branch <name branch>   
```
# Отображение всех веток

````
git branch
```
# Создание новой ветки
 ```
git branch <имя>
```
# Удаление ветки 
````
git branch -d <имя_ветки>
```
# Измененные файлы 

git status

# Разница двух состояний 
```
git diff <1> [2]

# Закоммитить все изменения
```
git commit -m "all my changes"