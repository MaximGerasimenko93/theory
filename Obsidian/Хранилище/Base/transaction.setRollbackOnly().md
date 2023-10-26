#flashcards #Hibernate 
Data: 2023-09-18 10:55
Title: [[transaction.setRollbackOnly()]]
Alias:
Header:

Что такое [[transaction.setRollbackOnly()]]?::[[transaction.setRollbackOnly()]] – это метод, который помечает транзакцию как откаченную в будущем.
<!--SR:!2023-10-27,1,130-->



Body:


#Hibernate 
Чем отличается метод `setRollbackOnly()` от `rollback()`?
!---
Ответ:
	- В отличие от `rollback()` метод `setRollbackOnly()` не закрывает транзакцию и все последующие запросы к базе будут продолжать выполняться в рамках той же самой транзакции.
	- Но завершить эту транзакцию можно будет только откатом и вызовом `rollback()`.
<!--SR:!2023-10-27,1,130-->


#Hibernate 
Что произойдет при вызове метода `commit()` у объекта `transaction.setRollbackOnly()`?
!---
Ответ:
	- Вызов `commit()` на такой транзакции выбросит исключение.
<!--SR:!2023-10-31,6,330-->


Главы:
-


Sources:
- [ ] [Hibernate вопросы-ответы](https://docs.google.com/document/d/104EUUT-gv7xSalJlJu0DInzlyCVFjC5Sz2gcDoVtfyE/edit)
- [ ] []()
- [ ] []()
