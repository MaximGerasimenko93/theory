#flashcards #SQL 
Data: 2023-07-19 16:16
Title: [[Оператор MERGE]]
Alias:
Header:

Что такое [[Оператор MERGE]]?::[[Оператор MERGE]] – это оператор, который позволяет осуществить слияние данных одной таблицы с данными другой таблицы.
<!--SR:!2023-11-03,10,450-->



Body:



#SQL 
Как происходит слияние таблиц с помощью `MERGE`?
!---
Ответ:
	- При слиянии таблиц проверяется условие, и если оно истинно, то выполняется `UPDATE`, а если нет - `INSERT`. 
	- При этом изменять поля таблицы в секции `UPDATE`, по которым идет связывание двух таблиц, нельзя.
<!--SR:!2023-10-31,5,270-->




Главы:
-


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
