# Инструкция для работы с Git и удалёнными репозиториями

## Что такое Git?
> Git - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.

## Подготовка репозитория
Для создание репозитория необходимо выполнить команду *git init*  в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка .git)

## Создание коммитов

### Git add
Для добавления измений в коммит используется команда *git add*. Чтобы использовать команду *git add* напишите *git add <имя файла>*

### Просмотр состояния репозитория
Для того, чтобы посмотреть состояние репозитория используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и Вы увидите были ли измения в файлах, или их не было.

### Создание коммитов
Для того, чтобы создать коммит(сохранение) необходимо выполнить команду *git commit*. Выполняется она так: *git commit -m "<сообщение к коммиту>*. Все файлы для коммита должны быть ***ДОБАВЛЕНЫ*** и сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.

### Перемещение между сохранениями
Для того, чтобы перемещаться между коммитами, используется команда *git checkout*. Используется она в папке с пепозиторием следующим образом: *git checkout <номер коммита>*

### Журнал изменений
Для того, чтобы посмтреть все сделанные изменения в репозитории, используется команда *git log*. Для этого достаточно выполнить команду *git log* в папке с репозиторием

## Ветки в Git

### Создание ветки

Для того, чтобы создать ветку, используется команда *git branch*. Делается это следующим образом в папке с репозиторием: *git branch <название новой ветки>*

## Слияние веток

Для того чтобы дабавить ветку в текущую ветку используется команда *git merge <name branch>*

### Удаление веток
Для удаления ветки ввести команду "git branch -d 'name branch'"

---

## Работа с картинками и ссылками

Для того, чтобы добавить картинку, необходимо ввести следующее: ![Кто-то кем-то щас закусит:)](woman-camels-funny-animals-funny-6435837.jpeg)

Для того, чтобы добавить ссылку, необходимо ввести следующее: [Работа с Markdown](https://gist.github.com/Jekins/2bf2d0638163f1294637)


## Работа с цитатами и списками

### Цитаты

Для того, чтобы добавить одиночную цитату, необходимо поставить ">".

> Кто глупее: дурак или тот, кто за ним следует?

Цитаты под цитатами (максимум 15 ">")
> Когда что-то понимаешь, то жить становится легче. А когда что-то почувствуешь — то тяжелее. Но почему-то всегда хочется почувствовать, а не понять!
>> Люди становятся лучше, когда немного поизносятся, вроде как ружья или сёдла.
>>> Если есть Зачем жить, можно вынести почти любое Как.
>>>> А чтобы заметить яму, необходимо прощупать всем телом очертания её дна.

### Списки
#### Списки бывают:

##### Нумерованные
1. Адын
2. Дыва
3. Тры

##### Ненумерованные (с разными знаками перечисления пунктов)

- рыба
+ овощи
* фрукты

##### Ненумерованные (с одинаковыми знаками перечисления пунктов):

* кофе
* чай
* алкоголь

git pull

Эта команда позволяет скачать все из текущего репозитория и автоматически сделать merge с нашей версией

 

git push

При первом её использовании нужна авторизация.

Эта команда позволяет отправить нашу версию репозитория на внешний репозиторий. ТРЕБУЕТ АВТОРИЗАЦИИ на внешнем репозитории.

 

Как настроить совместную работу

 

1. Создать аккаунт на GitHub.com

2. Создать локальный репозиторий

3. “Подружить” ваш локальный и удалённый репозитории.

GitHub при создании нового репозитория подскажет, как это можно сделать

    

4. Отправить (push) ваш локальный репозиторий в удалённый (на GitHub), при этом, возможно, вам нужно будет авторизоваться на удалённом репозитории

5. Провести изменения “с удаленного репозитория”

6. Выкачать (pull) актуальное состояние из удалённого репозитория

 

pull request

 

- команда для предложения изменений 

 

- запрос на вливание изменений в репозиторий

 

В больших компаниях один ответственный за проект создает аккаунт. Другие пользователи дают команду **pull request**. Предлагать изменения на GitHub нужно в отдельной ветке. 

Сначала пользователь копирует репозиторий на свой компьютер, делает fork репозитория, затем клонирует версию на своём ПК, создаёт ветку с предлагаемыми изменениями, отправляет изменения командой push в свой аккаунт на GitHub и даёт команду pull request.