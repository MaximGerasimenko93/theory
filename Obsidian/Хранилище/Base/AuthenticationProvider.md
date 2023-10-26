#flashcards #Spring 
Data: 2023-08-23 13:22
Title: [[AuthenticationProvider]]
Alias:
Header:

Что такое [[AuthenticationProvider]]?::[[AuthenticationProvider]] – это интерфейс объекта, выполняющего аутентификацию. Имеет массу готовых реализаций. Также можем задать свой тип аутентификации.
<!--SR:!2023-11-03,10,250-->



Body:

#Spring 
Чем `AuthenticationProvider` отличается от `AuthenticationManager`?
!---
Ответ:
	- `AuthenticationProvider` немного похож на `AuthenticationManager`, но у него есть дополнительный метод, позволяющий вызывающей стороне спрашивать, поддерживает ли он переданный ему объект Authentication, возможно этот AuthenticationProvider может поддерживать только аутентификацию по логину и паролю
<!--SR:!2023-11-05,10,170-->




Главы:
-


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
