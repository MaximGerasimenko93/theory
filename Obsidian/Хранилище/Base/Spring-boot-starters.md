#flashcards #Spring 
Data: 2023-08-07 14:12
Title: [[Spring-boot-starters]]
Alias:
Header:

Что такое [[Spring-boot-starters]]?::[[Spring-boot-starters]] – это обычные зависимости (jars), которые добавляют нужный функционал в проект и следуют определенному шаблону именования spring-boot-starter-* ; 
<!--SR:!2023-11-03,10,350-->
Это набор удобных дескрипторов зависимостей, которые можно включить в свое приложение.



Body:


#Spring
Для чего используют spring-boot-starters?
!---
Ответ:
	- Это позволит получить универсальное решение для всех, связанных со Spring технологий, избавляя программиста от лишнего поиска примеров кода и загрузки из них требуемых дескрипторов зависимостей. 
	- Например, если вы хотите начать использовать Spring Data JPA для доступа к базе данных, просто включите в свой проект зависимость spring-boot-starter-data-jpa и все будет готово (вам не придется искать совместимые драйверы баз данных и библиотеки Hibernate)
	- Например, если вы добавите Spring-boot-starter-web, Spring Boot автоматически сконфигурирует такие зарегистрированные бины, как DispatcherServlet, ResourceHandlers, MessageSource.
	- Если вы используете spring-boot-starter-jdbc, Spring Boot автоматически регистрирует бины DataSource, EntityManagerFactory, TransactionManager и считывает информацию для подключения к базе данных из файла application.properties
<!--SR:!2023-11-03,10,350-->


#Spring
К какой группе относят spring-boot-starters?
!---
Ответ:
	- `org.springframework.boot`
<!--SR:!2023-11-03,10,390-->


#Spring
Назовите примеры spring-boot-starters?
!---
Ответ:
	- `org.springframework.boot:spring-boot-starter-data-cassandra
	- `org.springframework.boot:spring-boot-starter-data-jpa
	- `org.springframework.boot:spring-boot-starter-data-jdbc
	- `org.springframework.boot:spring-boot-starter-test
	- `org.springframework.boot:spring-boot-starter-thymeleaf
	- `org.springframework.boot:spring-boot-starter-security
<!--SR:!2023-11-03,10,370-->


Главы:
-


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
