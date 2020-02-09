# Reydan46 Admin Extension

Дополнение предложено пользователем Reydan46 для добавления некоторых функций на сайт для упрощения администрирования.

## Установка

Расширение не является самостоятельным и требует установки в браузер дополнительных расширений:

* Tampermonkey - для запуска пользовательских скриптов
* Slylish - для применения пользовательских стилей

### Slylish

После установки, нажимаем на `Slylish` – Троеточие – «Создать стиль»:

![alt text](https://raw.githubusercontent.com/freedomsex/Reydan46AdminExtension/master/images/1.png)

В открытое окно вставляем содержимое файла `css.txt`. В название пишем к примеру «Freedomsex». В нижней части окна «Применить к:» нажимаем «Указать» - «URLв домене» и вписываем в строку (без кавычек) «freedomsex.me». Должно получиться следующее:

![alt text](https://raw.githubusercontent.com/freedomsex/Reydan46AdminExtension/master/images/2.png)

### Tampermonkey

(На ошибки не обращаем внимания – всё будет работать) Далее, нажимаем на `Tampermonkey` – «Добавить новый скрипт»:

![alt text](https://raw.githubusercontent.com/freedomsex/Reydan46AdminExtension/master/images/3.png)

В появившемся окне выделяем все и заменяем содержимым файла `java-script.txt`. Нажимаем «Сохранить» (либоCtrl+S). В списке открываем наш созданный скрипт «Freedomsex». Переходим в появившеюся вкладку «Настройки» и в поле «Запускать при:» выбираем «document-start». Ещё раз сохраняем (на вкладке редактора, либоCtrl+S). Готово, пробуйте.
