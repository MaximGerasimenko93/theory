#flashcards 
Data: 2022-05-03 08:59
Title: [[Liskov substitution principle]]
Tags: #LiskovSubstitutionPrinciple #LSP #ПринципПодстановкиЛисков # # # # #
Alias:
	- LSP
	- Liskov substitution principle
	- Принцип подстановки Лисков
Header:
	- Что такое [[Liskov substitution principle]]?::[[Liskov substitution principle]] - это Принцип подстановки Лисков – Объекты в программе должны быть заменяемыми на экземпляры их подтипов без изменения правильности выполнения программы.
<!--SR:!2023-11-03,10,290-->
	- 
Body:

Пусть q(x) является свойством верным
относительно объектов x некоторого
типа T. Тогда q(y) также должно быть
верным для объектов y типа S, где S
является подтипом типа T.

Функции, которые используют базовый тип, должны иметь возможность использовать подтипы базового типа, не зная об этом


Заачем нужно использовать [[Liskov substitution principle]]?
!---
Ответ:
	- Принцип подстановки Лисков позволяет понять правильно ли была сформирована абстракция. Она должна быть сделана так, чтобы мы не могли различать наследников между собой
	- Функции, которые используют ссылки на базовые классы, должны иметь возможность использовать объекты производных классов, не зная об этом
	- Мы в программе не должны обнаружить объекты производных классов. Мы не должны иметь возможности определить конкретный тип этого объекта. Какой производный класс он использует.
<!--SR:!2023-11-03,10,330-->


Главы:
	- 

Sources:
1) [The Liskov Substitution Principle](https://web.archive.org/web/20150905081111/http://www.objectmentor.com/resources/articles/lsp.pdf)
2) []()
