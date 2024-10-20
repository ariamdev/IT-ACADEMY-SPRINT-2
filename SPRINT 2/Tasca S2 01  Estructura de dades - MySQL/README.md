[![EN](https://img.shields.io/badge/EN-blue.svg)](#eng)
[![ES](https://img.shields.io/badge/ES-red.svg)](#es)
[![CAT](https://img.shields.io/badge/CAT-yellow.svg)](#cat)

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

<a name="es"></a>
**1. Estructura de datos - MySQL**
=

Aprender a modelar bases de datos SQL.

>**Como se organizan las actividades?**
>
>Cada tema contiene 3 niveles de dificultad. A mayor nivel, mayor dificultad. Así mismo, un mismo nivel puede contener más de un ejercicio. 

🌟 Nivel 1
-

#### 📍 [Ejercicio 1 - Óptica](https://github.com/ariamdev/IT-ACADEMY-SPRINT-2/tree/main/SPRINT%202/Tasca%20S2%2001%20%20Estructura%20de%20dades%20-%20MySQL/n1exercici1)

Una óptica, llamada “Culo de Botella”, quiere informatizar la gestión de los clientes/se y ventas de gafas.

En primer lugar, la óptica quiere saber cuál es el proveedor de cada una de las gafas. En concreto quiere saber de cada proveedor:
+ El nombre
+ La dirección (calle, número, piso, puerta, ciudad, código postal y país)
+ Teléfono
+ Fax
+ NIF.

La política de compras de la óptica se basa que las gafas de una marca se comprarán a un único proveedor (así podrá sacar más buenos precios), 
pero pueden comprar gafas de varias marcas a un proveedor. De las gafas quiere saber:
+ La marca.
+ La graduación de cada uno de los vidrios.
+ El tipo de montura (flotante, pasta o metálica).
+ El color de la montura.
+ El color de cada vidrio.
+ El precio.

De los clientes/se quiere almacenar:
+ El nombre.
+ La dirección postal.
+ El teléfono.
+ El correo electrónico.
+ La fecha de registro.
+ 
Cuando llega uno/a cliente/a nuevo, almacenar el/la cliente/a que le ha recomendado el establecimiento (siempre que alguien le haya recomendado).
Nuestro sistema tendrá que indicar quién ha sido el empleado/da que ha vendido cada gafa.

#### 📍 [Ejercicio 2 - Pizzería](https://github.com/ariamdev/IT-ACADEMY-SPRINT-2/tree/main/SPRINT%202/Tasca%20S2%2001%20%20Estructura%20de%20dades%20-%20MySQL/n1exercici2#cat)
Te han contratado para diseñar una web que permita hacer pedidos de comer a domicilio por Internet.

Ten en cuenta las siguientes indicaciones para modelar cómo sería la base de datos del proyecto:

Para cada cliente/a almacenamos un identificador único:
+ Nombre.
+ Apellidos.
+ Dirección.
+ Código postal.
+ Localidad.
+ Provincia.
+ Número de teléfono.
+ Los datos de localidad y provincia estarán almacenados en tablas separadas.
Sabemos que una localidad pertenece en una única provincia, y que una provincia puede tener muchas localidades.
Para cada localidad almacenamos un identificador único y un nombre. Para cada provincia almacenamos un identificador único y un nombre.

Una persona puede realizar muchos pedidos, pero un único pedido solo puede ser realizado por una única persona. 
De cada pedido se almacena un identificador único:
+ Fecha/hora.
+ Si el pedido es para reparto a domicilio o para recoger en tienda.
+ La cantidad de productos que se han seleccionado de cada tipo.
+ El precio total.

Un pedido puede constar de uno o varios productos.

Los productos pueden ser pizzas, hamburguesas y bebidas. De cada producto se almacena un identificador único:
+ Nombre.
+ Descripción.
+ Imagen.
+ Precio.

En el caso de las pizzas existen varias categorías que pueden ir cambiante de nombre a lo largo del año. 
Una pizza solo puede estar dentro de una categoría, pero una categoría puede tener muchas pizzas.

De cada categoría se almacena un identificador único y un nombre. 
Un pedido es gestionado por una única tienda y una tienda puede gestionar muchos pedidos. De cada tienda se almacena un identificador único:
+ Dirección.
+ Código postal.
+ Localidad.
+ Provincia.

En una tienda pueden trabajar muchos empleados/des y un empleado/da solo puede trabajar en una tienda. De cada empleado/da, se almacena un identificador único:
+ Nombre.
+ Apellidos.
+ NIF.
+ Teléfono.
+ Si trabaja como cocinero/a o repartidor/a.
+ Para los pedidos de reparto a domicilio interesa guardar quién es el repartidor/a que hace la entrega del pedido y la fecha/hora del momento de la entrega.


⭐🌟Nivel 2
-

#### 📍 [Ejercicio 1 - YouTube](https://github.com/ariamdev/IT-ACADEMY-SPRINT-2/tree/main/SPRINT%202/Tasca%20S2%2001%20%20Estructura%20de%20dades%20-%20MySQL/n2exercici1)
Trataremos de hacer un modelo sencillo de cómo sería la base de datos para una versión reducida de YouTube.

De cada usuario/aria guardamos un identificador único:
+ Email.
+ Password.
+ Nombre de usuario/aria.
+ Fecha de nacimiento.
+ Género.
+ País.
+ Código postal.

Un usuario/aria publica videos. De cada video guardamos un identificador único:
+ Un título.
+ Una descripción.
+ Un tamaño.
+ El nombre del archivo de video.
+ Duración del video.
+ Un thumbnail.
+ El número de reproducciones.
+ El número de likes.
+ El número de dislikes.

Un video puede tener tres estados diferentes: público, oculto y privado. 
Un video puede tener muchas etiquetas. 
Una etiqueta se identifica por un identificador único y un nombre de etiqueta. 
Interesa guardar quién es el usuario/aria que publica el video y en qué fecha/hora lo hace.


Un usuario/aria puede crear un canal. Un canal tiene un identificador único:
+ Un nombre.
+ Una descripción.
+ Una fecha de creación.


Un usuario/aria se puede subscribir en los canales otros usuarios/se. 
Un usuario/aria puede darle un like o un dislike a un video una única vez. 
Habrá que llevar un registro de los usuarios/se que le han dado like y dislike a un determinado video y en qué fecha/hora lo hicieron.


Un usuario/aria puede crear playlists con los videos que le gustan. Cada playlist tiene un identificador único:
+ Un nombre.
+ Una fecha de creación.
+ Un estado que indica que puede ser pública o privada.


Un usuario/aria puede escribir comentarios en un video determinado. Cada comentario está identificado por un identificador único:
+ El texto del comentario.
+ La fecha/hora en la cual se realizó.


Un usuario/aria puede marcar un comentario como me gusta o no me gusta. 
Habrá que llevar un registro de los usuarios/se que han marcado un comentario como me gusta/no me gusta, y en qué fecha/hora lo hicieron.

---

<a name="cat"></a>
**1. Estructura de dades - MySQL**
=

Aprendre a modelar bases de dades SQL.


>**Com s'organitzen les activitats?**
>
>Cada tema conté 3 nivells de dificultat. A major nivell, major dificultat. Així mateix, un mateix nivell pot contenir més d'un exercici.


🌟 Nivell 1
-

#### 📍 [Exercici 1 - Òptica](https://github.com/ariamdev/IT-ACADEMY-SPRINT-2/tree/main/SPRINT%202/Tasca%20S2%2001%20%20Estructura%20de%20dades%20-%20MySQL/n1exercici1)
Una òptica, anomenada “Cul d'Ampolla”, vol informatitzar la gestió dels clients/es i vendes d'ulleres.

En primer lloc, l'òptica vol saber quin és el proveïdor de cadascuna de les ulleres. En concret vol saber de cada proveïdor:
+ El nom
+ L'adreça (carrer, número, pis, porta, ciutat, codi postal i país)
+ Telèfon
+ Fax
+ NIF.

La política de compres de l'òptica es basa que les ulleres d'una marca es compraran a un únic proveïdor (així en podrà treure més bons preus), 
però poden comprar ulleres de diverses marques a un proveïdor. De les ulleres vol saber:
+ La marca.
+ La graduació de cadascun dels vidres.
+ El tipus de muntura (flotant, pasta o metàl·lica).
+ El color de la muntura.
+ El color de cada vidre.
+ El preu.

Dels clients/es vol emmagatzemar:
+ El nom.
+ L'adreça postal.
+ El telèfon.
+ El correu electrònic.
+ La data de registre.
+ Quan arriba un/a client/a nou, emmagatzemar el/la client/a que li ha recomanat l'establiment (sempre que algú li hagi recomanat).

El nostre sistema haurà d’indicar qui ha sigut l’empleat/da que ha venut cada ullera.

#### 📍 [Exercici 2 - Pizzeria](https://github.com/ariamdev/IT-ACADEMY-SPRINT-2/tree/main/SPRINT%202/Tasca%20S2%2001%20%20Estructura%20de%20dades%20-%20MySQL/n1exercici2#cat)
T’han contractat per a dissenyar una web que permeti fer comandes de menjar a domicili per Internet.

Tingues en compte les següents indicacions per a modelar com seria la base de dades del projecte:

Per a cada client/a emmagatzemem un identificador únic:
+ Nom.
+ Cognoms.
+ Adreça.
+ Codi postal.
+ Localitat.
+ Província.
+ Número de telèfon.
+ Les dades de localitat i província estaran emmagatzemats en taules separades. Sabem que una localitat pertany a una única província, i que una província pot tenir moltes localitats. Per a cada localitat emmagatzemem un identificador únic i un nom. Per a cada província emmagatzemem un identificador únic i un nom.

Una persona pot realitzar moltes comandes, però una única comanda només pot ser realitzat per una única persona. De cada comanda s'emmagatzema un identificador únic:
+ Data/hora.
+ Si la comanda és per a repartiment a domicili o per a recollir en botiga.
+ La quantitat de productes que s'han seleccionat de cada tipus.
+ El preu total.

Una comanda pot constar d'un o diversos productes.

Els productes poden ser pizzes, hamburgueses i begudes. De cada producte s'emmagatzema un identificador únic:
+ Nom.
+ Descripció.
+ Imatge.
+ Preu.

En el cas de les pizzes existeixen diverses categories que poden anar canviant de nom al llarg de l'any.
Una pizza només pot estar dins d'una categoria, però una categoria pot tenir moltes pizzes.

De cada categoria s'emmagatzema un identificador únic i un nom. Una comanda és gestionada per una única botiga i una botiga pot gestionar moltes comandes. 
De cada botiga s'emmagatzema un identificador únic:
+ Adreça.
+ Codi postal.
+ Localitat.
+ Província.


En una botiga poden treballar molts empleats/des i un empleat/da només pot treballar en una botiga. De cada empleat/da, s'emmagatzema un identificador únic:
+ Nom.
+ Cognoms.
+ NIF.
+ Telèfon.
+ Si treballa com a cuiner/a o repartidor/a.

Per a les comandes de repartiment a domicili interessa guardar qui és el repartidor/a que fa el lliurament de la comanda i la data/hora del moment del lliurament.

⭐🌟Nivell 2
-

#### 📍 [Exercici 1 - YouTube](https://github.com/ariamdev/IT-ACADEMY-SPRINT-2/tree/main/SPRINT%202/Tasca%20S2%2001%20%20Estructura%20de%20dades%20-%20MySQL/n2exercici1)
Tractarem de fer un model senzill de com seria la base de dades per a una versió reduïda de YouTube.

De cada usuari/ària guardem un identificador únic:
+ Email.
+ Password.
+ Nom d'usuari/ària.
+ Data de naixement.
+ Sexe.
+ País.
+ Codi postal.


Un usuari/ària publica vídeos. De cada vídeo guardem un identificador únic:
+ Un títol.
+ Una descripció.
+ Una grandària.
+ El nom de l'arxiu de vídeo.
+ Durada del vídeo.
+ Un thumbnail.
+ El nombre de reproduccions.
+ El número de likes.
+ El número de dislikes.

Un vídeo pot tenir tres estats diferents: públic, ocult i privat. 
Un vídeo pot tenir moltes etiquetes. Una etiqueta s'identifica per un identificador únic i un nom d'etiqueta. 
Interessa guardar qui és l'usuari/ària que publica el vídeo i en quina data/hora el fa.

Un usuari/ària pot crear un canal. Un canal té un identificador únic:
+ Un nom.
+ Una descripció.
+ Una data de creació.


Un usuari/ària es pot subscriure als canals d'altres usuaris/es. 
Un usuari/ària pot donar-li un like o un dislike a un vídeo una única vegada. 
Caldrà portar un registre dels usuaris/es que li han donat like i dislike a un determinat vídeo i en quina data/hora ho van fer.


Un usuari/ària pot crear playlists amb els vídeos que li agraden. Cada playlist té un identificador únic:
+ Un nom.
+ Una data de creació.
+ Un estat que indica que pot ser pública o privada.


Un usuari/ària pot escriure comentaris en un vídeo determinat. Cada comentari està identificat per un identificador únic:
+ El text del comentari.
+ La data/hora en la qual es va realitzar.


Un usuari/ària pot marcar un comentari com m'agrada o no m'agrada. 
Caldrà portar un registre dels usuaris/es que han marcat un comentari com m'agrada/no m'agrada, i en quina data/hora ho van fer.


