# OOP-Labs
 
**Лабораторная работа 1**

***Вариант 14***

Напишите метод, который заменяет каждый n-ый символ oldValue на newValue. 
 
*Входные данные* 

text: строка для модификации 

n: номер целевой буквы  

old_value : целевой символ

new_value : символ, который следует использовать в качестве замены 
  
*Правила* 

Если n равно 0 или отрицательно, или если оно больше, чем счетчик oldValue, вернуть исходный 
текст без изменений.

*Пример:* 

n:         2 

old_value: 'a' 

new_value: 'o' 

"Vader said: No, I am your father!" -> "Vader soid: No, I am your fother!" 

**Лабораторная работа 2**

***Вариант 14***

Создать класс BitString для работы с битовыми строками. Битовая строка должна быть представлена 
массивом типа unsigned char, каждый элемент которого принимает значение 0 или 1. Должны быть 
реализованы все традиционные операции для работы с битовыми строками: and, or, xor, not.  

**Лабораторная работа 3-4**

***Вариант 30***

Фигура 1 - 5-угольник
Фигура 2 - 6-угольник
Фигура 3 - 8-угольник

**Лабораторная работа 5**

***Вариант 2***

*Контейнер* - Стек

*Стратегия работы memory_resource - 1*
Фиксированный блок памяти (выделяется один раз), информация о 
выделенных блоках памяти хранится в std::list 

