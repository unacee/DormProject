# DormProject
database:
spring.datasource.username=root
spring.datasource.password=123456
spring.datasource.url=jdbc:mysql://localhost:3306/DormDB?serverTimezone=GMT%2B8

table：
User:
create table User (uid int primary key auto_increment,name varchar(255),dormId int);
create table Dorm(dormId int primary key auto_increment,location varchar(255),vacant int);

url:localhost:8080/home
