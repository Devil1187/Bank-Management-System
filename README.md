---------------------------------------------------
Database Queries for BANK MANAGEMENT SYSTEM Project
---------------------------------------------------

create table signup(formno varchar(20), name varchar(40), father_name varchar(40), dob varchar(20),gender varchar(20), email varchar(50), marital_ststus varchar(20), address varchar(50), city varchar(25), pincode varchar(20), state varchar(25));
select* from signup; 
drop table signup;
create table signup2(formno varchar(20), religion varchar(20), category varchar(20), income varchar(20), education varchar(20), occuption varchar(30), pan varchar(20), aadhar varchar(40), siniorcitizen varchar(25), existingaccount varchar(20));

create table login(formno varchar(20), cardnumber varchar(25), pin varchar(10));

show tables;

select* from signup2;

create table signup3(formno varchar(20), accountType varchar(40), cardnumber varchar(25), pin varchar(10), facility varchar(100)); 

select* from signup3;

create table bank(pin varchar(10), date varchar(50), type varchar(20), amount varchar(20));
drop table bank;
select* from bank;

select* from login;
