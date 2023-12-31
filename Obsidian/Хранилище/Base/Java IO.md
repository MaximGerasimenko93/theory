#flashcards
Data: 2023-07-31 11:06
Title: [[Java IO]]
Alias:
Header:

Что такое [[Java IO]]?::[[Java IO]] – это это Java API, которое облегчает разработчикам работу с потоками. Java IO (input-output) является потокоориентированным.
<!--SR:!2023-11-03,10,750-->


Body:


Что подразумевает потокоориентированный ввод/вывод?
!---
Ответ:
	- Потокоориентированный ввод/вывод подразумевает чтение/запись из потока/в поток одного или нескольких байт в единицу времени поочередно. Данная информация нигде не кэшируются. Таким образом, невозможно произвольно двигаться по потоку данных вперед или назад.
<!--SR:!2023-11-03,10,230-->


Назовите недостатки Java IO.
!---
Ответ:
	- Блокирующий доступ для ввода/вывода данных. Проблема состоит в том, что когда разработчик пытается прочитать файл или записать что-то в него, используя Java IO, он блокирует файл и доступ к нему до момента окончания выполнения своей задачи.
	- Отсутствует поддержка виртуальных файловых систем.
	- Нет поддержки ссылок.
	- Очень большое количество checked исключений.
<!--SR:!2023-11-03,10,381-->


В чем суть блокирующего доступа в Java IO?
!---
Ответ:
	- Это значит, что когда в потоке выполнения вызывается `read()` или `write()` метод любого класса из пакета `java.io.*`, происходит блокировка до тех пор, пока данные не будут считаны или записаны.
<!--SR:!2023-11-03,10,381-->





Главы:
- [[Java NIO]]
- [[Каналы]]
- [[Основные классы IO]]
- [[Reader]]
- [[Writer]]
- [[Буфферные классы]]
- [[File]]
- [[Чтение и запись потоков в компрессированном формате]]
- [[Перенаправление потоков стандартного ввода-вывода]]

Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
