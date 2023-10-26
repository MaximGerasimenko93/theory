#flashcards
Data: 2023-02-18 10:57
Title: [[Аннотация @EnableTransactionManagement]]
Alias:
Header:

Что такое [[Аннотация @EnableTransactionManagement]]?::[[Аннотация @EnableTransactionManagement]] – это аннотация, которая включает возможности управления транзакциями.
<!--SR:!2023-11-03,10,398-->


Body:


#Spring 
Что означает аннотация `@EnableTransactionManagement`?
!---
Ответ:
	- Аннотация `@EnableTransactionManagement` означает, что классы, помеченные `@Transactional`, должны быть обернуты аспектом транзакций.
	- Однако, если мы используем Spring Boot и имеем зависимости `spring-data-*` или `spring-tx`, то управление транзакциями будет включено по умолчанию.
<!--SR:!2023-10-27,1,130-->



#Spring 
Над чем нужно первым делом разместить аннотацию `@EnableTransactionManagement` для включения управления транзакциями?
!---
Ответ:
	- Для включения возможности управления транзакциями первым делом нужно разместить аннотацию `@EnableTransactionManagement` у класса-конфигурации `@Configuration`.
<!--SR:!2023-10-27,1,178-->



#Spring 
За что отвечает аннотация `@EnableTransactionManagement`?
!---
Ответ:
	- `@EnableTransactionManagement` отвечает за регистрацию необходимых компонентов Spring, таких как `TransactionInterceptor` и советы прокси (proxy advices- набор инструкций, выполняемых на точках среза – Pointcut). 
	- Регистрируемые компоненты помещают перехватчик в стек вызовов при вызове методов `@Transactional`.
<!--SR:!2023-10-27,1,130-->




Главы:
-


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
