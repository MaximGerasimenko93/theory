#flashcards #Hibernate 
Data: 2023-08-30 12:54
Title: [[MappedSuperclass]]
Alias:
Header:

Что такое [[MappedSuperclass]]?::[[MappedSuperclass]] – это класс от которого наследуются `Entity`, он может содержать аннотации JPA
<!--SR:!2023-11-04,10,370-->



Body:



#Hibernate 
Является ли класс `MappedSuperclass` `Entity`?
!---
Ответ:
Сам класс `MappedSuperclass` не является `Entity`, ему не обязательно выполнять все требования установленные для `Entity`.
<!--SR:!2023-11-04,10,390-->




#Hibernate 
Где нельзя использовать класс `MappedSuperclass`?
!---
Ответ:
	- Класс `MappedSuperclass` нельзя использовать в операциях `EntityManager` или `Query`.
<!--SR:!2023-11-03,10,290-->


#Hibernate 
Какой аннотацией помечают класс `MappedSuperclass`?
!---
Ответ:
	- Класс `MappedSuperclass` помечают аннотацией `@MappedSuperclass` или описывают в XML-файле.
<!--SR:!2023-11-04,10,390-->




Главы:
- [[Entity]]


Sources:
- [ ] [Hibernate вопросы-ответы](https://docs.google.com/document/d/104EUUT-gv7xSalJlJu0DInzlyCVFjC5Sz2gcDoVtfyE/edit)
- [ ] []()
- [ ] []()
