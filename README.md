# StartToAndroidStudio
Начало работы с AndroidStudio, здесь будет описание лабораторных работ 1-4, цель которых ознакомится с интерфейсом IDE и создания простейших мобильных приложений. Дальнейшее описание будет в папках проектов. 
## Лабораторная работа 1-2
1.	Скачиваю IDE Android Studio с официального сайта:
![](https://github.com/GTkatya/StartToAndroidStudio/blob/main/pic/1.png)
2.	Установить IDE Android Studio:
![](https://github.com/GTkatya/StartToAndroidStudio/blob/main/pic/2.png)
3.	Ознакомление с интерфейсом и настройка IDE Android Studio:
Интерфейс главного приложения
![](https://github.com/GTkatya/StartToAndroidStudio/blob/main/pic/3.png)
Редактор макетов: 
![](https://github.com/GTkatya/StartToAndroidStudio/blob/main/pic/4.png)
*Xml файл схож с html файлом, а также в нем пишется визуальная часть приложения*
***
Добавлю SDK  файл, чтобы скомпилировать и запустить код на мобильном телефоне или на эмуляторе андроид.
![](https://github.com/GTkatya/StartToAndroidStudio/blob/main/pic/5.png)
***
Выбираем нужный компонент

![](https://github.com/GTkatya/StartToAndroidStudio/blob/main/pic/6.png)
***
Ждем пока установится до конца:

![](https://github.com/GTkatya/StartToAndroidStudio/blob/main/pic/7.png)

4. Создаем первое мобильное приложение
 ---
Мы вызываем setContentView в onCreate с желаемым дизайном в качестве аргумента.
Создаем кнопку Button и событие onClick
событие onClick мы добавляем метод Toast, который выводит текст. При нажатии на кнопку мы увидим сообщение «я сосиска!»

![](https://github.com/GTkatya/StartToAndroidStudio/blob/main/pic/8.png)
***
Дизайн кнопки:
![](https://github.com/GTkatya/StartToAndroidStudio/blob/main/pic/9.png)
***
На макете окон мы добавляем constrain для кнопки, чтобы зафиксировать ее в одном положении:

![](https://github.com/GTkatya/StartToAndroidStudio/blob/main/pic/10.png)
***
Теперь проверим для альбомной ориентации, для этого посмотрим как это будет на устройстве заранее в редакторе:

![](https://github.com/GTkatya/StartToAndroidStudio/blob/main/pic/11.png)

***
Поправила положение для кнопки, теперь она тоже будет посередине
![](https://github.com/GTkatya/StartToAndroidStudio/blob/main/pic/12.png)
***
5.	Запуск и отладка на телефоне и эмуляторе:
---
Добавляю эмулятор Андроида
![](https://github.com/GTkatya/StartToAndroidStudio/blob/main/pic/13.png)
***
Теперь выбираю версию Андроида(я поставила последнюю версию)
![](https://github.com/GTkatya/StartToAndroidStudio/blob/main/pic/14.png)
