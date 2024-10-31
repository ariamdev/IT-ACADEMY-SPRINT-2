[![EN](https://img.shields.io/badge/EN-blue.svg?logo=googletranslate&logoColor=white)](https://github.com/ariamdev/IT-ACADEMY-SPRINT-2/tree/main/SPRINT%202/Tasca%20S2%2004%20MongoDB%20queries#readme)
[![CAT](https://img.shields.io/badge/CAT-yellow.svg?logo=googletranslate&logoColor=white)](https://github.com/ariamdev/IT-ACADEMY-SPRINT-2/blob/main/SPRINT%202/Tasca%20S2%2004%20MongoDB%20queries/queries.js)


4.MongoDB queries 
=

Aprender a consultar una base de datos NoSQL.

>**Como se organizan las actividades?**
>
>Cada tema contiene 3 niveles de dificultad. A mayor nivel, mayor dificultad. Así mismo, un mismo nivel puede contener más de un ejercicio.
>
>🌟Nivel 1
>
>Si construyes 17 consultas correctas.
>
>⭐🌟Nivel 2
>
>Tendrás nivel 2 si construyes entre 17 y 25 consultas correctas.
>
>⭐⭐🌟Nivel 3
>
>Nivel 3 si consigues construir correctamente más de 256 consultas correctas.

#### 📍 [Restaurante de Nueva York]()

Tenemos una colección de Objetos Restaurando en la ciudad de Nueva York, y necesitamos algunas consultas... puedes ayudarnos?

1. Escribe una consulta para mostrar todos los documentos en la colección Restaurantes.
2. Escribe una consulta para mostrar el restaurante_*id, *name, *borough y *cuisine por todos los documentos en la colección Restaurantes.
3. Escribe una consulta para mostrar el restaurante_*id, *name, *borough y *cuisine, pero excluye el campo _*id por todos los documentos en la colección Restaurantes.
4. Escribe una consulta para mostrar restaurando_*id, *name, *borough y *zip *code, pero excluye el campo _*id por todos los documentos en la colección Restaurantes.
5. Escribe una consulta para mostrar todos los restaurantes que están en el *Bronx.
6. Escribe una consulta para mostrar los primeros 5 restaurantes que están en el *Bronx.
7. Escribe una consulta para mostrar el próximo 5 restaurantes después de saltar los primeros 5 del *Bronx.
8. Escribe una consulta para encontrar los restaurantes que tienen un *score de más de 90.
9. Escribe una consulta para encontrar los restaurantes que tienen un *score de más de 80 pero menos que 100.
10. Escribe una consulta para encontrar los restaurantes que se localizan en valor de latitud menos de -95.754168.
11. Escribe una consulta de *MongoDB para encontrar los restaurantes que no preparan jefe *cuisine de '*American' y su calificación es superior en 70 y longitud inferior a -65.754168.
12. Escribe una consulta para encontrar los restaurantes que no preparan jefe *cuisine de '*American' y consiguieron un marcador más de 70 y localizado en la longitud menos que -65.754168. Nota: Fez esta consulta sin utilizar $*and operador.
13. Escribe una consulta para encontrar los restaurantes que no preparan jefe *cuisine de '*American' y obtuvieron un punto de grado 'A' no pertenece a Brooklyn. Se tiene que mostrar el documento según la *cuisine en orden descendente.
14. Escribe una consulta para encontrar el restaurante_*id, *name, *borough y *cuisine para aquellos restaurantes que contienen '*Wil' como las tres primeras letras en su nombre.
15. Escribe una consulta para encontrar el restaurante_*id, *name, *borough y *cuisine para aquellos restaurantes que contienen 'ces' como las últimas tres letras en su nombre.
16. Escribe una consulta para encontrar el restaurante_*id, *name, *borough y *cuisine para aquellos restaurantes que contienen 'Riego' como tres letras en algún lugar en su nombre.
17. Escribe una consulta para encontrar los restaurantes que pertenecen al *Bronx y prepararon cualquier plato americano o chino.
18. Escribe una consulta para encontrar el restaurante_*id, *name, *borough y *cuisine para aquellos restaurantes que pertenecen a *Staten *Island o *Queens o *Bronx o Brooklyn.
19. Escribe una consulta para encontrar el restaurante_*id, *name, *borough y *cuisine para aquellos restaurantes que no pertenecen a *Staten *Island o *Queens o *Bronx o Brooklyn.
20. Escribe una consulta para encontrar el restaurante_*id, *name, *borough y *cuisine para aquellos restaurantes que consigan un marcador que no es más de 10.
21. Escribe una consulta para encontrar el restaurante_*id, *name, *borough y *cuisine para aquellos restaurantes que preparan pescado excepto '*American' y '*Chinees' o lo *name del restaurante empieza con letras '*Wil'.
22. Escribe una consulta para encontrar el restaurante_*id, *name, y gradas para aquellos restaurantes que consigan un grado "A" y un *score 11 en datos de estudio *ISODate "2014-08-11T00:00:00Z".
23. Escribe una consulta para encontrar el restaurante_*id, *name y gradas para aquellos restaurantes donde el 2.º elemento de variedad de grados contiene un grado de "A" y marcador 9 sobre un *ISODate "2014-08-11T00:00:00Z".
24. Escribe una consulta para encontrar el restaurante_*id, *name, dirección y ubicación geográfica para aquellos restaurantes donde el segundo elemento del *array *coord contiene un valor que es más de 42 y hasta 52.
25. Escribe una consulta para organizar el nombre de los restaurantes en orden ascendente junto con todas las columnas.
26. Escribe una consulta para organizar el nombre de los restaurantes en orden descendente junto con todas las columnas.
27. Escribe una consulta para organizar el nombre de la *cuisine en orden ascendente y por el mismo barrio de *cuisine. Orden descendente.
28. Escribe una consulta para saber todas las direcciones que no contienen la calle.
29. Escribe una consulta que seleccionará todos los documentos en la colección de restaurantes donde el valor del campo *coord es *Double.
30. Escribe una consulta que seleccionará el restaurante_*id, *name y *grade para aquellos restaurantes que devuelvan 0 como resto después de dividir el marcador por 7.
31. Escribe una consulta para encontrar el *name de restaurante, *borough, longitud y altitud y *cuisine para aquellos restaurantes que contienen 'mi' como tres letras en algún lugar de su nombre.
32. Escribe una consulta para encontrar el *name de restaurante, *borough, longitud y latitud y *cuisine para aquellos restaurantes que contienen '*Mad' como primeras tres letras de su nombre.
