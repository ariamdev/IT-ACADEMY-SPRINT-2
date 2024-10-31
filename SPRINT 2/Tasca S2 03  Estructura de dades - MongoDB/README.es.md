[![EN](https://img.shields.io/badge/EN-blue.svg?logo=googletranslate&logoColor=white)](https://github.com/ariamdev/IT-ACADEMY-SPRINT-2/blob/main/SPRINT%202/Tasca%20S2%2003%20%20Estructura%20de%20dades%20-%20MongoDB/README.md)
[![CAT](https://img.shields.io/badge/CAT-yellow.svg?logo=googletranslate&logoColor=white)](https://github.com/ariamdev/IT-ACADEMY-SPRINT-2/blob/main/SPRINT%202/Tasca%20S2%2003%20%20Estructura%20de%20dades%20-%20MongoDB/README.cat.md)


3.Estructura de datos - MongoDB
=

Aprender a modelar base de datos NoSQL.

>**Como se organizan las actividades?**
>
>Cada tema contiene 3 niveles de dificultad. A mayor nivel, mayor dificultad. Así mismo, un mismo nivel puede contener más de un ejercicio. 

🌟 Nivel 1
-

Una óptica, llamada “Culo de Botella”, quiere informatizar la gestión de los clientes/se y ventas de gafas.

En primer lugar, la óptica quiere saber cuál es el proveedor de cada una de las gafas. 

- En concreto quiere saber de cada proveedor: El nombre, la dirección (calle, número, piso, puerta, ciudad, código postal y país), teléfono, fax, NIF.
- De las gafas se quiere saber: La marca, la graduación de cada uno de los cristales, el tipo de montura (flotante, pasta o metálica), el color de la montura, el color de cada cristal y el precio.
- De los clientes/se quiere almacenar: El nombre, la dirección postal, el teléfono, el correo electrónico, la fecha de registro.
- Cuando llega uno/a cliente/a nuevo, almacenar el/la cliente/a que le ha recomendado el establecimiento (siempre que alguien le haya recomendado).
- Nuestro sistema tendrá que indicar quién ha sido el empleado/da que ha vendido cada gafa. Define qué día/hora se realiza la venta.

#### 📍 [Ejercicio 1](https://github.com/ariamdev/IT-ACADEMY-SPRINT-2/tree/main/SPRINT%202/Tasca%20S2%2003%20%20Estructura%20de%20dades%20-%20MongoDB/Nivell%201/Exercici1)

Imagina que tenemos la siguiente interfaz gráfica, desde el punto de vista de un cliente de la Óptica. 
Cómo diseñarías la base de datos que facilitara la información?

![opticaSQL](https://github.com/user-attachments/assets/5d6b4ba8-0394-4bae-b1fa-5a032e164001)

#### 📍 [Ejercicio 2](https://github.com/ariamdev/IT-ACADEMY-SPRINT-2/tree/main/SPRINT%202/Tasca%20S2%2003%20%20Estructura%20de%20dades%20-%20MongoDB/Nivell%201/Exercici2)

Y si el punto de vista de la interficie fuesen las gafas?

![opticaSQL2](https://github.com/user-attachments/assets/d6b684f2-1e6d-4a0b-a530-c205e3979bcb)

⭐🌟 Nivel 2
-

#### 📍 [Ejercicio 1](https://github.com/ariamdev/IT-ACADEMY-SPRINT-2/tree/main/SPRINT%202/Tasca%20S2%2003%20%20Estructura%20de%20dades%20-%20MongoDB/Nivell%202/Exercici1)

Te han contratado para diseñar una web que permita hacer pedidos de comer a domicilio por Internet.

Ten en cuenta las siguientes indicaciones para modelar cómo sería la base de datos del proyecto:

- Para cada cliente/a almacenamos un identificador único: Nombre, apellidos, dirección, código postal, localidad, provincia, número de teléfono.
- Una persona puede realizar muchos pedidos, pero un único pedido solo puede ser realizado por una única persona. De cada pedido se almacena un identificador único: Data/hora de realización,
si el pedido es para reparto a domicilio o para recoger en tienda, la cantidad de productos que se han seleccionado de cada tipo, el precio total además de una nota con información adicional.

Un pedido puede constar de uno o varios productos.

- Los productos pueden ser pizzas, hamburguesas y bebidas.
- De cada producto se almacena un identificador único: Nombre, descripción, imagen, precio. En el caso de las pizzas existen varias categorías que pueden ir cambiante de nombre a lo largo del año.

Un pedido es gestionado por una única tienda y una tienda puede gestionar muchos pedidos. 
- De cada tienda se almacena un identificador único: Dirección, código postal, localidad, provincia.
- En una tienda pueden trabajar muchos empleados/das y un empleado/da solo puede trabajar en una tienda. De cada empleado/da, se almacena un identificador único: Nombre, apellidos, NIF, Teléfono, si trabaja como cocinero/a o repartidor/a. 
- Para los pedidos de reparto a domicilio interesa guardar quién es el repartidor/a que hace la entrega del pedido y la data/hora del momento de la entrega.

![image](https://github.com/user-attachments/assets/10322547-898c-47f0-8d02-4e52e1385ffb)
