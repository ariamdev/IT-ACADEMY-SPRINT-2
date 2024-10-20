[![EN](https://img.shields.io/badge/EN-blue.svg)](#eng)
[![ES](https://img.shields.io/badge/ES-red.svg)](#es)
[![CAT](https://img.shields.io/badge/CAT-yellow.svg)](#cat)


<a name="eng"></a>
🌟 Level 1
-

#### [EN] 📍 Exercise 2 - Pizza shop
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


---

<a name="es"></a>
🌟 Nivel 1
-

#### [ES] 📍 Ejercicio 2 - Pizzería
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


---

<a name="cat"></a>
🌟 Nivell 1
-

#### [CAT] 📍 Exercici 2 - Pizzeria
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
