#flashcards #Spring 
Data: 2023-08-17 12:13
Title: [[AspectJ]]
Alias:
Header:

Что такое [[AspectJ]]?::[[AspectJ]] – это стандарт реализации АОП.
<!--SR:!2023-10-27,1,550-->


Body:

#Spring 
Какие отличия имеет реализация АОП от Spring?
!---
Ответ:
	- Spring AOP немного проще, т.к. нет необходимости следить за процессом связывания.
	- Spring AOP поддерживает аннотации AspectJ, таким образом мы можем работать в спринг проекте похожим образом с AspectJ проектом.
	- Spring + AOP поддерживает только proxy-based АОП и может использовать только один тип точек соединения - Method Invocation. AspectJ поддерживает все виды точек соединения.
	- Недостатком Spring AOP является работа только со своими бинами, которые существуют в Spring Context.
<!--SR:!2023-10-27,1,130-->




Главы:
-


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
