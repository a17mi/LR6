# LR6
Лабораторная работа №6

Создаем копию репозитория в личное хранилище.

![Image alt](https://github.com/a17mi/LR6/raw/reportMichurina/Screenshots/1.jpg)

Настраиваем клиент git, вводим имя пользователя и email, с помощью команд: git config --global user.name <username>; git config --global user.email <email>.

![Image alt](https://github.com/a17mi/LR6/raw/reportMichurina/Screenshots/2.jpg)

Клонируем удалённый репозиторий на компьютер, с помощью команды: git clone <url>.

![Image alt](https://github.com/a17mi/LR6/raw/reportMichurina/Screenshots/3.jpg)

Добавляем файл через интерфейс GitHub, с помощью команды: cd LR6/.

![Image alt](https://github.com/a17mi/LR6/raw/reportMichurina/Screenshots/4.jpg)

Поддтягиваем изменения в локальный репозиторий, с помощью команды: git pull.

![Image alt](https://github.com/a17mi/LR6/raw/reportMichurina/Screenshots/5.jpg)

Просматриваем коммиты ветки master, с помощью команды: git log.

![Image alt](https://github.com/a17mi/LR6/raw/reportMichurina/Screenshots/6.jpg)

Просматриваем существующие ветки в текщем репозитории, с помощью команды: git branch, затем переходим в ветку branch1, с помощью команды: git checkout branch1.

![Image alt](https://github.com/a17mi/LR6/raw/reportMichurina/Screenshots/7.jpg)

Просматриваем коммиты ветки branch1, с помощью команды: git log.

![Image alt](https://github.com/a17mi/LR6/raw/reportMichurina/Screenshots/9.jpg)

Подробно рассматриваем коммиты, с помощью команды: git log -p.

![Image alt](https://github.com/a17mi/LR6/raw/reportMichurina/Screenshots/10.jpg)

Возникает конфликт, проверяем причину коммита, добавляем файл для отслеживания, оставляем коммит, с помощью команд:git status; git add mergefile.txt; git commit -m "Fixed merge". Слияние в ветку master происходит с помощью команды: git merge branch1.

![Image alt](https://github.com/a17mi/LR6/raw/reportMichurina/Screenshots/11.jpg)
![Image alt](https://github.com/a17mi/LR6/raw/reportMichurina/Screenshots/12.jpg)

После успешного слияния удаляем побочную ветку, с помощью команды: git branch -d branch1.

![Image alt](https://github.com/a17mi/LR6/raw/reportMichurina/Screenshots/13.jpg)

Создаем изменения и фиксируем их, с помощью команд: git add и git commit.

![Image alt](https://github.com/a17mi/LR6/raw/reportMichurina/Screenshots/14.jpg)
![Image alt](https://github.com/a17mi/LR6/raw/reportMichurina/Screenshots/15.jpg)

Просматриваем корректное сохранение комментариев, с помощью команды: git log.

![Image alt](https://github.com/a17mi/LR6/raw/reportMichurina/Screenshots/16.jpg)

Делаем "хард" откат коммита, с помощью команды git reset --hard HEAD~1

![Image alt](https://github.com/a17mi/LR6/raw/reportMichurina/Screenshots/17.jpg)

Создаем ветку отчета, с  помощью команды: git branch report и делаем переход к ней с помощью команды: git checkout report.

![Image alt](https://github.com/a17mi/LR6/raw/reportMichurina/Screenshots/18.jpg)

Выводим итоговую историю оперций, с помощью команды: git log.

![Image alt](https://github.com/a17mi/LR6/raw/reportMichurina/Screenshots/19.jpg)


