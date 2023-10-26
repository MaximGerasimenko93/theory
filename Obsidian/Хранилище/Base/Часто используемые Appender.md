#flashcards
Data: 2023-07-21 13:24
Title: [[Часто используемые Appender]]
Alias:
Header:


Body:



#Журналирование 
Перечислите наиболее часто используемые Appender-ы.
!---
Ответ:
	- `org.apache.log4j.ConsoleAppender` - вывод в консоль
	- `org.apache.log4j.FileAppender` - добавление в файл
	- `org.apache.log4j.DailyRollingFileAppender` - добавление в файл с обновлением файла через заданный промежуток времени
	- `org.apache.log4j.RollingFileAppender` - добавление в файл с обновлением файла по достижению определенного размера
	- `org.apache.log4j.varia.ExternallyRolledFileAppender` - расширение _RollingFileAppender_ обновляющее файл по команде принятой с заданного порта
	- `org.apache.log4j.net.SMTPAppender` - сообщение по SMTP
	- `org.apache.log4j.AsyncAppender` - позволяет, используя отдельный поток, организовать асинхронную работу, когда сообщения фиксируются лишь при достижении определенного уровня заполненности промежуточного буфера.
	- `org.apache.log4j.nt.NTEventLogAppender` - добавление в NT Event Log
	- `org.apache.log4j.net.SyslogAppender` - добавление в Syslog
	- `org.apache.log4j.jdbc.JDBCAppender` - запись в хранилище JDBC
	- `org.apache.log4j.lf5.LF5Appender` - сообщение передаётся в специальный GUI интерфейс LogFactor5
	- `org.apache.log4j.net.SocketAppender` - трансляция сообщения по указанному адресу и порту
	- `org.apache.log4j.net.SocketHubAppender` - рассылка сообщения сразу нескольким удалённым серверам, соединённым по заданному порту
	- `org.apache.log4j.net.TelnetAppender` - отсылка сообщения по протоколу Telenet
	- `org.apache.log4j.net.JMSAppender` - добавление сообщения в JMS
<!--SR:!2023-11-03,10,270-->




Главы:
-


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
