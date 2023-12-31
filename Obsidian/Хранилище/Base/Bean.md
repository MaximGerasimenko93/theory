#flashcards #Spring 
Data: 2023-02-05 10:56
Title: [[Bean]]
Alias:
Header:

Что такое [[Bean]]?::[[Bean]] – это объект со всеми необходимыми зависимостями, который был создан с помощью [[IoC Container]]
<!--SR:!2023-11-03,10,410-->



Body:


#Spring 
Как создают экземпляр Bean?
!---
Ответ:
	- Сначала BeanFactory из коллекции Map с объектами BeanDefinition достаёт те из них, из которых создаёт все BeanPostProcessor-ы, необходимые для настройки обычных бинов. 
	- Создаются экземпляры бинов через BeanFactory на основе ранее созданных BeanDefinition
<!--SR:!2023-11-03,10,290-->



#Spring 
Какие свойства определяют Bean?
!---
Ответ:
	- class – этот атрибут является обязательным и указывает конкретный класс Java-приложения, который будет использоваться для создания бина
	- name – Уникальный идентификатор бина
	- scope – это свойство определяет область видимости создаваемых объектов
	- constructor-arg – определяет конструктор, использующийся для внедрения зависимости
	- properties – определяет свойства внедрения зависимости.
	- initialization method – здесь определяется метод инициализации бина
	- destruction method – метод уничтожения бина, который будет использоваться при уничтожении контейнера, содержащего бин
	- autowiring mode – определяет режим автоматического связывания при внедрении зависимости
	- lazy-initialization mode – режим ленивой инициализации даёт контейнеру IoC команду создавать экземпляр бина при первом запросе, а не при запуске приложения
<!--SR:!2023-11-03,10,346-->



Главы:
- [[BeanFactory]]
- [[Dependency Injection]]
- [[Dependency Lookup]]
- [[Жизненный цикл Bean]]
- [[Metadata]]


Sources:
- [ ] [Spring вопросы-ответы](https://docs.google.com/document/d/1eFbKDhPfud_Kj07jHhj-OmZuEfHYWe4HaLUW4pRkZ9U/edit#heading=h.26f0p2oxn1f9)
- [ ] []()
- [ ] []()
