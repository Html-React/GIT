# Этот проект использует Git для управления версиями. В этом файле вы найдете базовые команды Git для работы с проектом.



## Установка Git

Если у вас еще нет Git, вы можете установить его с [официального сайта Git](https://git-scm.com/).

## Основные команды Git

### Настройка


```bash
# Настройка имени пользователя
git config --global user.name "Your Name"

# Настройка email
git config --global user.email "your.email@example.com"
```
### Инициализация и клонирование

```bash
# Инициализация нового репозитория
git init

# Клонирование существующего репозитория
git clone https://github.com/username/repository.git
```
### Работа с изменениями

```bash
# Просмотр состояния файлов в рабочей директории
git status

# Добавление изменений в индекс для последующего коммита
git add <file>

# Создание коммита с сообщением
git commit -m "Commit message"
```
### Ветвление и слияние

```bash
# Просмотр списка веток и текущей ветки
git branch
git branch -a

# Создание новой ветки
git branch <branch-name>

# Переключение на другую ветку
git checkout <branch-name>

# Удаление ветки
git branch -d <branch-name>

# Слияние указанной ветки в текущую
git merge <branch-name>
```
### Работа с удаленными репозиториями

```bash
# Добавление удаленного репозитория
git remote add origin https://github.com/username/repository.git

# Просмотр списка удаленных репозиториев
git remote -v

# Отправка изменений в удаленный репозиторий
git push -u origin main

# Получение изменений с удаленного репозитория и слияние их с локальными
git pull origin main
```

## Дополнительные команды

```bash
# Просмотр истории коммитов
git log

# Отмена изменений и возврат к предыдущему состоянию
git reset --hard HEAD

# Временное сохранение изменений, которые еще не готовы для коммита
git stash
git stash pop
```
