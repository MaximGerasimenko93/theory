#flashcards #Hibernate 
Data: 2023-09-13 10:54
Title: [[Hibernate Criteria API]]
Alias:
Header:

Что такое [[Hibernate Criteria API]]?::[[Hibernate Criteria API]] – это более объектно-ориентированный API для запросов, которые получают результат из базы данных.
<!--SR:!2023-10-27,3,150-->



Body:



#Hibernate 
Для чего нельзя использовать Hibernate Criteria API?
!---
Ответ:
	- Hibernate Criteria API нельзя использовать для операций `update`, `delete` или других DDL манипуляций.
<!--SR:!2023-10-29,10,210-->


#Hibernate 
Для чего используют Hibernate Criteria API?
!---
Ответ:
	- Критерии используются только для выборки из базы данных в более объектно-ориентированном стиле и для динамических запросов.
<!--SR:!2023-10-27,1,130-->



#Hibernate 
Перечислите области применения Hibernate Criteria API.
!---
Ответ:
	- Criteria API поддерживает проекцию, которую мы можем использовать для агрегатных функций вроде `sum()`, `min()`, `max()` и т.д.
	- Criteria API может использовать `ProjectionList` для извлечения данных только из выбранных колонок
	- Criteria API может быть использована для join-запросов с помощью соединения нескольких таблиц, используя методы `createAlias()`, `setFetchMode()` и `setProjection()`
	- Criteria API поддерживает выборку результатов согласно условиям (ограничениям). Для этого используется метод `add()` с помощью которого добавляются ограничения (Restrictions)
	- Criteria API позволяет добавлять порядок (сортировку) к результату с помощью метода `addOrder()`
<!--SR:!2023-10-27,1,130-->





Главы:
-


Sources:
- [ ] [Hibernate вопросы-ответы](https://docs.google.com/document/d/104EUUT-gv7xSalJlJu0DInzlyCVFjC5Sz2gcDoVtfyE/edit)
- [ ] []()
- [ ] []()
