#flashcards
Data: 2023-02-02 21:57
Title: [[Reference counting]]
Alias:
Header:

Что такое [[Reference counting]]?::[[Reference counting]] – это подход к обнаружению мусора.
<!--SR:!2023-11-03,10,710-->




Body:



В чем суть reference counting?
!---
Ответ:
	- Суть этого подхода состоит в том, что каждый объект имеет счетчик. Счетчик хранит информацию сколько ссылок указывает на объект.
	- Когда ссылка уничтожается, счетчик уменьшается. Если значение счетчика равно нулю – объект можно считать мусором. 
	- Главный минус такого подхода является сложность обеспечения точности счетчика. 
	- При таком подходе сложно выявлять циклические зависимости (когда два объекта указывают друг на друга, но ни один живой объект на них не ссылается), что приводит к утечкам памяти.
<!--SR:!2023-11-03,10,710-->




Главы:
-


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] [Избавляемся от мусора в Java](https://habr.com/ru/company/otus/blog/553996/)
- [ ] []()
