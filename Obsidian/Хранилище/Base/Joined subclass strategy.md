#flashcards #Hibernate 
Data: 2023-08-30 12:49
Title: [[Joined subclass strategy]]
Alias:
Header:

Что такое [[Joined subclass strategy]]?::[[Joined subclass strategy]] – это объединяющая стратегия, где каждый класс `entity` сохраняет данные в свою таблицу, но только уникальные колонки (не унаследованные от классов-предков) и первичный ключ, а все унаследованные колонки записываются в таблицы класса-предка, дополнительно устанавливается связь (relationships) между этими таблицами.
<!--SR:!2023-11-03,10,750-->


Body:




#Hibernate 
Какой есть недостаток у стратегии Joined subclass strategy?
!---
Ответ:
	- Минусом тут являются потери производительности от объединения таблиц (join) для любых операций.
<!--SR:!2023-11-03,10,367-->



Главы:
-


Sources:
- [ ] [Hibernate вопросы-ответы](https://docs.google.com/document/d/104EUUT-gv7xSalJlJu0DInzlyCVFjC5Sz2gcDoVtfyE/edit)
- [ ] []()
- [ ] []()
