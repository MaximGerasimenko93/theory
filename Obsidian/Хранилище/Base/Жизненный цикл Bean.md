#flashcards #Spring 
Data: 2023-02-18 11:00
Title: [[Жизненный цикл Bean]]
Alias:
Header:

Что такое [[Жизненный цикл Bean]]?::[[Жизненный цикл Bean]] – это время существования класса.
<!--SR:!2023-11-03,10,470-->



Body:



#Spring 
Опишите весь жизненный цикл бинов.
!---
Ответ:
	-   1. Парсирование конфигурации и создание BeanDefinition
	- 2. Настройка созданных BeanDefinition
	- 3. Создание кастомных FactoryBean (только для XML-конфигурации)
	- 4. Создание экземпляров бинов
	- 5. Настройка созданных бинов
	- 6. Бины готовы к использованию
	- 7. Закрытие контекста
<!--SR:!2023-11-03,10,256-->






Главы:
- [[Интерфейс BeanPostProcessor]]
- [[Bean scopes]]


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
