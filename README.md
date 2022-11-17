# Инструкция для работы с Git и удалёнными репозиториями
## Что такое Git?
Git - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.

## Подготовка репозитория
Для создание репозитория необходимо выполнить команду git init в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка .git)

## Создание коммитов
Git add
Для добавления измений в коммит используется команда *git add*. Чтобы использовать команду *git add* напишите *git add <имя файла>*

## Просмотр состояния репозитория
Для того, чтобы посмотреть состояние репозитория используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и Вы увидите были ли измения в файлах, или их не было.

## Создание коммитов
Для того, чтобы создать коммит(сохранение) необходимо выполнить команду git commit. Выполняется она так: *git commit -m "<сообщение к коммиту>*. Все файлы для коммита должны быть ДОБАВЛЕНЫ и сообщение к коммиту писать ОБЯЗАТЕЛЬНО.

## Перемещение между сохранениями
Для того, чтобы перемещаться между коммитами, используется команда *git checkout*. Используется она в папке с пепозиторием следующим образом: *git checkout <номер коммита>*

Также перемещаться можно между ветками, например *git checkout <имя ветки>*

## Журнал изменений
Для того, чтобы посмтреть все сделанные изменения в репозитории, используется команда *git log*. Для этого достаточно выполнить команду *git log* в папке с репозиторием

## Ветки в Git
Создание ветки
Для того, чтобы создать ветку, используется команда *git branch*. Делается это следующим образом в папке с репозиторием: *git branch <название новой ветки>*

## Слияние веток
Для того чтобы дабавить ветку в текущую ветку используется команда *git merge*

## Удаление веток
Для удаления ветки ввести команду "*git branch -d 'name branch'*"

### Цитаты из книги **Pro Git — профессиональный контроль версий**
![Обложка книги](https://images.secondsale.com/images/120x160/e9960772347abd83b4e9b4170ea570b5.jpg "Pro Git — профессиональный контроль версий")
> Git хранит данные не как последовательность изменений или дельт, а как последовательность снимков состояния (snapshot)

> Как только вы отредактируете файлы, Git будет рассматривать их как изменённые, т.к. вы изменили их с момента последнего коммита

> Стандартный рабочий процесс с использованием Git'а выглядит примерно так:
>+ Вы вносите изменения в файлы в своём рабочем каталоге.
>+ Подготавливаете файлы, добавляя их слепки в область подготовленных файлов.
>+ Делаете коммит, который берёт подготовленные файлы из индекса и помещает их в каталог Git'а на постоянное хранение


# Синтаксис языка Markdown

## Справочник по Markdown от Microsoft:

https://learn.microsoft.com/ru-ru/contribute/markdown-reference

## Блоки кода  
В описание можно добавлять блоки с кодом:
```java
    public static void main ()
    {
    integer i;
        for (i=0; i<array.length; i++)
        {
            printf(i);
        }
    }