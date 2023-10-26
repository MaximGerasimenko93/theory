#flashcards #Spring 
Data: 2023-08-23 13:00
Title: [[AuthenticationManager]]
Alias:
Header:

Что такое [[AuthenticationManager]]?::[[AuthenticationManager]] – это основной стратегический интерфейс для аутентификации.
<!--SR:!2023-11-03,10,690-->


Body:



#Spring 
Какой метод имеет `AuthenticationManager`?
!---
Ответ:
	- `AuthenticationManager` имеет только один метод, который срабатывает, когда пользователь пытается аутентифицироваться в системе – `authenticate(Authentication authentication)`
<!--SR:!2023-10-31,10,385-->



#Spring 
Что может сделать метод `authenticate()`?
!---
Ответ:
	- AuthenticationManager может сделать одну из 3 вещей в своем методе authenticate():
	-
	- вернуть `Authentication (с authenticated=true)`, если предполагается, что вход осуществляет корректный пользователь
	- бросить `AuthenticationException`, если предполагается, что вход осуществляет некорректный пользователь
	- вернуть `null`, если принять решение не представляется возможным
<!--SR:!2023-10-30,10,305-->


Главы:
- [[ProviderManager]]


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
