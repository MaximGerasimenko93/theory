#flashcards
Data: 2023-02-13 15:14
Title: [[Типы реализации Dependency Injection]]
Alias:
Header:




Body:



#Spring 
Какие есть типы реализации внедрения зависимостей?
!---
Ответ:
	- Constructor Dependency Injection – это тип внедрения зависимостей, при котором зависимости компонента предоставляются ему в его конструкторе (или конструкторах). Рекомендуется как основной способ, т.к. даже без спринга внедрение зависимостей будет работать корректно.
	- Setter Dependency Injection – контейнер IoC внедряет зависимости компонента в компонент через методы установки в стиле JavaBean. В основном через сеттеры. При модификации не создает новые экземпляры, в отличии от конструктора. Он при каждой модификации создаёт новый экземпляр.
<!--SR:!2023-11-04,10,330-->





Главы:
-


Sources:
- [ ] [Spring вопросы-ответы](https://docs.google.com/document/d/1eFbKDhPfud_Kj07jHhj-OmZuEfHYWe4HaLUW4pRkZ9U/edit#heading=h.26f0p2oxn1f9)
- [ ] []()
- [ ] []()
