# Basics-of-SQL

# 
## Login Mysql
#### mysql -u root

#
## to see available databases
#### show databases;

#
## to create a database
#### create database example;

#
## to use the database
#### use example;

#
## to see the table in the database
#### show tables;

#
## to create a table in the database
#### create table users(name varchar(100));
#### #() is to determine what data is to be stored in users
#### #name is the name of the column where the data will be stored
#### #varchar is a type of data in sql which means variable character, this type of data is used because the data to be stored is a name
#### #(100) this number will determine how many characters can be placed in the name


#
## to enter the value into the name column
#### insert into users value("tapau");
#### #The insert command is used to insert a value
#### #into to determine where the table is to be entered, here I will put it on users because I want to fill in the value into the name column
#### #value("tapau") is to determine what name to include in value

#
## to see the contents of the table
#### select * from users;
#### #command select is used to select
#### #* This query means everything from what is selected
#### #from users means from table users

#
## to delete the database
#### drop database example;
#### #command drop refers to delete
#### #database example; This one means to delete the database and the name of the database to be deleted is example

#
## to delete the tables
#### drop table users;
#### #command drop refers to delete
#### #table users; This one means to delete the table and the name of the table to be deleted is users

#
## to see what user we run as
#### select user();

#
## to see what version is used on databases
#### select version();

#
## to see what database is being used by me
#### select database();







































