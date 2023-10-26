#flashcards
Data: 2023-08-03 11:13
Title: [[Safe publication]]
Alias:
Header:

Что такое [[Safe publication]]?::[[Safe publication]] – это показ объектов другим потокам из текущего, не нарушая ограничений _visibility_.
<!--SR:!2023-10-27,1,130-->


Body:

Какие есть способы safe publication в Java?
!---
Ответ:
	- `static{}` инициализатор;
	- `volatile` переменные;
	- `atomic` переменные;
	- сохранение в разделяемой переменной, корректно защищенной с использованием `synchronized()`, синхронизаторов или других конструкций, создающих _read/write memory barrier_;
	- `final` переменные в разделяемом объекте, который был корректно проинициализирован.
<!--SR:!2023-10-30,10,210-->




Главы:
-


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
