#flashcards
Data: 2023-08-30 12:25
Title: [[Жизненный цикл entity]]
Alias:
Header:




Body:




#Hibernate 
Опишите жизненный цикл сущности.
!---
Ответ:
	- new – объект создан, не имеет primary key
    - managed – объект создан, имеет primary key, управляется JPA
    - detached – объект создан, не управляется JPA
    - removed – объект создан, управляется JPA, будет удален при commit-е
<!--SR:!2023-11-03,10,350-->




Главы:
- [[Операции над entity]]


Sources:
- [ ] [Hibernate вопросы-ответы](https://docs.google.com/document/d/104EUUT-gv7xSalJlJu0DInzlyCVFjC5Sz2gcDoVtfyE/edit)
- [ ] []()
- [ ] []()
