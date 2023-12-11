# Order management system for a restaurant
> brief description
> live demo

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


## Screenshots
Folder with img/

## Setup
There are no extra dependencies or external libraries that need to be installed apart from the JDK JJava Development Kit that contains the virtual machine to run the application.
For the setup of the app user has first to:
- Ensure he/she has the file **_menu.txt_** set accordingly to the specifications.
- Ensure the absolute paths for order.txt are set by the support team.

## Run app
User can run the system from command line, navigating to _out/production/restaurant-ppoo_, using followinf command

`java ro.ase.ebusiness.Main`

## Project Status
_complete_

## Further Improvements
TBD

Room for improvement: TBD

## Contact
Created by me [@CosminManu](https://www.linkedin.com/in/cosminmanu/) - feel free to contact me!
