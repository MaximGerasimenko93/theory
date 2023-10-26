#flashcards #Hibernate 
Data: 2023-08-30 12:51
Title: [[Table per concrete class strategy]]
Alias:
Header:

Что такое [[Table per concrete class strategy]]?::[[Table per concrete class strategy]] – это стратегия, где каждый отдельный класс-наследник имеет свою таблицу.
<!--SR:!2023-11-03,10,370-->



Body:




#Hibernate 
Какой есть недостаток у стратегии Table per concrete class strategy?
!---
Ответ:
	- Table per concrete class strategy плохо поддерживает полиморфизм.
	- Также для выборки всех классов иерархии потребуются большое количество отдельных SQL-запросов или использование UNION-запроса.
<!--SR:!2023-11-03,10,350-->


Главы:
-


Sources:
- [ ] [Hibernate вопросы-ответы](https://docs.google.com/document/d/104EUUT-gv7xSalJlJu0DInzlyCVFjC5Sz2gcDoVtfyE/edit)
- [ ] []()
- [ ] []()
