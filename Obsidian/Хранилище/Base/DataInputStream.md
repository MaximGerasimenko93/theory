#flashcards
Data: 2023-07-31 11:47
Title: [[DataInputStream]]
Alias:
Header:

Что такое [[DataInputStream]]?::[[DataInputStream]] – представляет поток ввода и предназначен для записи данных примитивных типов, таких, как `int`, `double` и т.д.
<!--SR:!2023-11-04,10,590-->


Body:



Какие методы имеет класс `DataInputStream`?
!---
Ответ:
	- `boolean readBoolean()`: считывает из потока булевое однобайтовое значение
	- `byte readByte()`: считывает из потока 1 байт
	- `char readChar()`: считывает из потока значение `char`
	- `double readDouble()`: считывает из потока 8-байтовое значение `double`
	- `float readFloat()`: считывает из потока 4-байтовое значение `float`
	- `int readInt()`: считывает из потока целочисленное значение `int`
	- `long readLong()`: считывает из потока значение `long`
	- `short readShort()`: считывает значение `short`
	- `String readUTF()`: считывает из потока строку в кодировке UTF-8
<!--SR:!2023-11-03,10,321-->




Главы:
-


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
