#flashcards #Журналирование 
Data: 2023-07-21 13:17
Title: [[Appender]]
Alias:
Header:

Что такое [[Appender]]?::[[Appender]] – это именованный объект журнала событий, реализующий интерфейс `org.apache.log4j.Appender` и добавляющий события в журнал. Appender вызывает разные вспомогательные инструменты - компоновщик, фильтр, обработчик ошибок (если они определены и необходимы). В ходе этой работы окончательно устанавливается необходимость записи сообщения, сообщению придаются окончательные содержание и форма.
<!--SR:!2023-11-03,10,470-->


Body:



#Журналирование 
Что представляет собой журнал в log4j?
!---
Ответ:
	- консоль
	- файл
	- сокет
	- объект класса реализующего `java.io.Writer` или `java.io.OutputStream`
	- JDBC хранилище
	- тему (topic) JMS
	- NT Event Log
	- SMTP
	- Syslog
	- Telnet
<!--SR:!2023-11-03,10,270-->




Главы:
- [[Часто используемые Appender]]


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
