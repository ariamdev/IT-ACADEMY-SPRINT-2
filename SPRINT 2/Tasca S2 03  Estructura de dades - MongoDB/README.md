[![ES](https://img.shields.io/badge/ES-red.svg?logo=googletranslate&logoColor=white)](https://github.com/ariamdev/IT-ACADEMY-SPRINT-2/blob/main/SPRINT%202/Tasca%20S2%2003%20%20Estructura%20de%20dades%20-%20MongoDB/README.es.md)
[![CAT](https://img.shields.io/badge/CAT-yellow.svg?logo=googletranslate&logoColor=white)]()

3.Data structure - MongoDB
=
 
 Learn how to model NoSQL databases.

 >**How are the activities organized?**
>
>Each theme contains 3 levels of difficulty. The higher the level, the greater the difficulty. Likewise, the same level may contain more than one exercise.


🌟 Level 1
-

An optics, called “Cul d’Ampolla”, wants to computerize customer management and glasses sales.

First of all, optics wants to know which is the supplier of each of the glasses. 
Specifically, we want to know about each provider: 

- The name, the address (street, number, floor, door, city, postal code and country), telephone, fax, NIF.
- We want to know from the glasses: The brand, the graduation of each glass, the type of frame (floating, paste or metal), the color of the frame, the color of each glass and the price.
- Of the customers they want to store: Name, postal address, telephone number, email, registration date.
- When a new customer arrives, save the client who has been recommended by the establishment (provided that someone has recommended it).
- Our system must indicate who was the employee who sold each glasses. Defines which day/time the sale is made.


#### 📍 [Exercise 1](https://github.com/ariamdev/IT-ACADEMY-SPRINT-2/tree/main/SPRINT%202/Tasca%20S2%2003%20%20Estructura%20de%20dades%20-%20MongoDB/Nivell%201/Exercici1)

Imagine that we have the following graphical interface, from the point of view of an Optician client. 
How would you design the database that would provide the information?

![opticaSQL](https://github.com/user-attachments/assets/5d6b4ba8-0394-4bae-b1fa-5a032e164001)


#### 📍 [Exercise 2](https://github.com/ariamdev/IT-ACADEMY-SPRINT-2/tree/main/SPRINT%202/Tasca%20S2%2003%20%20Estructura%20de%20dades%20-%20MongoDB/Nivell%201/Exercici2)

What if the point of view of the interface were the glasses?

![opticaSQL2](https://github.com/user-attachments/assets/d6b684f2-1e6d-4a0b-a530-c205e3979bcb)

⭐🌟 Level 2
-

#### 📍 [Exercise 1](https://github.com/ariamdev/IT-ACADEMY-SPRINT-2/tree/main/SPRINT%202/Tasca%20S2%2003%20%20Estructura%20de%20dades%20-%20MongoDB/Nivell%202/Exercici1)

They have hired you to design a website that allows you to place food orders at home on the Internet.

Take into account the following indications to model what the project database would be like:

- For each client we store a unique identifier: Name, surname, address, postal code, town, province, telephone number.
- A person can place many orders, but a single order can only be made by a single person.
- A unique identifier is stored for each order: Date/time of delivery, if the order is for delivery at home or to pick up in store, the amount of products that have been selected of each type, the total price as well as a note with additional information.
- An order may consist of one or more products.
- Products can be pizzas, hamburgers and drinks. A unique identifier is stored for each product: Name, description, image, price. In the case of pizzas there are several categories that can change their name throughout the year.
- An order is managed by a single store and a store can manage many orders. A unique identifier is stored from each store: Address, postal code, town, province.
- In a store many employees can work and an employee can only work in a store. Of each employee, a unique identifier is stored: Name, surname, NIF, Telephone, if you work as a cook or delivery person.
- For delivery orders at home you are interested in saving who is the delivery person who makes the delivery of the order and the date/time of delivery.

  ![image](https://github.com/user-attachments/assets/10322547-898c-47f0-8d02-4e52e1385ffb)
