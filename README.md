# Basic-MySql
Today I learning about MySql for database and data managment ,etc.
create database ads ;
drop database ads;
use  ads;
create table asd (
  Sno int primary key,
  name varchar(50),
  rollno int not null unique,
  result varchar(10) not null 
  );
select * from asd;
drop table asd;
insert into asd 
  (Sno ,name ,rollno ,result )
   value 
   (1 ,' Gulshan ' ,221901221 ,'76%'),
   (2 ,' Sahil ' ,221901222 ,'93%'),
   (3 ,' Anup ' ,221901223 ,'67%'),
   (4 ,' Deepak ' ,221901224 ,'97%'),
   (5 ,' Jyoti ' ,221901225 ,'53%'),
   (6 ,' Payal ' ,221901227 ,'86%');