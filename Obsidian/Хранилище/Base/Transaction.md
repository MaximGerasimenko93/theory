#flashcards #Hibernate 
Data: 2023-08-28 13:24
Title: [[Transaction]]
Alias:
Header:

Что такое [[Transaction]]?::[[Transaction]] – это однопоточный короткоживущий объект в Hibernate, используемый для атомарных операций. Это абстракция приложения от основных JDBC транзакций.
<!--SR:!2023-11-02,10,230-->



Body:



#Hibernate 
Сколько `Transaction` может занимать `Session`?
!---
Ответ:
	- `Session` может занимать несколько `Transaction` в определенных случаях, является необязательным API.
<!--SR:!2023-11-03,10,350-->



#Hibernate 
Как получить объект `Transaction`?
!---
Ответ:
	- С объектом `Session` всегда связан ровно один объект `Transaction`, доступ к которому может быть получен вызовом `getTransaction()`.
<!--SR:!2023-11-03,10,348-->


#Hibernate 
Как начать транзакцию?
!---
Ответ:
	- Транзакцию можно начать вызовом метода `beginTransaction()` у объекта `Session`
	- Либо запросить у `Session` связанный с ней объект `Transaction` и позвать у последнего метод `begin()`.
<!--SR:!2023-11-04,10,348-->



#Hibernate 
Какие методы кроме `commit()` и `rollback()` поддерживает объект `Transactional`?
!---
Ответ:
	- isActive()
	- setRollbackOnly()
	- getRollbackOnly()
<!--SR:!2023-11-03,10,230-->



Главы:
- [[Session]]
- [[transaction.isActive()]]
- [[transaction.setRollbackOnly()]]
- [[transaction.getRollbackOnly()]]


Sources:
- [ ] [Hibernate вопросы-ответы](https://docs.google.com/document/d/104EUUT-gv7xSalJlJu0DInzlyCVFjC5Sz2gcDoVtfyE/edit)
- [ ] []()
- [ ] []()
