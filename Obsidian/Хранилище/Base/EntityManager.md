#flashcards #Hibernate 
Data: 2023-08-28 13:41
Title: [[EntityManager]]
Alias:
Header:

Что такое [[EntityManager]]?::[[EntityManager]] – это интерфейс, который описывает API для всех основных операций над `Entity`, получение данных и других сущностей JPA. По сути главный API для работы с JPA.
<!--SR:!2023-11-05,10,310-->



Body:


#Hibernate 
Назовите основные операции `EntityManager` над `Entity`.
!---
Ответ:
	- Для операций над `Entity`: 
	- `persist` – добавление `Entity` под управление JPA
	- `merge` – обновление
	- `remove` – удаления
	- `refresh` – обновление данных
	- `detach` – удаление из управление JPA
	- `lock` – блокирование `Entity` от изменений в других `thread`
	- 
	- Получение данных: 
	- `find` – поиск и получение Entity
	- `createQuery`
	- `createNamedQuery`
	- `createNativeQuery`
	- `contains`
	- `createNamedStoredProcedureQuery`
	- `createStoredProcedureQuery`
	- 
	- Получение других сущностей JPA: 
	- `getTransaction`
	- `getEntityManagerFactory`
	- `getCriteriaBuilder`
	- `getMetamodel`
	- `getDelegate`
	- 
	- Работа с `EntityGraph`: 
	- `createEntityGraph`
	- `getEntityGraph`
	- 
	- Общие операции над `EntityManager` или всеми `Entities`: 
	- `close`
	- `isOpen`
	- `getProperties`
	- `setProperty`
	- `clear`
<!--SR:!2023-10-27,1,170-->




Главы:
- [[Entity]]
- [[Каскадирование]]
- [[orphanRemoval]]
- [[FetchType]]

Sources:
- [ ] [Hibernate вопросы-ответы](https://docs.google.com/document/d/104EUUT-gv7xSalJlJu0DInzlyCVFjC5Sz2gcDoVtfyE/edit)
- [ ] []()
- [ ] []()
