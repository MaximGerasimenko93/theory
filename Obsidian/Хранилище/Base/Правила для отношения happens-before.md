#flashcards
Data: 2023-08-01 12:38
Title: [[Правила для отношения happens-before]]
Alias:
Header:




Body:



Назовите правила для отношения happens-before
!---
Ответ:
	- В рамках одного потока любая операция happens-before любой операцией, следующей за ней в исходном коде;
	- Освобождение монитора (unlock) happens-before захват того же монитора (lock);
	- Выход из `synchronized` блока/метода happens-before вход в `synchronized` блок/метод на том же мониторе;
	- Запись `volatile` поля happens-before чтение того же самого `volatile` поля;
	- Завершение метода `run()` экземпляра класса `Thread` happens-before выход из метода `join()` или возвращение `false` методом `isAlive()` экземпляром того же потока;
	- Вызов метода `start()` экземпляра класса `Thread` happens-before начало метода `run()` экземпляра того же потока;
	- Завершение конструктора happens-before начало метода `finalize()` этого класса;
	- Вызов метода `interrupt()` на потоке happens-before обнаружению потоком факта, что данный метод был вызван либо путем выбрасывания исключения `InterruptedException`, либо с помощью методов `isInterrupted()` или `interrupted()`.
	- Связь happens-before транзитивна, т.е. если _X_ happens-before _Y_, а _Y_ happens-before _Z_, то _X_ happens-before _Z_.
	- Освобождение/захват монитора и запись/чтение в `volatile` переменную связаны отношением happens-before, только если операции проводятся над одним и тем же экземпляром объекта.
	- В отношении happens-before участвуют только два потока, о поведении остальных потоков ничего сказать нельзя, пока в каждом из них не наступит отношение happens-before с другим потоком.
<!--SR:!2023-10-27,1,130-->




Главы:
-


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
