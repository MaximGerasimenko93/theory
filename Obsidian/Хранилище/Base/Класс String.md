#flashcards
Data: 2023-02-04 12:14
Title: [[Класс String]]
Alias:
Header:

Что такое [[Класс String]]?::[[Класс String]] – это класс, который работает со строками.
<!--SR:!2023-11-03,10,690-->




Body:




Назовите особенности класса String.
!---
Ответ:
	- Это неизменяемый (immutable) и финализированный тип данных.
	- Все объекты класса `String` JVM хранит в пуле строк.
	- Объект класса `String` можно получить, используя двойные кавычки
	- Можно использовать оператор `+` для конкатенации строк.
	- Начиная с Java 7 строки можно использовать в конструкции `switch`.
	- Класс реализует интерфейсы `Serializable` и `CharSequence`. Поскольку он входит в пакет `java.lang`, его не нужно импортировать.
	- Благодаря своей неизменности, объекты класса `String` являются потокобезопасными и могут быть использованы в многопоточной среде.
	- Каждый объект в Java может быть преобразован в строку через метод `toString()`, унаследованный всеми Java-классами от класса `Object`.
<!--SR:!2023-11-03,10,630-->




Главы:
- [[Пул строк]]
- [[Преимущества неизменяемости строк]]
- [[String в HashMap]]
- [[Метод intern() в классе String]]
- [[Оператор switch и строки]]
- [[Отличия String, StringBuffer и StringBuilder]]


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] [Класс String в Java](https://javarush.com/groups/posts/2347-klass-string-v-java)
- [ ] []()
