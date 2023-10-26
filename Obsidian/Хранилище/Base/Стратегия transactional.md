#flashcards #Hibernate 
Data: 2023-09-13 10:36
Title: [[Стратегия transactional]]
Alias:
Header:

Что такое [[Стратегия transactional]]?::[[Стратегия transactional]] – это полноценное разделение транзакций.
<!--SR:!2023-10-27,1,130-->



Body:



#Hibernate 
Что происходит при стратегии `transactional`?
!---
Ответ:
	- Каждая сессия и каждая транзакция видят объекты, как если бы только они с ним работали последовательно одна транзакция за другой.
<!--SR:!2023-10-27,1,130-->



#Hibernate 
Какие недостатки есть у стратегии `transactional`?
!---
Ответ:
	- Блокировки и потеря производительности.
<!--SR:!2023-10-28,10,170-->


Главы:
-


Sources:
- [ ] [Hibernate вопросы-ответы](https://docs.google.com/document/d/104EUUT-gv7xSalJlJu0DInzlyCVFjC5Sz2gcDoVtfyE/edit)
- [ ] []()
- [ ] []()
