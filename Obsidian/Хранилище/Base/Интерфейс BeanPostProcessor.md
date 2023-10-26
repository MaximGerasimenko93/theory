#flashcards #Spring 
Data: 2023-02-18 11:09
Title: [[Интерфейс BeanPostProcessor]]
Alias:
Header:

Что такое [[Интерфейс BeanPostProcessor]]?::[[Интерфейс BeanPostProcessor]] – позволяет разработчику самому имплементировать некоторые методы бинов перед инициализацией и после уничтожения экземпляров бина. Это интерфейс для обеспечения интеграции кастомной логики создания экземпляров, разрешения зависимостей и т. д. Каждый компонент, созданный `BeanFactory`, проходит через каждый зарегистрированный `BeanPostProcessor`.
<!--SR:!2023-11-03,10,270-->



Body:

#Spring 
Какие методы имеет интерфейс BeanPostProcessor?
!---
Ответ:
	- `postProcessBeforeInitialization()`
	- `postProcessAfterInitialization()`
<!--SR:!2023-11-03,10,310-->


#Spring 
Как интерфейс `BeanPostProcessor` донастраивает созданные бины?
!---
Ответ:
	- Сначала сработает метод `postProcessBeforeInitialization()` всех имеющихся `BeanPostProcessor`-ов.
	- Затем, при наличии, будет вызван метод, аннотированный `@PostConstruct`.
	- Если бин имплементирует `InitializingBean`, то Spring вызовет метод `afterPropertiesSet()` - не рекомендуется к использованию как устаревший.
	- При наличии, будет вызван метод, указанный в параметре initMethod аннотации `@Bean`.
	- В конце бины пройдут через `postProcessAfterInitialization (Object bean, String beanName)`. 
	- Именно на данном этапе создаются прокси стандартными `BeanPostProcessor`-ами. Затем отработают наши кастомные `BeanPostProcessor`-ы и применят нашу логику к прокси-объектам. После чего все бины окажутся в контейнере, который будет обязательно обновлен методом `refresh()`.
	- Но даже после этого мы можем донастроить наши бины `ApplicationListener`-ами.
<!--SR:!2023-11-01,10,348-->




#Spring 
В чем разница методов `postProcessBeforeInitialization()` и `postProcessAfterInitialization()`?
!---
Ответ:
	- У обоих методов параметры абсолютно одинаковые.
	- Разница только в порядке их вызова. 
	- Первый вызывается до init-метода, второй - после.
<!--SR:!2023-11-03,10,388-->






Главы:
- [[Интерфейс BeanFactoryPostProcessor]]


Sources:
- [ ] [Spring-потрошитель: жизненный цикл Spring Framework](https://habr.com/ru/post/720794/)
- [ ] []()
- [ ] []()
