### install and start MySql
1. install bitnami wamp
2. open windows cmd
3. change directory to the folder where bitnami is installed and change directory to "mysql/bin" folder
4. type command "mysql -uroot -p"

### Data
| id   | title         | description     | created      | author | profile    |
| :--: | :-----------: | :-------------: | :----------: | :----: | :--------: |
| 1    | MySQL | MySQL is ...    | 2018-01-10   | egoing | develpoer  |
| 2    | ORACLE | ORACLE is ...   | 2018-01-15   | egoing | develpoer  |
| 3    | SQL Server | SQL Server is ... | 2018-01-18   | duru | database administrator  |
| 4    | PostgreSQL | Postgre SQL is ... | 2018-01-20   | teaho | data scientist, developer  |
| 5    | MongoDB | MongoDB is ... | 2018-01-30   | egoing | developer  |


### MySql commands
**search cheat sheet! for example: "create table in mysql cheat sheet"**
<dl>
  <dt>mysql</dt>
  <dd>create database tablename;</dd>
  <dd>show databases;</dd>
  <dd>drop database helloworld;</dd>
	<dd>create database topic;</dd>
	<dd>use topic;</dd>
	<dd>create table topic(id INT(11) NOT NULL AUTO_INCREMENT, title VARCHAR(100) NOT NULL, description TEXT NULL, created DATETIME NOT NULL,     author VARCHAR(15) NULL, profile VARCHAR(200) NULL, PRIMARY KEY(id));</dd>
	<dd>show tables;</dd>
	<dd>DROP tables topic;</dd>
	<dd>DESC topic; (*show table data)</dd>
	<dd>insert into topic (title, description, created, author, profile) values('MySQL', 'MySQL is ...', now(), 'egoing', 'developer');</dd>
	<dd>SELECT * FROM topic;</dd>
	<dd>SELECT id, title, created, author from topic where author='egoing' order by id desc LIMIT 2;</dd>
	<dd>UPDATE topic SET description='Oracle is' , title='Oracle' where id=2;</dd>
	<dd>DELETE FROM topic where id=5;</dd>
 </dl>
