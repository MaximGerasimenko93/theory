#flashcards
Data: 2023-08-04 14:28
Title: [[Различия между interrupted() и isInterrupted()]]
Alias:
Header:




Body:



В чем разница между `interrupted()` и `isInterrupted()`?
!---
Ответ:
	- Когда прерванный поток проверяет статус прерывания, вызывая статический метод `Thread.interrupted()`, статус прерывания сбрасывается.
	- Нестатический метод `isInterrupted()` используется одним потоком для проверки статуса прерывания у другого потока, не изменяя флаг прерывания.
<!--SR:!2023-11-05,10,390-->




Главы:
-


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
