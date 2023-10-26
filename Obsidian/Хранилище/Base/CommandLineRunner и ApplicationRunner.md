#flashcards #Spring 
Data: 2023-08-15 12:01
Title: [[CommandLineRunner и ApplicationRunner]]
Alias:
Header:

Что такое [[CommandLineRunner и ApplicationRunner]]?::[[CommandLineRunner и ApplicationRunner]] – это интерфейсы, для запуска логики при запуске приложения, после создания экземпляра контекста приложения Spring.
<!--SR:!2023-11-03,10,710-->


Body:



#Spring 
Какое единственное отличие между `CommandLineRunner` и `ApplicationRunner`?
!---
Ответ:
	- `CommandLineRunner.run()` принимает в качестве параметра`String array[]`
	- `ApplicationRunner.run()` принимает `ApplicationArguments` в качестве аргумента
<!--SR:!2023-11-03,10,305-->




Главы:
-


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
