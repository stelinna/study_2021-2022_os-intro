### **Презентация лабораторной работы 11**  





**ТЕМА «**Программирование в командном процессоре ОС UNIX. Ветвления и циклы**»**





## Выполнил/лa:

**Студент/ка** **группы** НПИбд-02-21

**Студенческий билет No** 1032205421

**Студент/кa:** Стелина Петрити







# Цель работы                                     

Изучить основы программирования в оболочке ОС UNIX. Научится писать более сложные командные файлы с использованием логических управляющих конструкций и циклов.





### **Последовательность выполнения работы**



**1.** **Используя команды getopts grep, написать командный файл, который анализирует командную строку с ключами:**

*– -iinputfile — прочитать данные из указанного файла;*

*– -ooutputfile — вывести данные в указанный файл;*

*– -pшаблон — указать шаблон для поиска;*

*– -C — различать большие и малые буквы;*

*– -n — выдавать номера строк.*

*а затем ищет в указанном файле нужные строки, определяемые ключом -p*

![1.1](C:\Users\Admin\OneDrive\Desktop\lab11\1.1.png)



​									***1.1. данные exp1.txt***



![1.4](C:\Users\Admin\OneDrive\Desktop\lab11\1.4.png)

​							***1.2. анализирует командную строку с ключами***

![1.5](C:\Users\Admin\OneDrive\Desktop\lab11\1.5.png)

​								***1.3.проверка***





**2.** **Написать на языке Си программу, которая вводит число и определяет, является ли оно больше нуля, меньше нуля или равно нулю. Затем программа завершается с помощью функции exit(n), передавая информацию в о коде завершения в оболочку. Командный файл должен вызывать эту программу и, проанализировав с помощью команды $?, выдать сообщение о том, какое число было введено.**

![2](C:\Users\Admin\OneDrive\Desktop\lab11\2.png)

​									***2.1.code exp4.c*** 

![2.1](C:\Users\Admin\OneDrive\Desktop\lab11\2.1.png)

​																	***2.2.code exp5.sh***

![2..3](C:\Users\Admin\OneDrive\Desktop\lab11\2..3.png)

​														***2.3. проверка***

![2.4](C:\Users\Admin\OneDrive\Desktop\lab11\2.4.png)

​															***2.4. проверка***





***3.Написать командный файл, создающий указанное число файлов, пронумерованных***

**последовательно от 1 до 𝑁 (например 1.tmp, 2.tmp, 3.tmp,4.tmp и т.д.). **

**Число файлов,которые необходимо создать, передаётся в аргументы командной строки. Этот же командный файл должен уметь удалять все созданные им файлы (если они существуют).**

![3](C:\Users\Admin\OneDrive\Desktop\lab11\3.png)

​																***3.1.code exc3.sh***

![3.2](C:\Users\Admin\OneDrive\Desktop\lab11\3.2.png)

***3.2. проверка***



**4. Написать командный файл, который с помощью команды tar запаковывает в архив все файлы в указанной директории. Модифицировать его так, чтобы запаковывались только те файлы, которые были изменены менее недели тому назад (использовать команду find).**



![kodi 4](C:\Users\Admin\OneDrive\Desktop\lab11\kodi 4.png)

​										***4.1.code exc4.sh***

![4](C:\Users\Admin\OneDrive\Desktop\lab11\4.png)

​								***4.2.проверка***





# Выводы

В этой лаборатории я научилась писать сложные командные файлы, используя логические управляющие конструкции и циклы. Я изучилa основы программирования в оболочке.



