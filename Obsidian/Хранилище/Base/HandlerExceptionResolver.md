#flashcards #Spring 
Data: 2023-08-15 11:43
Title: [[HandlerExceptionResolver]]
Alias:
Header:

Что такое [[HandlerExceptionResolver]]?::[[HandlerExceptionResolver]] – это интерфейс, предназначенный для работы с непредвиденными исключениями, возникающими во время выполнения обработчиков.
<!--SR:!2023-11-05,10,590-->


Body:



#Spring 
Как происходит работа по умолчанию интерфейса `HandlerExceptionResolver`?
!---
Ответ:
	- По умолчанию `DispatcherServlet` регистрирует класс `DefaultHandlerExceptionResolver` (из пакета `org.springframework.web.servlet.mvc.support`). Этот распознаватель обрабатывает определенные стандартные исключения Spring MVC, устанавливая специальный код состояния ответа.
<!--SR:!2023-10-27,1,130-->







Главы:
- [[Исключения в Spring MVC]]


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
