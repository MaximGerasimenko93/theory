#flashcards #Spring 
Data: 2023-08-15 12:12
Title: [[Model View Controller]]
Alias:
Header:

Что такое [[Model View Controller]]?::[[Model View Controller]] – это схема разделения данных приложения и управляющей логики на три отдельных компонента: модель, представление и контроллер – таким образом, что модификация каждого компонента может осуществляться независимо
<!--SR:!2023-10-31,5,330-->



Body:



#Spring 
Назовите компоненты MVC.
!---
Ответ:
	- Model
	- View
	- Controller
<!--SR:!2023-11-01,7,370-->



#Spring 
Какие зоны ответственности у компонентов MVC: Модели, Представления и Контроллера?
!---
Ответ:
	- Модель (_Model_) предоставляет данные и реагирует на команды контроллера, изменяя своё состояние
	- Представление (_View_) отвечает за отображение данных модели пользователю, реагируя на изменения модели
	- Контроллер (_Controller_) интерпретирует действия пользователя, оповещая модель о необходимости изменений
<!--SR:!2023-11-03,10,270-->




Главы:
- [[ModelAndView]]
- [[Model]]
- [[View]]
- [[Controller]]


Sources:
- [ ] [Model-View-Controller](https://ru.wikipedia.org/wiki/Model-View-Controller)
- [ ] [Паттерны для новичков: MVC vs MVP vs MVVM](https://habr.com/ru/articles/215605/)
- [ ] [Что такое MVC: рассказываем простыми словами](https://ru.hexlet.io/blog/posts/chto-takoe-mvc-rasskazyvaem-prostymi-slovami)
