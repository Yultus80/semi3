# Инструкция для работы с Git и удалёнными репозиториями

## Что такое Git?
**Git** - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.
## Подготовка репозитория
Для создание репозитория необходимо выполнить команду **git init**  в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка .git)

## Создание коммитов

**Git add**

Для добавления измений в коммит используется команда **git add**. Чтобы использовать команду **git add** напишите **git add <имя файла>**

## Просмотр состояния репозитория
Для того, чтобы посмотреть состояние репозитория используется команда **git status**. Для этого необходимо в папке с репозиторием написать **git status**, и Вы увидите были ли измения в файлах, или их не было.

## Создание коммитов
Для того, чтобы создать коммит(сохранение) необходимо выполнить команду **git commit**. Выполняется она так: **git commit -m "<сообщение к коммиту>**. Все файлы для коммита должны быть ***ДОБАВЛЕНЫ*** и сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.

## Перемещение между сохранениями
Для того, чтобы перемещаться между коммитами, используется команда **git checkout**. Используется она в папке с пепозиторием следующим образом: **git checkout <номер коммита>**

## Журнал изменений
Для того, чтобы посмтреть все сделанные изменения в репозитории, используется команда **git log**. Для этого достаточно выполнить команду **git log** в папке с репозиторием

## Ветки в Git

***Создание ветки***

Для того, чтобы создать ветку, используется команда **git branch**. Делается это следующим образом в папке с репозиторием: **git branch <название новой ветки>**

***Слияние веток***

Для того чтобы дабавить ветку в текущую ветку используется команда **git merge <name branch>**

***Удаление веток***

Для удаления ветки ввести команду **"git branch -d 'name branch'"**

# Язык разметки Markdown
 
## Работа с картинками

 ![картинка](https://www.imgonline.com.ua/examples/bee-on-daisy.jpg)
 ![водопад](https://w-dog.ru/wallpapers/11/3/473550050587055/kamni-mox-cvety-vodopad.jpg)
 Для добавления картинки надо:
 **![название картинки](путь к картинке)**

---

 ## работа с ссылками
 [работа с маркдаун](https://skillbox.ru/media/code/yazyk-razmetki-markdown-shpargalka-po-sintaksisu-s-primerami/?ysclid)

 [как поймать удачу](https://dzen.ru/a/XURcraxBJACtKHmF)

 Чтобы добавить ссылку необходимо сделать следующее:
 **[Название ссылки](Путь к ссылке)**


---

## Работа с цитатами и списками

> что то написали
>> еще пишем
>>> еще пишем

* списки
- списки
+ списки
+ списки

## Выделение текста

1. *Курсив* или _Курсив_
2. **Жирный** или __Жирный__
3. ***Жирный курсив*** или ___Жирный курсив___
4. Вы**делен**ие фрагмента слова или т*а*к
5. ~~Зачеркнутый~~
6. <u>Подчеркнутый
7. 

## git pull
Эта команда позволяет скачать все из текущего репозитория и автоматически сделать merge с нашей версией

## git push
При первом её использовании нужна авторизация.
Эта команда позволяет отправить нашу версию репозитория на внешний репозиторий. **ТРЕБУЕТ АВТОРИЗАЦИИ** на внешнем репозитории.

## Как настроить совместную работу

1. Создать аккаунт на **GitHub.com**
2. Создать локальный репозиторий
3. “Подружить” ваш локальный и удалённый репозитории. 
    
**GitHub** при создании нового репозитория подскажет, как это можно сделать
    
4. Отправить (push) ваш локальный репозиторий в удалённый (на **GitHub**), при этом, возможно, вам нужно будет авторизоваться на удалённом репозитории
5. Провести изменения “с удаленного репозитория”
6. Выкачать **(pull)** актуальное состояние из удалённого репозитория

## pull request

- команда для предложения изменений 

- запрос на вливание изменений в репозиторий

В больших компаниях один ответственный за проект создает аккаунт. Другие пользователи дают команду **pull request**. Предлагать изменения на GitHub нужно в отдельной ветке. 
Сначала пользователь копирует репозиторий на свой компьютер, делает **fork** репозитория, затем клонирует версию на своём ПК, создаёт ветку с предлагаемыми изменениями, отправляет изменения командой push в свой аккаунт на GitHub и даёт команду **pull request**.
 
 Как сделать pull request (по шагам):

- Делаем fork (ответвление) репозитория
- Делаем git clone СВОЕЙ версии репозитория
- Создаем новую ветку и в НЕЕ вносим свои изменения
- Фиксируем изменения (делаем коммиты)
- Отправляем свою версию в свой GitHub
- На сайте GitHub нажимаем кнопку pull request
 
 hhhh
конец
