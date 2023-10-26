#flashcards
Data: 2023-07-19 16:08
Title: [[Отличия между ограничениями PRIMARY и UNIQUE]]
Alias:
Header:




Body:



#SQL 
Какие отличия между ограничениями `PRIMARY` и `UNIQUE`?
!---
Ответ:
	- По умолчанию ограничение `PRIMARY` создает кластерный индекс на столбце, а `UNIQUE` - некластерный. 
	- Другим отличием является то, что `PRIMARY` не разрешает `NULL` записей, в то время как `UNIQUE` разрешает одну (а в некоторых СУБД несколько) `NULL` запись.
<!--SR:!2023-11-01,6,310-->




Главы:
-


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
