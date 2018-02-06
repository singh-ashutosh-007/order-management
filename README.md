#Order Management System (OMS)

## About this application

This application is created by ASHUTOSH SINGH RAWAT. This is a simple order management system. 
<br>
##### Framework: Ruby on Rails 5.1.5
##### Language : Ruby 2.6.0


## Install
- Install all gems by typing this:
```
bundle install
```
- To change Database go to "config/database.yml" and then change database. Default Database is Mysql.

- Migrate Database by typing this:
```
rake db:migrate
```
- Login:
	Username: singh.ashutoshrawat@gmail.com<br>
	Password: Abc.1234

- To Add new user go to "config/route.rb" change this line to 
```
devise_for :users, path_names: { 
		sign_up: '' #Stop Sign Up
	}
```
to
```
devise_for :users
```
and then go to /sign_up page by web browser. Fill the form. 
- Again change that line to hide sign_up page.

## Features
- Add order
- Export Order (pdf, excel, csv and etc)
- Edit / Delete Order
- Search Order
- Print Invoice
- Easy interface
- Mobile view

## Uses
* Restaurant Order
* Facebook Commerce
* etc...

### Contact me 
Facebook: facebook.com/ <br>
Email: singh.ashutoshrawat@gmail.com   