# Итоговая контрольная работа

1. создаем общедоступный репозиторий
2. решаем **1 пункт** 
*Используя команду cat в терминале операционной системы Linux, создать два файла Домашние животные (заполнив файл собаками, кошками,хомяками) и Вьючные животными заполнив файл Лошадьми, (верблюдами и ослы), а затем объединить их. Просмотреть содержимое созданного файла. Переименовать файл, дав ему новое имя (Друзья человека).*

* создаю файлы: 

**cat > home_animals**

* втавила список домашних животных

**ctr +d** - сохранила

**cat > pack_animals**

* написала список

**ctr +d - сохранила**

## 3. решаем **пункт 2** 
*Создать директорию, переместить файл туда.*

* Создала папку для файлов: 

**mkdir conrol_work**

* переместила файлы в созданную папку

**mv pack_animals control_work**

**mv home_animals control_work**

* перешла в созданную папку

**cd control_work/**

* проверила все ли на месте

**ls**

user@userVB:~/control_work$ ls

home_animals  pack_animals

* забыла объединить 

**cat home_animals pack_animals > human_friends**

* переименовать 

**mv human_friends humans_friend**

* посмотрела 

**more humans_friend**

## 4. решаем **пункт 3** 
*Подключить дополнительный репозиторий MySQL. Установить любой пакет из этого репозитория*

*скачиваем

**sudo wget https://dev.mysql.com/get/mysql-apt-config_0.8.24-1_all.deb**

* устанавливаю

**sudo dpkg -i mysql-apt-config_0.8.24-1_all.deb**

* обновим

**sudo apt-get update**

* устанвливаем сервер

**sudo apt-get install mysql-server**

## 4. решаем **пункт 4** 

* удаляем пакет

**sudo dpkg -r mysql-apt-config**

## решаем **пункт 5 **

* 5. Выложить историю команд в терминале ubuntu

650  mkdir conrol_work

  651  mv conrol_work control_work 

  652  ls

  653  cd control_work/

  654  cd ../

  655  ls

  656  cat home_animals

  657  cat > home_animals

  658  cat > pack_animals

  659  nano pack_animals

  660  ls

  661  mv pack_animals control_work 

  662  ls

  663  mv home_animals control_work 

  664  ls

  665  cd control_work/

  666  ls

  667  cat home_animals pack_animals > human_friends

  668  ls

  669  more pack_animals

  670  more human_friends

  671  mv human_friends humans_friend

  672  ls

  673  more humans_friend

  674  clear

  675  sudo wget https://dev.mysql.com/get/mysql-apt-config_0.8.24-1_all.deb

  676  ls

  677  sudo dpkg -i mysql-apt-config_0.8.24-1_all.deb

  678  sudo apt-get update

  679  sudo apt-get install mysql-server

  680  sudo dpkg -r mysql-apt-config

  681  history

  ##  решаем **пункт 6** 

 * 6. Нарисовать диаграмму, в которой есть класс родительский класс, домашние животные и вьючные животные, в составы которых в случае домашних
животных войдут классы: собаки, кошки, хомяки, а в класс вьючные животные
войдут: Лошади, верблюды и ослы.

! [схема_животных] (C:\Users\User\Documents\Control work\final\2024-04-07_21-53-26.jpg)









