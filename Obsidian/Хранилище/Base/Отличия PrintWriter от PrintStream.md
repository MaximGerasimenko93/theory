#flashcards
Data: 2023-07-31 11:55
Title: [[Отличия PrintWriter от PrintStream]]
Alias:
Header:




Body:


Перечислите отличия между классами `PrintWriter` и `PrintStream`?
!---
Ответ:
	- В классе `PrintWriter` применен усовершенствованный способ работы с символами Unicode и другой механизм буферизации вывода
	- в классе `PrintStream` буфер вывода сбрасывался всякий раз, когда вызывался метод `print()` или `println()`, а при использовании класса `PrintWriter` существует возможность отказаться от автоматического сброса буферов, выполняя его явным образом при помощи метода `flush()`
	- Кроме того, методы класса `PrintWriter` никогда не создают исключений. Для проверки ошибок необходимо явно вызвать метод `checkError()`
<!--SR:!2023-10-31,10,170-->




Главы:
- [[Отличия PrintWriter от PrintStream]]


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
