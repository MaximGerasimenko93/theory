#flashcards
Data: 2023-01-10 18:59
Title: [[Различия между Heap и Stack]]
Alias:
Header:


Body:


Чем отличаются между собой Heap и Stack?
!---
Ответ:
	- Куча используется всеми частями приложения, в то время как стек используется только одним потоком исполнения программы.
	- Всякий раз, когда создается объект, он всегда хранится в куче, а в памяти стека содержится лишь ссылка на него. Память стека содержит только локальные переменные примитивных типов и ссылки на объекты в куче.
	- Объекты в куче доступны с любой точки программы, в то время как стековая память не может быть доступна для других потоков.
	- Стековая память существует лишь какое-то время работы программы, а память в куче живет с самого начала до конца работы программы.
	- Если память стека полностью занята, то Java Runtime бросает исключение `java.lang.StackOverflowError`.
	- Если заполнена память кучи, то бросается исключение `java.lang.OutOfMemoryError`: Java Heap Space.
	- Размер памяти стека намного меньше памяти в куче.
	- Из-за простоты распределения памяти, стековая память работает намного быстрее кучи.
	- Для определения начального и максимального размера памяти в куче используются `-Xms` и `-Xmx` опции JVM. Для стека определить размер памяти можно с помощью опции `-Xss`.
<!--SR:!2023-11-03,10,430-->



Чем отличаются между собой Heap и Stack с точки зрения многопоточности?
!---
Ответ:
	- **Cтек** – участок памяти, тесно связанный с потоками. У каждого потока есть свой стек, которые хранит локальные переменные, параметры методов и стек вызовов. Переменная, хранящаяся в стеке одного потока, не видна для другого.
	- **Куча** – общий участок памяти, который делится между всеми потоками. Объекты, неважно локальные или любого другого уровня, создаются в куче. Для улучшения производительности, поток обычно кэширует значения из кучи в свой стек, в этом случае для того, чтобы указать потоку, что переменную следует читать из кучи используется ключевое слово `volatile`.
<!--SR:!2023-11-03,10,430-->



Главы:
- [[Heap]]
- [[Stack]]


Sources:
- [ ] [Вопросы для собеседования Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
