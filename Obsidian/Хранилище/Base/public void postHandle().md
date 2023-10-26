#flashcards #Spring 
Data: 2023-08-14 14:03
Title: [[public void postHandle()]]
Alias:
Header:

Что такое [[public void postHandle()]]?::[[public void postHandle()]] – это метод интерфейса `HandlerInterceptor`, который отработает после контроллера, но перед формированием представления.
<!--SR:!2023-10-27,10,170-->



Body:



#Spring 
Когда применяют метод `public void postHandle()`?
!---
Ответ:
	- Метод можно использовать этот метод для добавления дополнительных атрибутов в ModelAndView или для определения времени, затрачиваемого методом-обработчиком на обработку запроса клиента.
	- Также можно добавить больше объектов модели в представление, но вы не можете изменить `HttpServletResponse`, так как он уже зафиксирован.
<!--SR:!2023-10-27,1,130-->




Главы:
-


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
