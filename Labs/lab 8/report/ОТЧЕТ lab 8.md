### **МИНИСТЕРСТВО ОБРАЗОВАНИЯ И НАУКИ РОССИЙСКОЙ ФЕДЕРАЦИИ ФЕДЕРАЛЬНОЕГОСУДАРСТВЕННОЕ АВТОНОМНОЕ ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГООБРАЗОВАНИЯ**

### **«РОССИЙСКИЙ УНИВЕРСИТЕТ ДРУЖБЫ НАРОДОВ»**

Факультет физико-математических и естественных наук 

Кафедра информационных технологий

**ОТЧЕТ**

по лабораторной работе 8
**ТЕМА** **«**Текстовой редактор vi**»**по дисциплине **«**Операционные системы**»**



**Выполнил/лa:**

**Студент/ка группы** НПИбд-02-21

**Студенческий билет No** 1032205421

**Студент/кa:** Стелина Петрити







### **Цель работы**

Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором vi, установленным по умолчанию практически во всех дистрибутивах.



### **Последовательность выполнения работы**

1. Ознакомиться с теоретическим материалом.
2. Ознакомиться с редактором vi.
3. Выполнить упражнения, используя команды vi.

**Задание 1. Создание нового файла с использованием vi**

1. Создайте каталог с именем ~/work/os/lab06. 

2. Перейдите во вновь созданный каталог.

3. Вызовите vi и создайте файл hello.sh

   

![img](https://lh6.googleusercontent.com/HM032hvwbKGCyRlK2LdmsAUHHm4aAlwP11FHPvM0vX4Vuf6r1g29vlCkTcpoqo85BmTeQqfJVeiFczbnkb6v9RMO9RAOCzeVEkliUMkFf95dmK6ukc8mwpkRKpjur3ASRp4OL4I7bizbJDE8EQ)



4. Нажмите клавишу i и вводите следующий текст.

   ![img](https://lh5.googleusercontent.com/wU6FVRd6EmbzktyvnBzfOiyV8iJlpDQsL7eR_orZmn7XwmmnngVol2ho6pcnCFcZN4M11me36WzRhPXnWjVgSMFCkvud-kZqdxtHus4-MDcJ8vp2wlvEIfAkhEPhCgB5pUHk6nYSpmnl7AJr0Q)





5. Нажмите клавишу Esc для перехода в командный режим после завершения ввода текста.
6. Нажмите : для перехода в режим последней строки и внизу вашего экрана появится приглашение в виде двоеточия.
7. Нажмите w (записать) и q (выйти), а затем нажмите клавишу Enter для сохранения вашего текста и завершения работы.

![img](https://lh3.googleusercontent.com/vu5hGdoOa6WUC8yKmN4Uo6HeRZo43-kyzGwdhYHGJTHL8g6nfnX1hKzcqxlrafg8jZjbMg584Sqd6FOH4iPX2vKaZOI4MltIUR1Q2JYaUSt7f6eNMVlDlfkCla-Wja97tOsxG9HHVhqXMi5h5w)



8. Сделайте файл исполняемым

![img](https://lh5.googleusercontent.com/fv_pBkX_Hz34Os4_ehlMxW60XhBVAw4RM7mNFNLG7LApGxy-bwbvvZNEdq8LaxwA3EC9Hu-pwC10gVzKRX2okXhZ66xQXckQJAZxP_HxSaF4b5AuQTBc9YREhfSKZXuXwU0GVHQtJHZ6CEzYPA)





**Задание 2. Редактирование существующего файла**

1. Вызовите vi на редактирование файла

![img](https://lh5.googleusercontent.com/tNIQtK1ydeBWFkwV8r7lIfACeyhhaT8XVx3OCjq_Fo9wIhTAqPMWSzF9wvSwA5DP2pltvlFxKGo7l4i3HCM4UPcr5NyFlBo3vH6kNw6TQZlZb1UIyHIVAGrhnLKaeR9Y_lLueLoll8ARwbCrTA)



2. Установите курсор в конец слова HELL второй строки.
3. Перейдите в режим вставки и замените на HELLO. Нажмите Esc для возврата в командный режим.
4. Установите курсор на четвертую строку и сотрите слово LOCAL.
5. Перейдите в режим вставки и наберите следующий текст: local, нажмите Esc для возврата в командный режим.
6. Установите курсор на последней строке файла. Вставьте после неё строку, содержащую следующий текст: echo $HELLO.
7. Нажмите Esc для перехода в командный режим.

![img](https://lh5.googleusercontent.com/22hlkAM6JYbIBq_b05r855o2iiknjSkXqF9qKOf7zFoaeQEOjr4cRuKbCtmjvzNXtLNAvMXDSymr8EgGdx8ZEN8wP5_5mha0gr5Wi0JIiP6AjB9aMjGbj1pT8ySGCaAvI0-QFqnwQSG3SJHj7w)



8. Удалите последнюю строку. d+$ 

   

![img](https://lh4.googleusercontent.com/4wAE1fKSVs0oO_BM0GFyVroF302ZMuvOkdTwVfSa7xsBEg24PVtlhEVU8ENPMRPwk1z_U6ITcEDUBOWBLEMiCDf1KX1wsYcrLY1N6tkdQe0-5w-SSaqSwVyCMCkAxyCA4Df_RIXVMvrjzZL36w)



9. Введите команду отмены изменений u для отмены последней команды.u

![img](https://lh6.googleusercontent.com/AgecVB4u6HuwRjTf6WgLEXoqNf0OBc9j1_RKc3-1nTRLbpKkMPVI9Lpe0lYmK0C5cQ6o1qKF4kPpiPhCKF2CCeEcCx3YTYtwRKokEAU3dWHwtbTeRNXjvWROwhUkMv33kYkuM13A3UvgeIgyWA)



10. Введите символ : для перехода в режим последней строки. Запишите произведённые изменения и выйдите из vi.

    ![img](https://lh6.googleusercontent.com/FgjVJ9Zh7nmVsPMiTw0i0MnlIlak-VXd6FPjaN4QSLA7G2zXx59KTuL8v4nwBChAxDlVUT2rerS-jAqtpkyAgDIoJ898kY06ZQVY3H1R1C38Bbuln2NaE0kVf03dkObYBIyz6qCCaAy0AIZM9w)





### **Контрольные вопросы**

**1. Дайте краткую характеристику режимам работы редактора vi.**

Командный режим используется для редактирования команд и навигации по редактируемому файлу. режим вставки − ввод содержимого отредактированного файла. 

режим последней строки − запись изменений в файл и выход из редактора.

**2. Как выйти из редактора, не сохраняя произведённые изменения?** 

  Клавиши (:), (q), (!)

**3.Назовите и дайте краткую характеристику командам позиционирования.**

"0"(ноль) − переходит в начало строки;

"$" − переходит в конец строки;

"G" − переходит в конец файла;

n"G" − переходит к строке с номером n.

**4.Что для редактора vi является словом?**

При использовании букв W и B разделители понимаются как пробел, табуляция и возврат каретки. При использовании l w, b означает знаки препинания.

**5. Каким образом из любого места редактируемого файла перейти в начало (конец)файла?**клавиши (4) (G).
**6.Назовите и дайте краткую характеристику основным группам команд редактирования.**

Вставка строки

«о» − вставить строку под курсором;

(О)− вставить строку над курсором.

Удаление текста(x)− удалить один символ в буфер;

«d» «w» − удалить одно слово в буфер;

«d» «$» − удалить в буфер текст от курсора до конца строки;

«d» «0» − удалить в буфер текст от начала строки до позиции курсора;

«d» «d» − удалить в буфер одну строку;

n «d» «d» − удалить в буфер n строк.

Копирование и перемещение текста

«:» n,m «d» – удалить строки с n по m;

«:» i,j «m» k – переместить строки с i по j, начиная со строки k;

«:» i,j «t» k – копировать строки с i по j в строку k;

«:» i,j «w» имя-файла – записать строки с i по j в файл с именем имя-файла.

Вставка текста

«а» − вставить текст после курсора;

«А» − вставить текст в конец строки;

«i» − вставить текст перед курсором;

«i» − вставить текст n раз;

«I» − вставить текст в начало строки.

Копирование текста в буфер

«Y» − скопировать строку в буфер;

n «Y» − скопировать n строк в буфер;

«y» «w» − скопировать слово в буфер.

Вставка текста из буфера

«p» − вставить текст из буфера после курсора;

«P» − вставить текст из буфера перед курсором.

**7.Необходимо заполнить строку символами $. Каковы ваши действия?**

n(G)+0+c+ $

**8.Как отменить некорректное действие, связанное с процессом редактирования?**

* (u) - одно предыдущее действие последовательно,

* (:) (e") (!) - это отменяет все изменения, которые вам нужно нажат

**9.Назовите и дайте характеристику основным группам команд режима последней строки.**

Запись и выход из редактора в файле
":" "w" − записывает измененный текст в файл, не покидая vi

":" "e" "!" − возврат в командный режим, отменяющий все изменения, внесенные с момента последней записи.

":" "w" "q" − записать изменения в файл и выйти из vi

"s":" "w" filename − записывает измененный текст в новый файл с именем filename

":" "w" "!" filename − записывает измененный текст в файл с именем filename

":" "q" − выход из редактора vi

":" "q" "!" − выходит из редактора без записи

":"n,m "d" − удаляет строки от n до m

":"i,j "m" k − перемещает строки из i в j, начиная со строки k

":"i,j "t" k − копирует строки из i в j в строку k

":"i,j "w" filename − записывает строки от i до j в файл с именем filename.

Копирование и перемещение

":"i,j "t" k − копирует строки из i в j в строку k

":"i,j "m" k − перемещает строки из i в j, начиная со строки k

":"n,m "d" − удаляет строки от n до m

":"i,j "w" filename − записывает строки от i до j в файл с именем filename.

**10.Как определить, не перемещая курсора, позицию, в которой заканчивается строка?"**

$" и число после десятичной точки в правом нижнем углу.

**11. Выполните анализ опций редактора vi (сколько их, как узнать их назначение и т.д.).**

Команда set. Поставьте нет перед именем параметра в команде set, чтобы отказаться от него.
":" - чтобы просмотреть параметры редактора vi, нажмите

**12.Как определить режим работы редактора vi?**

1. Вставки - клавиатура используется для набора текста.
   2. командный режим - Esc или Ctrl + c.- Для выхода в командный режим



### **Выводы**

В этой лабораторной работе мы узнали о редакторе vi, Мы изучили команды редактирования в режиме командной строки, как перемещать курсор с помощьюклавиши, мы научились редактировать файлы, удалять их и выполнять поиск. Подводя итог, мы научились редактировать с помощью vi.