#flashcards #Hibernate 
Data: 2023-09-13 10:45
Title: [[Стратегия nonstrict-read-write]]
Alias:
Header:

Что такое [[Стратегия nonstrict-read-write]]?::[[Стратегия nonstrict-read-write]] – это аналогичная `read-write` стратегия, но изменения объектов могут запаздывать и транзакции могут видеть старые версии объектов.
<!--SR:!2023-10-27,1,130-->



Body:


#Hibernate 
Когда рекомендуется использовать стратегию `nonstrict-read-write`?
!---
Ответ:
	- Ее стоит использовать в случаях, когда одновременное обновление объектов маловероятно и не может привести к проблемам.
<!--SR:!2023-10-27,1,130-->




Главы:
-


Sources:
- [ ] [Hibernate вопросы-ответы](https://docs.google.com/document/d/104EUUT-gv7xSalJlJu0DInzlyCVFjC5Sz2gcDoVtfyE/edit)
- [ ] []()
- [ ] []()
