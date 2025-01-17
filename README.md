create database shop24;
use shop24;
create table user(Name varchar(30) , Email varchar(30) , MobileNumber long , SecurityQuestion varchar(100) , Answer varchar(100) , Password varchar(50) , Address varchar(100) , City varchar(40) , State varchar(40) , Country varchar(50));
select*from user;
create table Product(Id int, Pname varchar(20) , Category varchar(30), Price varchar(30) , Active varchar(20));
select*from product;
create table cart(email varchar(40) , product_id varchar(20) , quantity int , product_price int ,product_total int);
