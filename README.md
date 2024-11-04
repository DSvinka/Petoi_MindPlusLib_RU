# Библиотека расширений Petoi Mind+ 
### Инструмент программирования с использованием блоков для роботов Petoi.
<img src="./python/_images/featured.png" width="300">

---------------------------------------------------------

## Содержание
- [Библиотека расширений Petoi Mind+](#библиотека-расширений-petoi-mind)
  - [Содержание](#содержание)
  - [URL](#url)
  - [Краткое описание](#краткое-описание)
  - [Как использовать](#как-использовать)
  - [Примеры](#примеры)
  - [Лицензия](#лицензия)
  - [Поддерживаемые цели](#поддерживаемые-цели)
  - [История версий](#история-версий)

## URL
* URL оригинального проекта: ```https://github.com/PetoiCamp/Petoi_MindPlusLib```
* URL русского проекта: ```https://github.com/DSvinka/Petoi_MindPlusLib_RU```

## Краткое описание
Используйте библиотеку Mind+ версии V1.7.3 и выше для загрузки этого расширения и управления роботом Petoi.
Библиотека позволяет планировать движения, воспроизводить музыку и получать доступ к контактам GPIO.

## Как использовать
Скачайте и установите [Mind+ Desktop app](https://mindplus.dfrobot.com).

Введите URL проекта: **https://github.com/DSvinka/Petoi_MindPlusLib_RU** в интерфейс, чтобы импортировать эту библиотеку, как показано ниже:
<img width="613" alt="image" src="https://user-images.githubusercontent.com/9747608/227246863-bb229849-4470-494a-9e00-f674ce0ffe9a.png">
<img width="613" alt="image" src="https://user-images.githubusercontent.com/9747608/227246912-f83f9640-2bf7-4dc8-8e2d-b329245a40d6.png">
<img width="613" alt="image" src="https://user-images.githubusercontent.com/9747608/227698081-96999540-9196-46da-b4ba-62fbb5087b30.png">

Для macOS, если ваша версия Mind+ <=V1.7.2 RC3.0, сначала скачайте [PetoiRobot.zip](https://github.com/DSvinka/Petoi_MindPlusLib_RU/raw/main/PetoiRobot.zip) и скопируйте извлечённую папку (**PetoiRobot**) в **/Users/{ваше имя пользователя}/Documents/mindplus-py/environment/Python3.6.5-64/lib/python3.6/site-packages/**.

* Перед запуском программы мы рекомендуем [обновить прошивку робота до последней версии](https://bittle.petoi.com/3-NyBoard-Configuration) для лучшей совместимости. Стандартная прошивка поддерживает большинство блоков программирования. Однако для доступа к контактам IO нужно использовать режим **GROVE_SERIAL_PASS_THROUGH**.
 
<img width="613" alt="image" src="https://user-images.githubusercontent.com/9747608/227701778-c60b5e7e-bee9-474c-bc70-ed91c95773f9.png">


<img width="900" alt="image" src="https://user-images.githubusercontent.com/9747608/227698055-bc776753-745f-43d1-b8c8-46347df969e8.png">

## Примеры
Следующие примеры можно найти в папке [examples/](https://github.com/JasonWong08/ext-petoi_robot/tree/main/examples) и открыть напрямую в приложении Mind+.

Воспроизведение мелодии (/examples/PlayMelody.mp)

![PlayMelody](https://user-images.githubusercontent.com/15603750/228172247-f12aafe9-7187-4717-a1be-107a4a56f2c1.png)

Выполнение навыков (/examples/ExecuteSkills.mp)

![ExecuteSkills](https://user-images.githubusercontent.com/15603750/228173463-0b30986d-6a4c-4d8e-be68-4b881dc51953.png)

Поворот (/examples/TurnAround.mp)

![TurnAround](https://user-images.githubusercontent.com/15603750/228174412-81008304-0352-477a-8a03-a43560927139.png)

Запись значения на цифровой пин (/examples/WriteDigital.mp)

![WriteDigital](https://user-images.githubusercontent.com/15603750/228175321-eba6484f-6643-4e22-8c4c-d470e2423217.png)

Запись значения на аналоговый пин (/examples/WriteAnalog.mp)

![WriteAnalog](https://user-images.githubusercontent.com/15603750/228176252-088885a7-6f42-4f61-8d1a-b6697106d945.png)

Чтение случайных значений аналогового пина и их преобразование в музыкальные тоны (/examples/ReadAnalog.mp)

![ReadAnalog](https://user-images.githubusercontent.com/15603750/228176846-758c68ab-11e0-4f6d-944d-543aaf068b53.png)

Управление суставами робота и воспроизведение мелодии (/examples/Robot.mp)

![Robot](https://user-images.githubusercontent.com/15603750/228177210-a76f390d-262b-4bb5-8e22-54e2129ce1a8.png)

## Лицензия
MIT

## Поддерживаемые цели

MCU                | JavaScript    | Arduino   | MicroPython    | Python
---------------- | :------------: | :---------: | :---------------: | ----------
arduino            |                     |                 |                          |       √
esp32               |                     |                 |                          |       √

## История версий
* V0.0.1  Основные функции завершены.

## Ссылка на зарубежный [интернет-магазин](https://www.petoi.com/collections/robots) для покупки аппаратного обеспечения роботов.