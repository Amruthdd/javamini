### Copy and Paste the following MYSQL commands to make a dummy database for this Project :


create database onlinebookstore;

use onlinebookstore;

create table books(barcode varchar(100) primary key, name varchar(100), author varchar(100), price int, quantity int);

create table users(username varchar(100) primary key,password varchar(100), firstname varchar(100),lastname varchar(100),address text, phone varchar(100),mailid varchar(100),usertype int);

insert into books values('101','Five Feet Apart','Rachael Lippincott ',500,5);

insert into books values('102','Java Simplified','Scott Mayers',150,13);

insert into books values('103','Database Knowledge','Charles Pettzoid',124,360);

insert into books values('104','Let us c++','Steve Macclen',90,111);

insert into books values('105','You can Win','Shiv Khera',5000,15);

insert into users values('User','Password','First','User','My Home','42502216225','User@gmail.com',2);

insert into users values('Admin','Admin','Mr.','Amruth','Calicut','9584552224521','admin@gmail.com',1);

insert into users values('amruth','amruth','Amruth','DD','Kerala','1236547089','amruth@gmail.com',2);

commit;
