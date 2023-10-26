#flashcards #Hibernate 
Data: 2023-08-30 12:16
Title: [[Аннотация @Enumerated]]
Alias:
Header:

Что такое [[Аннотация @Enumerated]]?::[[Аннотация @Enumerated]] – это аннотация, которая указывает, следует ли сохранять `Enum` по имени или по порядковому номеру (по умолчанию).
<!--SR:!2023-11-03,10,750-->


Body:



#Hibernate 
Какие атрибуты содержит аннотация `@Enumerated`?
!---
Ответ:
	- `@Enumerated(EnumType.STRING)`
	- `@Enumerated(EnumType.ORDINAL)`
<!--SR:!2023-11-03,10,407-->



#Hibernate 
Что означает атрибут `@Enumerated(EnumType.STRING)`?
!---
Ответ:
	- `@Enumerated(EnumType.STRING)` означает, что в базе будут храниться имена `Enum`.
<!--SR:!2023-11-03,10,387-->



#Hibernate 
Что означает атрибут `@Enumerated(EnumType.ORDINAL)`?
!---
Ответ:
	- `@Enumerated(EnumType.ORDINAL)` означает, что в базе будут храниться порядковые номера Enum.
<!--SR:!2023-11-03,10,387-->



Главы:
-


Sources:
- [ ] [Hibernate вопросы-ответы](https://docs.google.com/document/d/104EUUT-gv7xSalJlJu0DInzlyCVFjC5Sz2gcDoVtfyE/edit)
- [ ] []()
- [ ] []()
