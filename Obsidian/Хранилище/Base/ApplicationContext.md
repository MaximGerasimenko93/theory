#flashcards #Spring 
Data: 2023-03-13 21:13
Title: [[ApplicationContext]]
Alias:
Header:

Что такое [[ApplicationContext]]?::[[ApplicationContext]] – это интерфейс, реализации которого создают компоненты приложения, связывает их вместе, настраивает и управляет ими от создания до момента уничтожения. Т.е. обеспечивает жизненный цикл. Компоненты после создания хранятся в контексте и называются бинами [[Bean]]. В упрощенном виде контекст можно представить, как Map, где ключом является id бина. 
<!--SR:!2023-11-03,10,310-->



Body:


#Spring 
Что представляет собой ApplicationContext?
!---
Ответ:
	- Интерфейс ApplicationContext представляет собой [[IoC Container]].
<!--SR:!2023-11-03,10,330-->


#Spring 
Каким интерфейсом определен ApplicationContext?
!---
Ответ:
	- Этот контейнер определяется интерфейсом org.springframework.context.ApplicationContext.
<!--SR:!2023-11-03,10,405-->


#Spring 
Чьи наследником является ApplicationContext?
!---
Ответ:
	- ApplicationContext является наследником [[BeanFactory]].
<!--SR:!2023-11-03,10,385-->

#Spring
Что нужно класть в [[ApplicationContext]]?
!---
Можно класть:
	- Бизнес-сервисы (DAO, Services)
	- Подключения к внешним системам
	- Мапперы/Маршаллеры/конвертеры
	- Служебные бины
	- Бизнес-бины стратегий (Паттерн стратегия)
<!--SR:!2023-11-03,10,290-->


#Spring
Что НЕЛЬЗЯ класть в [[ApplicationContext]]?
!---
Нельзя класть:
	- Бизнес-объекты (пользователи)
	- Настройки (отдельно, сгруппированные в класс можно) 
	- Объекты, которые понадобятся только один раз в один момент (временные) 
	- Стандартные классы (String, InputStream, Locale)
<!--SR:!2023-11-04,10,310-->




Главы:
- [[IoC Container]]
- [[Bean]]
- [[Отличия ApplicationContext от BeanFactory]]
- [[Реализация ApplicationContext]]
- [[Основные этапы поднятия ApplicationContext]]
- [[Дополнительный функционал ApplicationContext]]
- [[CommandLineRunner и ApplicationRunner]]


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
