### **Презентация лабораторной работы 1**



​																			



**ТЕМА** «Установка и конфигурация операционной системы на виртуальной машину.»





**Выполнил/ла:**
**Студент/ка группы:** НПИбд-02-20	

**Студенческий билет No**:1032205421

**Студент/ка:**     Стелина Петрити	













### **Цель работы:**

Эта работа заключается в приобретении практических навыков установки операционной системы на виртуальную машину и настройке минимальных сервисов.



### **Последовательность выполнения работы**

Дождитесь загрузки графического окружения и откройте терминал. В окне терминала проанализируйте последовательность загрузки системы, выполнив команду dmesg.
Можно просто просмотреть вывод этой команды:  *dmesg | less*  

* Можно использовать поиск с помощью grep:
  *dmesg | grep -i "то, что ищем"*  

  *Получите следующую информацию.*

  1. *Версия ядра Linux (Linux version).*

  2. *Частота процессора (Detected Mhz processor).*

  3. *Модель процессора (CPU0).*

  4. *Объем доступной оперативной памяти (Memory available).*

  5. *Тип обнаруженного гипервизора (Hypervisor detected).*

  6. *Тип файловой системы корневого раздела.*

  7. *Последовательность монтирования файловых систем.*  

     *1.dmesg | less*

  ![img](https://lh3.googleusercontent.com/zkd_OjwgciQQEJ7yKnfyili6dpOUkLCn_ruxprWXKRIUU59hzmQd95ZQX6Y9o4EsE79bG8b8EPzIvHOWJUujNtfu2ONucjkw2omyvuncuTMXdqku9OdVBpXzvjdMVYRhDNCaLlVCoGzJZw3H8A)

​	  	

*1.Версия ядра Linux, dmesg | Linux*

![img](https://lh4.googleusercontent.com/3KdORuPoCXTv6IwlHxmmXok9jy1faeUmU1JGjU7WJhPNFt4B8PDnG4XI13SS13huDaFwGQbVNRNGmz962kcguLyg-I413KJF91S0oAFiuiTgiSfflGmN-fiY5PaPwQ7hL8UVe0HC2IA8nCEreQ)



​          *2.Частота процессора, dmesg | grep Mhz*

![img](https://lh3.googleusercontent.com/LfZSnD6gzmWa9rNSUCZdPmWAIFyUxkgEsfXIBOaR3KEstPxfosq3YjqoIarwYhqanE4j718v7v2n0KGB_ecEtoU8Cc3Cg_vkCvIdpg0msLT80UQD-9RhsXtGrIK8uAo2RpqUK_AuIL6wzeLBWA)



​		 *3. Модель процессора, dmesg | grep cpu*

![img](https://lh4.googleusercontent.com/Zjy0pSHtjKZmFYwQStlcJxm6_yNNB9DaU_AJTUwNRo92tA1Cni403vElfb7SnnEjqyvX9F0wG4Vgjp9SkAHpn9o_LMsLxsHsflIfX2t-ae9BQcpU4C4k30bOj5cv2Q4VHLj2RW19caIiC25zNA)



​							*4.Объем доступной оперативной памяти, dmesg | grep MemTotal /proc/meminfo*

![img](https://lh6.googleusercontent.com/qZ1fhPF_9YyV5mEX0QspnTqiEHDbjqXJkPx7IaVerw4MKORPQ3itJC_8dvkf_-oLqjL6y1J-LJgkuMF3ozzmJChtLKEJblghul8cCe0-yFpmXkRsE6d9Sqyx6OuSMmzjFOezyYOTMjWdZOAe1Q)



​						*5.Тип обнаруженного гипервизора, dmesg | grep virtual*

![img](https://lh4.googleusercontent.com/NJuj8CZWlBLrz9OoqQawylIgleystnrk4hszMhSaao3Ex05aBWe2KoXzN939dUi7zeW49E-MXPfg55UnepY9gy-eB47JUaPqWiQgffvfY_hlImbKM0dN6xRbNPAyCDdlQOtsmcd4Qj3O5kuZOA)



​								*6.Тип файловой системы корневого раздела, df -hT*

![img](https://lh5.googleusercontent.com/f9Xl3sSWarOaJ3CRi86W_2U9lqhQ83rAJUnmipTxjMFoQuRpsBCkZ4U4QAhGp94b9u_VtrbqPlFo7RRrmIx6XjxZCCfgR-4_rYAQeIqs2BE3VgnqZ9GU4oiIQYvXIxHHk6bOW239e-UbAvFrKw)



​							*7.Последовательность монтирования файловых систем, findmnt*

![img](https://lh6.googleusercontent.com/B3VuuYqNCr8JOnG4cZ_u4zBm9bArJeEcx94dz--u46BCDlBImAFZJdT5Us2isdcMzzRqjz6BaxoX1cLZNpI7ynhe7g3nJbRmKtPao8MKP9xa1cJB3WFoEH0TR0OBTBiFQxR36ZlLUxBEfY4M1g)





### **Выводы**

В этой лаборатории мы узнали, как установить fedora linux, как использовать команду и другие команды, необходимые для завершения работы.

