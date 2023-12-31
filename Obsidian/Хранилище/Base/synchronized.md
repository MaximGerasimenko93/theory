#flashcards
Data: 2023-08-01 12:56
Title: [[synchronized]]
Alias:
Header:

Что такое [[synchronized]]?::[[synchronized]] – это ключевое слово позволяет добиваться синхронизации в помеченных им методах или блоках кода.
<!--SR:!2023-10-27,1,250-->



Body:


Как работает `synchronized`?
!---
Ответ:
	- При входе в `synchronized` метод или блок поток обновляет содержимое локальной памяти, а при выходе из `synchronized` метода или блока поток записывает изменения, сделанные в локальной памяти, в главную.
	- Такое поведение `synchronized` методов и блоков следует из правил для отношения «происходит раньше»: так как все операции с памятью происходят раньше освобождения монитора и освобождение монитора происходит раньше захвата монитора, то все операции с памятью, которые были сделаны потоком до выхода из `synchronized` блока должны быть видны любому потоку, который входит в `synchronized` блок для того же самого монитора.
	- Очень важно, что это правило работает только в том случае, если потоки синхронизируются, используя один и тот же монитор!
<!--SR:!2023-10-27,1,130-->


Можно ли создавать новые экземпляры класса, пока выполняется `static synchronized` метод?
!---
Ответ:
	- Да, можно создавать новые экземпляры класса, так как статические поля не принадлежат к экземплярам класса.
<!--SR:!2023-11-01,10,390-->




Главы:
- [[Монитор (mutex)]]
- [[Синхронизация]]
- [[Вызов static synchronized метода]]
- [[Различия между synchronized и ReentrantLock]]


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
