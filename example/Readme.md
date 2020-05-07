### Пример программы с использованием RegisterSet

В примере показано, как с помощью класса обертки RegisterSet реализовать одну обобщенную программу, которая решает одну и туже задачу на под разную аппаратную платформу. При переносе кода, требуется только изменить конфигурацию для используемых объектов под требуемый МК.

В качестве простого примера реализована следующая программа бегущих огней.\
На 8 разрядный порт ввода/вывода подключены 8 LED диодов\
Скорость переключения LED диодов реализована аппаратным таймером\
Для изменения скорости переключения к порту ввода/вывода подключены 8 кнопок

#### ATmega16
![mega16]
#### ATtiny2313
![tiny2313]


[mega16]:https://github.com/Reifat/MetaBitLibrary/blob/master/example/pictures/Atmega16.png
[tiny2313]:https://github.com/Reifat/MetaBitLibrary/blob/master/example/pictures/ATtiny2313.png