#flashcards #Spring 
Data: 2023-08-23 12:44
Title: [[UserDetails]]
Alias:
Header:

Что такое [[UserDetails]]?::[[UserDetails]] – это интерфейс, представляющий учетную запись пользователя.
<!--SR:!2023-11-03,10,710-->


Body:


#Spring 
Кто должен имплементировать интерфейс `UserDetails`?
!---
Ответ:
	- Как правило модель нашего пользователя должна имплементировать `UserDetails`.
<!--SR:!2023-11-03,10,405-->



#Spring 
Что хранит модель, реализующая интерфейс `UserDetails`?
!---
Ответ:
	- Она просто хранит пользовательскую информацию в виде логина, пароля и флагов `isAccountNonExpired`, `isAccountNonLocked`, `isCredentialsNonExpired`, `isEnabled`, а также коллекции прав (ролей) пользователя.
<!--SR:!2023-11-03,10,345-->


#Spring 
Во что еще инкапсулируется пользовательская информация модели, которая реализующая интерфейс `UserDetails`?
!---
Ответ:
	- В `Authentication`.
<!--SR:!2023-11-03,10,305-->


Главы:
-


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
