#flashcards
Data: 2023-07-31 11:49
Title: [[OutputStream]]
Alias:
Header:

Что такое [[OutputStream]]?::[[OutputStream]] – это абстрактный класс, определяющий потоковый байтовый вывод
<!--SR:!2023-11-03,10,750-->


Body:

Какие есть подклассы класса `OutputStream` и для чего они предназначены?
!---
Ответ:
	- `OutputStream` - это абстрактный класс, определяющий потоковый байтовый вывод;
	- `BufferedOutputStream` - буферизированный выходной поток;
	- `ByteArrayOutputStream` - все данные, посылаемые в этот поток, размещаются в предварительно созданном буфере;
	- `DataOutputStream` - выходной поток байт, включающий методы для записи стандартных типов данных Java;
	- `FileOutputStream` - запись данных в файл на физическом носителе;
	- `FilterOutputStream` - абстрактный класс, предоставляющий интерфейс для классов-надстроек, которые добавляют к существующим потокам полезные свойства;
	- `PrintStream` - выходной поток, включающий методы `print()` и `println()`;
	- `ObjectOutputStream` - выходной поток для записи объектов;
	- `PipedOutputStream` реализует понятие выходного канала.
<!--SR:!2023-11-03,10,421-->




Главы:
- [[Отличия PrintWriter от PrintStream]]
- [[OutputStreamWriter]]


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
