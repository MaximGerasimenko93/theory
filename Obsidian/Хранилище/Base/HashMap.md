#flashcards #Collections 
Data: 2023-02-08 11:32
Title: [[HashMap]]
Alias:
Header:

Что такое [[HashMap]]?::[[HashMap]] – основан на хэш-таблицах, реализует интерфейс Map (что подразумевает хранение данных в виде пар ключ/значение). Ключи и значения могут быть любых типов, в том числе и null.
<!--SR:!2023-11-03,10,610-->



Body:



#Collections 
Как устроен `HashMap`?
!---
Ответ:
	- `HashMap` состоит из "корзин" (bucket). 
	- С технической точки зрения "корзины" – это элементы массива, которые хранят ссылки на списки элементов. 
	- При добавлении новой пары "ключ-значение", вычисляет хэш-код ключа, на основании которого вычисляется номер корзины (номер ячейки массива), в которую попадет новый элемент.
	- Если корзина пустая, то в нее сохраняется ссылка на вновь добавляемый элемент, если же там уже есть элемент, то происходит последовательный переход по ссылкам между элементами в цепочке, в поисках последнего элемента, от которого и ставится ссылка на вновь добавленный элемент. 
	- Если в списке был найден элемент с таким же ключом, то он заменяется.
<!--SR:!2023-11-03,10,430-->




Главы:
- [[Реализация HashMap]]
- [[Начальное количество корзин в HashMap]]
- [[Максимальное число значений hashCode()]]
- [[Конструктор HashMap()]]



Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] [Структуры данных в картинках. HashMap](https://habr.com/ru/post/128017/)
- [ ] [Хеш-таблица](https://ru.wikipedia.org/wiki/%D0%A5%D0%B5%D1%88-%D1%82%D0%B0%D0%B1%D0%BB%D0%B8%D1%86%D0%B0#.D0.9C.D0.B5.D1.82.D0.BE.D0.B4_.D1.86.D0.B5.D0.BF.D0.BE.D1.87.D0.B5.D0.BA)
