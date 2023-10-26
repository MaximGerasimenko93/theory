#flashcards #Hibernate 
Data: 2023-08-30 12:45
Title: [[Single table per class hierarchy]]
Alias:
Header:

Что такое [[Single table per class hierarchy]]?::[[Single table per class hierarchy]] – это одна таблица на всю иерархию наследования. Все `entity`, со всеми наследниками записываются в одну таблицу, для идентификации типа `entity` определяется специальная колонка “discriminator column”
<!--SR:!2023-11-03,10,370-->



Body:


#Hibernate 
Какой есть недостаток у стратегии Single table per class hierarchy?
!---
Ответ:
	- Минус – в общей таблице будут созданы все поля уникальные для каждого из классов-потомков, которые были пусты для всех других классов-потомков.
<!--SR:!2023-11-04,10,390-->




Главы:
-


Sources:
- [ ] [Hibernate вопросы-ответы](https://docs.google.com/document/d/104EUUT-gv7xSalJlJu0DInzlyCVFjC5Sz2gcDoVtfyE/edit)
- [ ] []()
- [ ] []()
