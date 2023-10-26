#flashcards #Hibernate 
Data: 2023-08-28 13:19
Title: [[SessionFactory]]
Alias:
Header:

Что такое [[SessionFactory]]?::[[SessionFactory]] – это фабрика для объектов `Session`. Является потокобезопасным объектом и используется всеми потоками приложения.
<!--SR:!2023-11-03,10,350-->



Body:


#Hibernate 
Когда происходит создание `SessionFactory`?
!---
Ответ:
	- Обычно `SessionFactory` создают во время запуска приложения и сохраняют для последующего использования.
<!--SR:!2023-11-03,10,350-->



#Hibernate 
Как `SessionFactory` создает объект `Session`?
!---
Ответ:
	- С помощью метода `openSession()`
<!--SR:!2023-11-03,10,370-->


#Hibernate 
Сколько объектов `SessionFactory` создают на приложение?
!---
Ответ:
	- На все приложение должен существовать только один объект `SessionFactory`, как и `ConnectionPool`.
<!--SR:!2023-11-03,10,390-->


Главы:
- [[Session]]


Sources:
- [ ] [Hibernate вопросы-ответы](https://docs.google.com/document/d/104EUUT-gv7xSalJlJu0DInzlyCVFjC5Sz2gcDoVtfyE/edit)
- [ ] []()
- [ ] []()
