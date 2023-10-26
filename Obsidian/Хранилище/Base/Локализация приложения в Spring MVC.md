#flashcards
Data: 2023-08-15 11:52
Title: [[Локализация приложения в Spring MVC]]
Alias:
Header:




Body:



#Spring 
Как произвести локализацию приложения в Spring MVC?
!---
Ответ:
	- Создать файл `resource bundle`, в котором будут заданы различные варианты локализированной информации.
	- Определить `messageSource` в конфигурации Spring используя классы `ResourceBundleMessageSource` или `ResourceBundleMessageSource`
	- Определить `localceResolver` класса `CookieLocaleResolver` для включения возможности переключения локали.
	- С помощью элемента `spring:message DispatcherServlet` будет определять в каком месте необходимо подставлять локализированное сообщение в ответе.
<!--SR:!2023-10-27,1,130-->




Главы:
-


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
