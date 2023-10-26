#flashcards #Spring 
Data: 2023-08-14 14:06
Title: [[public void afterCompletion()]]
Alias:
Header:

Что такое [[public void afterCompletion()]]?::[[public void afterCompletion()]] – это метод интерфейса `HandlerInterceptor`, который отработает после формирования представления.
<!--SR:!2023-11-03,10,230-->



Body:


#Spring 
Когда вызывают метод `public void afterCompletion()`?
!---
Ответ:
	- Метод `public void afterCompletion()` вызывают только в том случае, если метод `preHandle()` этого перехватчика успешно завершен и вернул true.
<!--SR:!2023-10-27,10,248-->




Главы:
-


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
