#flashcards
Data: 2023-07-21 13:32
Title: [[Способы конфигурирования в log4j]]
Alias:
Header:



Body:



#Журналирование 
Перечислите способы конфигурирования в log4j?
!---
Ответ:
	- Создать конфигурацию программно, т.е. получить logger, определить уровень журналирования, прикрепить appender и задать способ форматирования
	- Указать файл или URL как аргумент при запуске java-машины `-Dlog4j.configuration=путь/к/файлу/конфигурации`, а затем прочитать его в программе при помощи `PropertyConfigurator.configure(...)`/ `DOMConfigurator.configure(...)` для формата `.properties` или `XML` соответственно
	- Загрузить конфигурацию из файла в формате `XML` или `.properties`: log4j ищет файл конфигурации в classpath. Сначала ищется файл `log4j.xml` и, если таковой не найден, - файл `log4j.properties`
<!--SR:!2023-10-27,1,130-->




Главы:
-


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
