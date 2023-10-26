#flashcards
Data: 2023-07-20 13:50
Title: [[Основные классы и интерфейсы JDBC]]
Alias:
Header:




Body:



#JDBC 
Перечислите основные классы и интерфейсы JDBC.
!---
Ответ:
	- `java.sql.DriverManager` - позволяет загрузить и зарегистрировать необходимый JDBC-драйвер, а затем получить соединение с базой данных.
	- `javax.sql.DataSource` - решает те же задачи, что и _DriverManager_, но более удобным и универсальным образом. Существуют также `javax.sql.ConnectionPoolDataSource` и `javax.sq1.XADataSource` задача которых - обеспечение поддержки пула соединений. 
	- `java.sql.Connection` - обеспечивает формирование запросов к источнику данных и управление транзакциями. Также предусмотрены интерфейсы `javax.sql.PooledConnection` и `javax.sql.XAConnection`. 
	- `java.sql.Statement` , `java.sql.PreparedStatement` и `java.sql.CallableStatement` - эти интерфейсы позволяют отправить запрос к источнику данных.
	- `java.sql.ResultSet` - объявляет методы, которые позволяют перемещаться по набору данных и считывать значения отдельных полей в текущей записи.
	- `java.sql.ResultSetMetaData` - позволяет получить информацию о структуре набора данных.
	- `java.sql.DatabaseMetaData` - позволяет получить информацию о структуре источника данных.
<!--SR:!2023-11-04,10,250-->




Главы:
-


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
