# Order management system for a restaurant

Console Application written in Java SE 17 that takes multiple orders for same/different clients of a restaurant. Application has 2 profiles: one for the **client** where orders are placed and one for the **administrator**, where data reports can be seen about the purchases through the day, orders made, ingredients of a product, etc

> Here is a live demo of a user entering an order _(1 pepperoni pizza, 1 burger, 2 cola, 1 heineken and 1 apple pie for dessert)_

https://github.com/CosminManu/restaurant-management-system/assets/75031246/3d64c550-11be-4c82-a0fd-28eba815505a

## Table of contents
* [General Info](#general-information)
* [Tech Stack](#tech-stack)
* [Features for Client](#features-for-client)
* [Features for Administrator](#features-for-admin)
* [Screenshots](#screenshots)
* [Setup](#setup)
* [How to run it](#run-app)
* [Project Status](#project-status)
* [Further Improvements](#further-improvements)
* [Contact](#contact)

## General Information
- "Order management system" is a console application written in Java Standard Edition 17, a Long Term Support version of the language offered by _Oracle_. 
- Application consists of **2 profiles**: **client** and **administrator**.

All customers of the restaurant can place an order using the 'client' application interface. Also an admin of the restaurant can view reports about what orders have been made through the day, what ingredients are needed for a product, how to add a product in the menu and so on.
- **_Important:_ Source code of the application is _on another private repo_.**

## Tech Stack
- Java SE 17

## Features for Client
- Choose one/more type of menu/s (food menu, beverage menu, dessert menu etc)
- One customer can make an order or multiple orders
- Receive a form of receipt

## Features for Admin
- Login Authentification with 3 attempts
- Show price for each order
- Show price for each customer that has ordered
- Show total sales of the restaurant
- Choose a product from the menu and show its ingredients
- Option to add a product in the menu


## Setup
There are no extra dependencies or external libraries that need to be installed apart from the JDK JJava Development Kit that contains the virtual machine to run the application.
For the setup of the app user has first to:
- Ensure that the system has the file **_menu.txt_** in models.Restaurant.readMenuData() is set accordingly to the specifications (firstly when the system starts admin must add the path to the restaurant's menu txt file
- _Obs_ if the path to the menu is not set correctly the system will print an error message!
- Ensure the absolute paths for order.txt are set by the support team.

https://github.com/CosminManu/restaurant-management-system/assets/75031246/5f7a0739-8be2-42db-8420-eec528536eb1


## Run app
User can run the system from command line, navigating to _out/production/restaurant-ppoo_, using following command

`java ro.ase.ebusiness.Main`

https://github.com/CosminManu/restaurant-management-system/assets/75031246/d1ca9da2-6bfe-40cd-a05b-09e01275dadc



## Project Status
_complete_

## Further Improvements
TBD

Room for improvement: TBD

## Contact
Created by me [@CosminManu](https://www.linkedin.com/in/cosminmanu/) - feel free to contact me!
