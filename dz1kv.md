# Инструкция по GIT

## В начале работы нужно представиться
```sh
* git config --global(local) user.name "name"
* git config --global(local) user.email "email"
```
## Создаём рипозиторий(папка) для работы
### Открываем созданную папку в VS code 

### С помощью команд проверяем наличие папки в GIT
* dir (Windows)
* ls (Macos, Linux)

### Инструкция по работе с файлами
## 1 шаг
```sh
git init - инициализирвать
```
### 2 шаг
После добавления информации в файл сохраняем его в VS code клавишами
```sh
Ctrl + S
```
## 3 шаг
После чего в GIT проводим последовательные действия
```sh
git status (файл будет красный)
git add "название файла" (добавление файла)
git status (проверка,файл зелёный)
git commit -m "действия с файлом,которые производились"
```

## 4 шаг
Можем проверить журнал изменений с помощю команды
```sh
git lod
git log --oneline (укороченая версия кодов)
```

## 5 шаг 
Внутри шага 4 можем переключаться между версиями файла с помощью команды 
```sh
git checkout (первые 4 символа)
git checkout master (возврат в последнюю версию файла)
```
# Раздел ветки

Команда с помощью которой смотрим сколько и на какой ветке находимся
```sh
git branch
```

Команда для создания ветки
```sh
git branch <namebranch>
```

Команда для удаления ветки
```sh
git branch -d <namebranch>
```

Переключения между ветками
```sh
git checkout <namebranch>
```

Слияние веток между собой.
Примечание: при слияние нужно находится на ветке **master**
```sh
git merge <namebranch> которую добавляем
```

Можем выполнить команду для просмотра веток и комитов
```sh
git log             длинная версия
git log --oneline   короткая версия
git log --oneline --graph  версия подробная
```

Команда для просмотра изменений
```sh
git diff
```

Команда для очистки теримнала
```sh
clear
```

Если во время слияния веток выскачит синий экран с символами,то делаем следующее
```sh
esc потом воодим :wq
```
