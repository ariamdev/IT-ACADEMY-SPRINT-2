[![EN](https://img.shields.io/badge/EN-blue.svg?logo=googletranslate&logoColor=white)](https://github.com/ariamdev/IT-ACADEMY-SPRINT-2/blob/main/README.md)
[![CAT](https://img.shields.io/badge/CAT-yellow.svg?logo=googletranslate&logoColor=white)](https://github.com/ariamdev/IT-ACADEMY-SPRINT-2/blob/main/SPRINT%202/Tasca%20S2%2001%20%20Estructura%20de%20dades%20-%20MySQL/README.cat.md)

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
