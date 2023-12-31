#flashcards
Data: 2023-08-01 13:09
Title: [[final в JMM]]
Alias:
Header:

Какие особенности слова [[final в JMM]]?::[[final в JMM]] – имеет дополнительную семантику ключевого слова `final`, имеющую отношение к видимости: после того как объект был корректно создан, любой поток может видеть значения его `final` полей без дополнительной синхронизации.
<!--SR:!2023-11-03,10,390-->



Body:


Что означает "Объект корректно создан"?
!---
Ответ:
	- "Корректно создан" означает, что ссылка на создающийся объект не должна использоваться до тех пор, пока не завершился конструктор объекта.
	- Наличие такой семантики для ключевого слова `final` позволяет создание неизменяемых (immutable) объектов, содержащих только `final` поля, такие объекты могут свободно передаваться между потоками без обеспечения синхронизации при передаче.
<!--SR:!2023-11-03,10,230-->



Какая проблема есть с `final` в JMM и Reflection API?
!---
Ответ:
	- Есть одна проблема, связанная с `final` полями: реализация разрешает менять значения таких полей после создания объекта (это может быть сделано, например, с использованием механизма reflection).
	- Если значение `final` поля – константа, чьё значение известно на момент компиляции, изменения такого поля могут не иметь эффекта, так-как обращения к этой переменной могли быть заменены компилятором на константу.
	- Также спецификация разрешает другие оптимизации, связанные с `final` полями, например, операции чтения `final` переменной могут быть переупорядочены с операциями, которые потенциально могут изменить такую переменную.
	- Так что рекомендуется изменять `final` поля объекта только внутри конструктора, в противном случае поведение не специфицировано.
<!--SR:!2023-11-03,10,310-->



Главы:
-


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
