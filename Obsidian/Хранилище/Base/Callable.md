#flashcards
Data: 2023-08-04 13:46
Title: [[Callable]]
Alias:
Header:

Что такое [[Callable]]?::[[Callable]] – это интерфейс, введенный в Java 5.0 в составе библиотеки `java.util.concurrent`. Похож на интерфейс Runnable.
<!--SR:!2023-11-03,10,730-->


Body:



Чем отличается интерфейс Callable от Runnable?
!---
Ответ:
	- Интерфейс `Runnable` появился в Java 1.0, а интерфейс `Callable` был введен в Java 5.0 в составе библиотеки `java.util.concurrent`;
	- Классы, реализующие интерфейс `Runnable` для выполнения задачи должны реализовывать метод `run()`. Классы, реализующие интерфейс `Callable` - метод `call()`;
	- Метод `Runnable.run()` не возвращает никакого значения, `Callable.call()` возвращает объект `Future`, который может содержать результат вычислений;
	- Метод `run()` не может выбрасывать проверяемые исключения, в то время как метод `call()` может.
<!--SR:!2023-11-03,10,383-->



Главы:
-


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
