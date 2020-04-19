# sum_Guzenko_A_M
Sum of 2 and 4.
Сложение 2 и 4.  
# Task_1
Using the auto-increment addressing method and register R4, add one to cell 1036 with data 45.  
Используя автоинкрементный метод адресации и регистр R4 выполнить прибавление единицы к ячейке 1036 с данными 45.  
# Task_2
Using the Indexing Addressing Method, move the data from cell 1002 - 6677 to cell 1022. Use the registers R0 and R5.  
Используя Индексный метод адресации переместить данные из ячейки 1002 - 6677 в ячейку 1022. Воспользоваться регистрами R0 и R5.  
# Task_3
Using the register and auto-decrement addressing methods, calculate the difference 1010 - 56 and R0 - 40. Write the result in 1010.  
Используя регистровый и автодекрементный методы адресации вычислить разность 1010 - 56 и R0 - 40. Результат записать в 1010.  
# Task_4
Copy an array of machine words from 6 elements from the RAM area 1010-1022 to the area 1050-1062 (using the auto-incrementing addressing method, registers R3, R4, a cycle based on the SOB operation).  
Копирование массива машинных слов из 6 элементов из области ОЗУ 1010-1022 в область 1050-1062 (использование автоинкрементного метода адресации, регистров R3, R4, цикл на основе операции SOB).  
# Task_5
Calculate the size of the array starting at address 1040, the sign of the end of the array is a zero word (Auto-incrementing addressing method using R5, a cycle based on the TST operation and the BNE-BEQ branch command)  
Вычисление размера массива, начинающегося с адреса 1040, признак конца массива – нулевое слово (Автоинкрементный метод адресации с использованием R5, цикл на основе операции TST и команды ветвления BNE - BEQ)  
# Task_6
Calculate the sum of the elements of an array consisting of 5 elements and starting with address 1040 (using the auto-increment addressing method, registers R4 and R5, a cycle based on the SOB operation)  
Вычисление суммы элементов массива состоящего из 5 элементов и начинающегося с адреса 1040 (использование автоинкрементного метода адресации, регистров R4 и R5, цикл на основе операции SOB)  
# Task_7
Counting the number of binary units in a word (using shift operations ASL, ASR and BCC branching - BCS and registers R2 and R3)  
Подсчет числа двоичных единиц в слове (использование операций сдвига ASL, ASR и ветвления BCC – BCS и регистры R2 и R3)  
# Task_8
“Russian peasant” method of integer multiplication (using shift operations ASL, ASR and BCC-BCS branching, use the registers R0 and R1 as multiplied numbers, write the result in R2).  
“Русский крестьянский” метод умножения целых чисел (использование операций сдвига ASL, ASR и ветвления BCC – BCS, в качестве умножаемых чисел использовать регистры R0 и R1, результат записать в R2).  
# Task_9
Multiplication of the elements of the array based on the subroutine “Russian peasant” method (the first array is located at 1034-1044, the second array 1050-1060).  
Перемножение элементов массива на основе подпрограммы “русский крестьянский” метод (первый массив находится по адресу 1034-1044, второй массив 1050-1060).  
# Task_10
Write in R1 - date, R2 - month, R3 - year (by direct addressing method).
Form a cycle (SOB command). Number of passes = R2, and refer to the routine (JSR, RTS) that does the following:
writes to the cell at the address located in R1, the square of the number from the register R1, sets the next address for writing (R1 + R2 + 2).  
Записать в R1 - число, R2 - месяц, R3 - год (методом непосредственной адресации).
Сформировать цикл (команда SOB). Количество прохождений = R2, и обратиться к подпрограмме (JSR, RTS), выполняющей следующее:
записывает в ячейку по адресу находящимуся в R1, квадрат числа из регистра R1, устанавливает следующий адрес для записи (R1+R2+2).  
# Task_11
Place at the addresses starting with address 200 codes of letters of your surname.
Using a survey of device readiness, interruptions, and using procedures, display your surname on the screen (text mode).  
Разместить по адресам начиная с адреса 200 коды букв своей фамилии (буквы английские).
С помощью опроса готовности устройства, прерываний и использования процедур вывести свою фамилию на экран (текстовый режим).  