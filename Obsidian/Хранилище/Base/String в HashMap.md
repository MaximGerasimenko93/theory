#flashcards
Data: 2023-02-04 12:50
Title: [[String в HashMap]]
Alias:
Header:




Body:


Почему строка является популярным ключем в `HashMap`?
!---
Ответ:
	- Поскольку строки неизменяемы, их хэш код вычисляется и кэшируется в момент создания, не требуя повторного пересчета при дальнейшем использовании. 
	- Поэтому в качестве ключа `HashMap` они будут обрабатываться быстрее.
<!--SR:!2023-11-03,10,570-->




Главы:
-


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
