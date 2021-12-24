# Инструкция для работы с Git и удаленными репозиториями

## Что такое Git?

Это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной системой контроля версий в мире.

## Подготовка репозиториев

Для создания репозитория необходимо выполнить команду "git ini" в папке с репозиторием  и у вас создастся репозиторий (появится скрытая папка .git)

## Создание коммитов

### Git add

Для добавления изменений в коммит используется команда *git add*. Чтобы использовать команду *git add* напишите 'git add <имя файла'.

### Просмотр состояния репозитория

Для того, чтобы посмотреть состояние репозитория, используется команда *git status*. Для этого необходимо написать эту команду в папке с репозиторием, и вы увидите были ли изменения в файлах или нет.

### Создание коммитов
Для того, чтобы создать коммит (фиксацию) необходимо выполнить команду *git commit*. Выполняется она так: *git commit -m <сообщение к коммиту>*. Все файлы для коммита должны быть ***ДОБАВЛЕНЫ*** и сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.

## Перемещение между сохранениями

Для того, чтобы перемещаться между коммитами, необходимо использовать команду *git checkout*. Выполняется она так: *git checkout <номер коммита>*. 

## Журнал изменений

Для того, чтобы просмотреть журнал изменений, необходимо использовать команду  *git log* в папке с репозиторием и у вас появится список коммитов. 

## Ветки в Git
### Добавление веток
Для того, чтобы добавить отдельную ветку, необходимо использовать команду *git branch*. Выполяняется она так: *git branch <название новой ветки>*.

### Просмотр всех веток
Для того, чтобы увидеть название всех веток, необходимо использовать команду *git branch* в папке с репозиторием, и у вас появятся названия всех существуующих веток.

## Слияние веток
Выполняется она так: *git merge <название ветки, из которой хотим перенести информацию>*. Для того, чтобы слить ветки (перенести информацию в чистовик), необходимо использовать команду *git merge*. 

## Удаление веток
Чтобы удалить ветку, необходимо использовать команду: *git branch -d <название ветки>*.
