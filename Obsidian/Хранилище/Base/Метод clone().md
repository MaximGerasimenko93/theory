#flashcards
Data: 2023-02-04 21:11
Title: [[Метод clone()]]
Alias:
Header:




Body:


Расскажите о методе `clone()`.
!---
Ответ:
	- Класс `Object` содержит `protected` метод `clone()`, осуществляющий побитовое копирование объекта производного класса.
	- Однако сначала необходимо переопределить метод `clone()` как `public` для обеспечения возможности его вызова.
	- В переопределенном методе следует вызвать базовую версию метода `super.clone()`, которая и выполняет собственно клонирование.
<!--SR:!2023-11-03,10,510-->



Главы:
-


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
