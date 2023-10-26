#flashcards #Spring 
Data: 2023-03-02 20:01
Title: [[Spring Security]]
Alias:
Header:

Что такое [[Spring Security]]?::[[Spring Security]] – Фреймворк аутентификации и авторизации.
<!--SR:!2023-11-03,10,430-->


Body:



#Spring 
Что предоставляет Spring Security?
!---
Ответ:
	- Spring Security предоставляет широкие возможности для защиты приложения.
	- Кроме стандартных настроек для аутентификации, авторизации и распределения ролей и маппинга доступных страниц, ссылок и т.п., предоставляет защиту от различных вариантов атак
<!--SR:!2023-11-04,10,421-->



#Spring 
Что представляет из себя Spring Security?
!---
Ответ:
	- Это список фильтров в виде класса `FilterChainProxy`, интегрированного в контейнер сервлетов, и в котором есть поле `List`. Каждый фильтр реализует какой-то механизм безопасности. Важна последовательность фильтров в цепочке.
<!--SR:!2023-10-31,5,270-->




Главы:
- [[Основные классы и интерфейсы Spring Security]]
- [[DelegatingFilterProxy]]
- [[Аннотация @EnableGlobalMethodSecurity]]
- [[Аннотация @EnableWebMvcSecurity]]
- [[Аннотация @PreAuthorize]]
- 

Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
