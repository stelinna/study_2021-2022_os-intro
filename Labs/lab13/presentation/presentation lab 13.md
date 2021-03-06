### **Презентация лабораторной работы 13**  



 

**ТЕМА** «Средства, применяемые при разработке программного обеспечения в ОС типа

UNIX/Linux» 



## Выполнил/лa:

**Студент/ка** **группы** НПИбд-02-21

**Студенческий билет No** 1032205421

**Студент/кa:** Стелина Петрити







### **Цель работы**

Приобрести простейшие навыки разработки, анализа, тестирования и отладки приложений в ОС типа UNIX/Linux на примере создания на языке программирования С калькулятора с простейшими функциями.



### **Последовательность выполнения работы**

***1.**В домашнем каталоге создайте подкаталог ~/work/os/lab_prog*

![1](C:\Users\Admin\OneDrive\Desktop\lab13\1.png)

​							*1.1.подкаталог ~/work/os/lab_prog*





***2.**Создайте в нём файлы: calculate.h, calculate.c, main.c. Это будет примитивнейший калькулятор, способный складывать, вычитать, умножать и делить, возводить число в степень, брать квадратный корень, вычислять sin, cos, tan. При запуске он будет запрашивать первое число, операцию, второе число. После этого программа выведет результат и остановится.*

![image-20220604170638673](C:\Users\Admin\AppData\Roaming\Typora\typora-user-images\image-20220604170638673.png)

​											*2.1.Создание файлы- calculate.h, calculate.c, main.c.*

![2.4](C:\Users\Admin\OneDrive\Desktop\lab13\2.4.png)

​															*2.2.emacs: calculate.h, calculate.c, main.c.*

![2.1](C:\Users\Admin\OneDrive\Desktop\lab13\2.1.png)

​										*2.3.функция калькулятора calculate.h*

![2.2](C:\Users\Admin\OneDrive\Desktop\lab13\2.2.png)

​											*2.4. Интерфейсный файл calculate.h*

![2.3](C:\Users\Admin\OneDrive\Desktop\lab13\2.3.png)

​														*2.5.файл main*





***3.**Выполните компиляцию программы посредством gcc:*

![3.1 (2)](C:\Users\Admin\OneDrive\Desktop\lab13\3.1 (2).png)

​											*3.1.Выполнение компиляцию программы*											





***4.**Создайте Makefile со следующим содержанием: В этом файле мы создаем переменные CC, CFLAGS, LIBS. Инициализируем и создаем блоки.*

![4 (1)](C:\Users\Admin\OneDrive\Desktop\lab13\4 (1).png)

​																	*4.1.Makefile*





**6.** *С помощью gdb выполните отладку программы calcul (перед использованием gdb исправьте Makefile):*

![6](C:\Users\Admin\OneDrive\Desktop\lab13\6.png)

​		

​																*6.1.отладка программы calcul*

- *Запустим отладчик GDB, загрузив в него программу для отладки (рис. [-@fig:008]).*

![](C:\Users\Admin\OneDrive\Desktop\lab13\..png)

​									*6.2.Запустим отладчик GDB*

- *Для просмотра строк с 12 по 15 основного файла используйте list с параметрами*

![6.2](C:\Users\Admin\OneDrive\Desktop\lab13\6.2.png)

​							*6.3.строк с 12 по 15* 

- Установите точку останова в файле calculate.c на строке номер 21

  ![6.3](C:\Users\Admin\OneDrive\Desktop\lab13\6.3.png)

​										*6.4.просмотра строк номер 21*





**7.** *С помощью утилиты splint попробуйте проанализировать коды файлов calculate.c*

*и main.c : splint calculate.c*

![7](C:\Users\Admin\OneDrive\Desktop\lab13\7.png)

​								*7.1. splint calculate.c*					

![7.1](C:\Users\Admin\OneDrive\Desktop\lab13\7.1.png)

​								*7.2.splint main.c*





### **Выводы**

Во время этой лабораторной работы я работала с самыми простыми навыками. Эти простейшие навыки включают в себя навыки разработки, анализа, тестирования и отладки приложений. Я использовала в качестве примера создание калькулятора с простейшими функциями.





