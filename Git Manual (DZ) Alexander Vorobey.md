# Git manual (Alexander Vorobey)

## Базовые команды при работе с GIT 

* **git init** - инициализация локального депозитория
* **git status** - получение информации от git о его текущем состоянии
* **git add** - добавление файла или файлов к следующему коммиту
* **git commit** -m "message" - создание коммита
* **git log** - вывод на экран всей истории коммитов с их хэш-кодами
* **git checkout** - переход от одного коммита к другому
* **git chechout master** - переход к актуальному состоянию и продолжение работы
* **git diff** - просмотр разницы между текущим и закоммиченым файлом

## Базовые фичи при работе с MD
1. Для того, чтобы создать *заголовок*, необходимо перед текстом вставить # и пробел
2. Для того, чтобы создать *подзаголовок*, необходимо перед текстом вставить ## и пробел. Всего есть 6 уровней подзаголовков
3. Для того, чтобы создать *ненумерованный список*, необходимо перед каждым значением в списке ставить * и пробел.

        Пример:
        * element 1
        * element 2
        * element 3

4. Для того, чтобы создать *нумероманный список*, необходимо перед каждым значением в списке ставить **цифру**,**точку** и **пробел**.

        Пример:
        1. element 1
        2. element 2
        3. element 3



5. **Полужирный текст выделяется с двух сторон** **
6. *Курсив выделяется c двух сторон* *

## Базовая инструкция по работе с удаленными депозиториями

* **git remote** - просмотр списка настроенных удаленных депозиториев
* **git clone** - выбора существующего репозитория и создания его клона
* **git push** - позволяет передать изменения из локального репозитория в удаленный.
* **git pull** - извлечение и загрузка содержимого из удаленного репозитория и немедленного обновления локального репозитория этим содержимым
* **git branch** - извлечения и загрузки содержимого из удаленного репозитория и немедленного обновления локального репозитория этим содержимым
* **git fork** - создание ветвления проект