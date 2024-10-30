[![ES](https://img.shields.io/badge/ES-red.svg?logo=googletranslate&logoColor=white)](https://github.com/ariamdev/IT-ACADEMY-SPRINT-2/blob/main/SPRINT%202/Tasca%20S2%2001%20%20Estructura%20de%20dades%20-%20MySQL/README.es.md)
[![CAT](https://img.shields.io/badge/CAT-yellow.svg?logo=googletranslate&logoColor=white)](https://github.com/ariamdev/IT-ACADEMY-SPRINT-2/blob/main/SPRINT%202/Tasca%20S2%2001%20%20Estructura%20de%20dades%20-%20MySQL/README.cat.md)

<a name="eng"></a>
**1. Data structure - MySQL**
=

Learn how to model SQL databases.

>**How are the activities organized?**
>
>Each theme contains 3 levels of difficulty. The higher the level, the greater the difficulty. Likewise, the same level may contain more than one exercise.


🌟 Level 1
-

#### 📍 [Exercise 1 - Optician's shop](https://github.com/ariamdev/IT-ACADEMY-SPRINT-2/tree/main/SPRINT%202/Tasca%20S2%2001%20%20Estructura%20de%20dades%20-%20MySQL/n1exercici1)

An optics, called “Cul d’Ampolla”, wants to computerize customer management and glasses sales.

First of all, optics wants to know which is the supplier of each of the glasses. Specifically, you want to know about each provider:
+ The name
+ Address (street, number, floor, door, city, postal code and country)
+ Phone
+ Fax
+ NIF

The optics purchasing policy is based on the fact that a brand’s glasses will be purchased from a single supplier (you can get better prices),
but you can buy glasses from various brands from a supplier. From the glasses he wants to know:
+ The brand.
+ The graduation of each of the glasses.
+ The type of mount (floating, paste or metal).
+ The color of the mount.
+ The color of each glass.
+ The price.

Of the customers they want to store:
+ The name.
+ The postal address.
+ The phone.
+ The email.
+ The registration date.

When a new customer arrives, store the client who has been recommended by the establishment (provided that someone has recommended it).
Our system must indicate who was the employee who sold each glasses.


#### 📍 [Exercise 2 - Pizza shop](https://github.com/ariamdev/IT-ACADEMY-SPRINT-2/tree/main/SPRINT%202/Tasca%20S2%2001%20%20Estructura%20de%20dades%20-%20MySQL/n1exercici2#cat)
They have hired you to design a website that allows you to place food orders at home on the Internet.

Take into account the following indications to model what the project database would be like:

For each client we store a unique identifier:
+ Name.
+ Last name.
+ Address.
+ Postal code.
+ Locality.
+ Province.
+ Phone number.
+ The locality and province data will be stored in separate tables. We know that a locality belongs to a single province, and that a province can have many localities. For each locality we store a unique identifier and a name. For each province we store a unique identifier and a name.

A person can place many orders, but a single order can only be made by a single person. A unique identifier is stored for each order:
+ Date/Time.
+ If the order is for delivery at home or to pick up at the store.
+ The amount of products that have been selected for each type.
+ The total price.

An order may consist of one or more products.

Products can be pizzas, hamburgers and drinks. A unique identifier is stored for each product:
+ Name.
+ Description.
+ Image.
+ Price.

In the case of pizzas there are several categories that can change their name throughout the year. A pizza can only be in one category, but a category can have many pizzas.


A unique identifier and a name are stored in each category. An order is managed by a single store and a store can manage many orders. A unique identifier is stored from each store:
+ Address.
+ Postal code.
+ Locality.
+ Province.


In a store many employees can work and an employee can only work in a store. Of each employee, a unique identifier is stored:
+ Name.
+ Last name.
+ NIF.
+ Telephone.

If you work as a cook or delivery company, for home delivery orders you are interested in saving who is the delivery provider who delivers the order and the date/time of delivery.


⭐🌟 Level 2
-

#### 📍 [Exercise 1 - YouTube](https://github.com/ariamdev/IT-ACADEMY-SPRINT-2/tree/main/SPRINT%202/Tasca%20S2%2001%20%20Estructura%20de%20dades%20-%20MySQL/n2exercici1)
We will try to make a simple model of what the database would be like for a reduced version of YouTube.

From each user we save a unique identifier:
+ Email.
+ Password.
+ Username.
+ Date of birth.
+ Gender.
+ Country.
+ Postal code.


A user publishes videos. From each video we save a unique identifier:
+ A title.
+ A description.
+ A size.
+ The name of the video archive.
+ Duration of the video.
+ A thumbnail.
+ The number of reproductions.
+ The likes number.
+ The dislike number.

A video can have three different states: public, hidden and private. A video can have many tags. A label is identified by a unique identifier and a tag name.
It is interesting to save who is the user who publishes the video and on what date / time he does it.

A user can create a channel. A channel has a unique identifier:
+ A name.
+ A description.
+ A date of creation.


A user can subscribe to the channels of other users. A user can give a like or dislike to a video once. 
It will be necessary to bring a record of the users who have given like and dislike to a certain video and on what date/time they did it.


A user can create playlists with the videos they like. Each playlist has a unique identifier:
+ A name.
+ A date of creation.
+ A state that indicates that it can be public or private.


A user can write comments in a given video. Each comment is identified by a unique identifier:
+ The text of the comment.
+ The date/time at which it was made.


A user can mark a comment as I like it or not. You will have to bring a record of the users who have marked a comment as I like it or not, 
and on what date/time they did.

---

<a name="cat"></a>

