#flashcards
Data: 2023-02-04 17:08
Title: [[Методы класса Object]]
Alias:
Header:




Body:


Назовите методы класса `Object`.
!---
Ответ:
	- `public boolean equals(Object obj)` – служит для сравнения объектов по значению;
	- `int hashCode()` – возвращает hash код для объекта;
	- `String toString()` – возвращает строковое представление объекта;
	- `Class getClass()` – возвращает класс объекта во время выполнения;
	- `protected Object clone()` – создает и возвращает копию объекта;
	- `void notify()` – возобновляет поток, ожидающий монитор;
	- `void notifyAll()` – возобновляет все потоки, ожидающие монитор;
	- `void wait()` – остановка вызвавшего метод потока до момента пока другой поток не вызовет метод `notify()` или `notifyAll()` для этого объекта;
	- `void wait(long timeout)` – остановка вызвавшего метод потока на определённое время или пока другой поток не вызовет метод `notify()` или `notifyAll()` для этого объекта;
	- `void wait(long timeout, int nanos)` – остановка вызвавшего метод потока на определённое время или пока другой поток не вызовет метод `notify()` или `notifyAll()` для этого объекта;
	- `protected void finalize()` – может вызываться сборщиком мусора в момент удаления объекта при сборке мусора.
<!--SR:!2023-11-03,10,610-->





Главы:
- [[Метод clone() в классе Object]]
- [[Метод equals()]]
- [[hashCode() и equals() в Object]]
- [[Метод wait()]]
- [[Метод notify()]]
- [[Метод notifyAll()]]


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
