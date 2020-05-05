﻿### Meta Bit Library (mbl)
Библиотека предназначена для написания кросплатформенных программ под микроконтроллеры (МК). 
mbl предоставляет класс обертку для регистров МК и набор функций для работы с его разрядами. Разработка с применением объектов класса обертки позволяет абстрагироваться от конкретной аппаратной платформы МК. Перенесение кода праграммы сводится к конфигурированию используемых в программе объектов.


###### Содержание библиотеки:
1. [Класс RegisterSet]
    1. [Функция инициализации разрядов BitInit]
2. [Библиотека функций для работы с разрядами BitLib]
3. [Кортэж типов Tuple]
4. [Библиотека для поддержки работы с типами данных Type_Traits]
    1. [Удалиние cv-квалификаторов]
5. [Класс обертка Reference_Wrapper]
6. [Заголовочеый файл с импользуемыми типами данных]
7. [nullptr]
8. [Препроцессорный псевдо "цикл"]
9. [Заголовочные файлы с указателями на регистры МК AVR]
10. [Примеры применения библиотеки]

![Using class RegisterSet]
![Not using class RegisterSet]

[Класс RegisterSet]:https://github.com/Reifat/MetaBit_Lib_in_style_Cpp98/tree/master/doc/metabit/register_set
[Функция инициализации разрядов BitInit]:https://github.com/Reifat/MetaBit_Lib_in_style_Cpp98/tree/master/doc/metabit/register_set
[Библиотека функций для работы с разрядами BitLib]:https://github.com/Reifat/MetaBit_Lib_in_style_Cpp98/tree/master/doc/metabit/bitlib
[Кортэж типов Tuple]:https://github.com/Reifat/MetaBit_Lib_in_style_Cpp98/tree/master/doc/metabit/tuple
[Библиотека для поддержки работы с типами данных Type_Traits]:https://github.com/Reifat/MetaBit_Lib_in_style_Cpp98/tree/master/doc/metabit/type_traits
[Удалиние cv-квалификаторов]:https://github.com/Reifat/MetaBit_Lib_in_style_Cpp98/tree/master/doc/metabit/type_traits
[Класс обертка Reference_Wrapper]:https://github.com/Reifat/MetaBit_Lib_in_style_Cpp98/tree/master/doc/metabit/utility
[Заголовочеый файл с импользуемыми типами данных]:https://github.com/Reifat/MetaBit_Lib_in_style_Cpp98/tree/master/doc/metabit/definitions_type
[nullptr]:https://github.com/Reifat/MetaBit_Lib_in_style_Cpp98/tree/master/doc/metabit/nullptr
[Препроцессорный псевдо "цикл"]:https://github.com/Reifat/MetaBit_Lib_in_style_Cpp98/tree/master/doc/metabit/preprocessor
[Заголовочные файлы с указателями на регистры МК AVR]:https://github.com/Reifat/MetaBit_Lib_in_style_Cpp98/tree/master/doc/avrdef_ptr
[Примеры применения библиотеки]:https://github.com/Reifat/MetaBit_Lib_in_style_Cpp98/tree/master/example

[Using class RegisterSet]:https://github.com/Reifat/MetaBit_Lib_in_style_Cpp98/blob/master/doc/pictures/1.PNG
[Not using class RegisterSet]:https://github.com/Reifat/MetaBit_Lib_in_style_Cpp98/blob/master/doc/pictures/2.PNG










