#flashcards
Data: 2023-08-01 12:23
Title: [[Проблема сериализации Singleton]]
Alias:
Header:




Body:


В чем проблема сериализации Singleton?
!---
Ответ:
	- Проблема в том что после десериализации мы получим другой объект. Таким образом, сериализация дает возможность создать Singleton еще раз, что недопустимо.
<!--SR:!2023-11-03,10,390-->


Как избежать проблем при сериализации Singleton?
!---
Ответ:
	- явный запрет сериализации.
	- определение метода с сигнатурой `(default/public/private/protected/) Object readResolve() throws ObjectStreamException`, назначением которого станет возврат замещающего объекта вместо объекта, на котором он вызван.
<!--SR:!2023-11-03,10,290-->



Главы:
-


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
