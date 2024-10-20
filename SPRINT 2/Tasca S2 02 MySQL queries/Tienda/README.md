[![EN](https://img.shields.io/badge/EN-blue.svg)](#eng)
[![ES](https://img.shields.io/badge/ES-red.svg)](#es)
[![CAT](https://img.shields.io/badge/CAT-yellow.svg)](#cat)


<a name="eng"></a>

[EN] 📍 Store Database
-

We have the product and manufacturing tables, each with the following fields:
- product (code, number, precision, manufacturercode)
- manufacturer (code, number)

The 'manufacturercode' field of the product entity is related to the 'code' field of the manufacturing entity.

Please make the following queries:

1. List the name of all the products in the product table.
2. List the names and prices of all the products in the product table.
3. List all the columns of the product table.
4. Lists the name of the products, the price in Euros and the price in US dollars (USD).
5. Lists the product name, the price in Euros and the price in US dollars (USD). Use the following lines for the columns: product name, euros, dollars.
6. Lists the names and prices of all the products in the product table, converting the names to uppercase.
7. List the names and prices of all the products in the product table, converting the names to lower case.
8. List the name of all the manufacturers in one column, and in another column get in uppercase the first two characters of the manufacturer's name.
9. List the names and the prices of all the products in the product table, showing the price value.
10. Lists the names and prices of all the products in the product table, truncating the price value to show it without any decimal places.
11. Lists the code of the manufacturers that have products in the product table.
12. Lists the code of the manufacturers that have products in the product table, eliminating the codes that are repeated.
13. Lists the names of the manufacturers in ascending order.
14. Lists the names of the manufacturers sorted in descending order.
15. Lists the names of the products ordered, first, by name in ascending order and, second, by price in descending order.
16. Returns a list with the first 5 files of the manufacturer table.
17. Returns a list with 2 files from the fourth row of the manufacturer table. The fourth row must also be included in the answer.
18. List the name and price of the cheapest product (only use the ORDER BY and LIMIT clauses). NOTE: Here you could not use MIN(price), you would need GROUP BY.
19. List the name and price of the most expensive product (only use ORDER BY and LIMIT clauses). NOTE: Here you could not use MAX(price), you would need GROUP BY.
20. Lists the name of all the products of the manufacturer whose manufacturer code is equal to 2.
21. Returns a list with the product name, price and manufacturer name of all products in the database.
22. Returns a list with the product name, price and manufacturer name of all products in the database. Sorts the result by the manufacturer's name, in alphabetical order.
23. Returns a list with the product code, product name, manufacturer code and manufacturer name, of all database products.
24. Returns the name of the product, its price and the name of its manufacturer, of the cheapest product.
25. Returns the name of the product, its price and the name of its manufacturer, of the most expensive product.
26. Returns a list of all Lenovo manufacturer products.
27. Returns a list of all Crucial manufacturer products that have a price greater than € 200.
28. Returns a list of all Asus manufacturers' products, Hewlett-Packardy Seagate. Without using the IN operator.
29. Returns a list of all Asus manufacturers' products, Hewlett-Packardy Seagate. Using the IN operator.
30. Returns a list with the name and price of all manufacturers' products whose name ends with the vowel e. Returns a list with the name and price of all products whose manufacturer name contains the character w in their name.
31. Return a list with the product name, price and manufacturer name, of all products that have a price greater than or equal to € 180. Sorts the result first by the price (in descending order) and second by the name (in ascending order).
32. Returns a list with the manufacturer's code and name, only for those manufacturers who have products associated with the database.
33. Returns a list of all the manufacturers that exist in the database, together with the products that each of them has. The list must also show those manufacturers who do not have associated products.
34. Returns a list where only those manufacturers who do not have any associated products appear.
35. Returns all products from the Lenovo manufacturer. (Without using INNER JOIN).
36. Returns all the data of the products that have the same price as the most expensive product of the manufacturer Lenovo. (Without using INNER JOIN).
37. List the name of the most expensive product by manufacturer Lenovo.
38. List the name of the cheapest product from Hewlett-Packard.
39. Returns all database products that have a higher or equal price to the most expensive product of the manufacturer Lenovo.
40. Read all Asus manufacturer products that have a price higher than the average price of all their products.

---

<a name="es"></a>
[ES] 📍 Base de datos Tienda
-

Tenemos las tablas producto y fabricante, cada una con los siguientes campos:
- producto (código, número, precio, codigofabricante)
- fabricante (código, número)

El campo 'códigofabricante' de la entidad producto se relaciona con el campo 'código' de la entidad fabricante.

Por favor, efectúa las siguientes consultas:

1. Lista el nombre de todos los productos que hay en la tabla producto.
2. Lista los nombres y los precios de todos los productos de la tabla producto.
3. Lista todas las columnas de la tabla producto.
4. Lista el nombre de los productos, el precio en euros y el precio en dólares estadounidenses (USD).
5. Lista el nombre de los productos, el precio en euros y el precio en dólares estadounidenses (USD). Utiliza los siguientes alias para las columnas: nombre de producto, euros, dólares.
6. Lista los nombres y los precios de todos los productos de la tabla producto, convirtiendo los nombres a mayúscula.
7. Lista los nombres y los precios de todos los productos de la tabla producto, convirtiendo los nombres a minúscula.
8. Lista el nombre de todos los fabricantes en una columna, y en otra columna obtenga en mayúsculas los dos primeros caracteres del nombre del fabricante.
9. Lista los nombres y los precios de todos los productos de la tabla producto, redondeando el valor del precio.
10. Lista los nombres y los precios de todos los productos de la tabla producto, truncando el valor del precio para mostrarlo sin ninguna cifra decimal.
11. Lista el código de los fabricantes que tienen productos en la tabla producto.
12. Lista el código de los fabricantes que tienen productos en la tabla producto, eliminando los códigos que aparecen repetidos.
13. Lista los nombres de los fabricantes ordenados de manera ascendente.
14. Lista los nombres de los fabricantes ordenados de manera descendente.
15. Lista los nombres de los productos ordenados, en primer lugar, por el nombre de manera ascendente y, en segundo lugar, por el precio de manera descendente.
16. Devuelve una lista con las 5 primeras filas de la tabla fabricante.
17. Devuelve una lista con 2 filas a partir de la cuarta fila de la tabla fabricante. La cuarta fila también se tiene que incluir en la respuesta.
18. Lista el nombre y el precio del producto más barato. (Utiliza solo las cláusulas *ORDER *BY y LÍMITE). NOTA: Aquí no podría usar *MIN(precio), necesitaría *GROUP *BY.
19. Lista el nombre y el precio del producto más caro. (Utiliza solo las cláusulas *ORDER *BY y LÍMITE). NOTA: Aquí no podría usar MAX(precio), necesitaría *GROUP *BY.
20. Lista el nombre de todos los productos del fabricante el código de fabricante del cual es igual a 2.
21. Devuelve una lista con el nombre del producto, precio y nombre de fabricante de todos los productos de la base de datos.
22. Devuelve una lista con el nombre del producto, precio y nombre de fabricante de todos los productos de la base de datos. Ordena el resultado por el nombre del fabricante, por orden alfabético.
23. Devuelve una lista con el código del producto, nombre del producto, código del fabricante y nombre del fabricante, de todos los productos de la base de datos.
24. Devuelve el nombre del producto, su precio y el nombre de su fabricante, del producto más barato.
25. Devuelve el nombre del producto, su precio y el nombre de su fabricante, del producto más caro.
26. Devuelve una lista de todos los productos del fabricante Lenovo.
27. Devuelve una lista de todos los productos del fabricante Crucial que tengan un precio mayor que 200 €.
28. Devuelve un listado con todos los productos de los fabricantes *Asus, Hewlett-*Packardy *Seagate. Sin utilizar el operador *IN.
29. Devuelve un listado con todos los productos de los fabricantes *Asus, Hewlett-*Packardy *Seagate. Usando el operador *IN.
30. Devuelve un listado con el nombre y el precio de todos los productos de los fabricantes el nombre de los cuales acabe por la vocal e.
31. Devuelve un listado con el nombre y el precio de todos los productos el nombre de fabricante de los cuales contenga el carácter w en su nombre.
32. Devuelve un listado con el nombre de producto, precio y nombre de fabricante, de todos los productos que tengan un precio mayor o igual a 180 €. Ordena el resultado, en primer lugar, por el precio (en orden descendente) y, en segundo lugar, por el nombre (en orden ascendente).
33. Devuelve un listado con el código y el nombre de fabricante, solo de aquellos fabricantes que tienen productos asociados en la base de datos.
34. Devuelve un listado de todos los fabricantes que existen en la base de datos, junto con los productos que tiene cada uno de ellos. El listado tendrá que mostrar también aquellos fabricantes que no tienen productos asociados.
35. Devuelve un listado donde solo aparezcan aquellos fabricantes que no tienen ningún producto asociado.
36. Devuelve todos los productos del fabricante Lenovo. (Sin utilizar *INNER *JOIN).
37. Devuelve todos los datos de los productos que tienen el mismo precio que el producto más caro del fabricante Lenovo. (Sin usar *INNER *JOIN).
38. Lista el nombre del producto más caro del fabricante Lenovo.
39. Lista el nombre del producto más barato del fabricante Hewlett-Packard.
40- Devuelve todos los productos de la base de datos que tienen un precio mayor o igual al producto más caro del fabricante Lenovo.
41. Lista todos los productos del fabricante *Asus que tienen un precio superior al precio medio de todos sus productos.

---
<a name="cat"></a>
[CAT] 📍 Base de dades Tenda
-

Tenim les taules producto i fabricador, cadascuna amb els següents camps:
- producto (codigo, nombre, precio, codigo_fabricante)
- fabricante (codigo, nombre)

El camp 'codigo_fabricante' de l'entitat producto es relaciona amb el camp 'codi' de l'entitat fabricante.

Si us plau, efectua les següents consultes:

1. Llista el nom de tots els productes que hi ha en la taula producto.
2. Llista els noms i els preus de tots els productes de la taula producto.
3. Llista totes les columnes de la taula producto.
4. Llista el nom dels productes, el preu en euros i el preu en dòlars estatunidencs (USD).
5. Llista el nom dels productes, el preu en euros i el preu en dòlars estatunidencs (USD). Utilitza els següents àlies per a les columnes: nom de producto, euros, dòlars.
6. Llista els noms i els preus de tots els productes de la taula producto, convertint els noms a majúscula.
7. Llista els noms i els preus de tots els productes de la taula producto, convertint els noms a minúscula.
8. Llista el nom de tots els fabricants en una columna, i en una altra columna obtingui en majúscules els dos primers caràcters del nom del fabricant.
9. Llista els noms i els preus de tots els productes de la taula producto, arrodonint el valor del preu.
10. Llista els noms i els preus de tots els productes de la taula producto, truncant el valor del preu per a mostrar-lo sense cap xifra decimal.
11. Llista el codi dels fabricants que tenen productes en la taula producto.
12. Llista el codi dels fabricants que tenen productes en la taula producto, eliminant els codis que apareixen repetits.
13. Llista els noms dels fabricants ordenats de manera ascendent.
14. Llista els noms dels fabricants ordenats de manera descendent.
15. Llista els noms dels productes ordenats, en primer lloc, pel nom de manera ascendent i, en segon lloc, pel preu de manera descendent.
16. Retorna una llista amb les 5 primeres files de la taula fabricante.
17. Retorna una llista amb 2 files a partir de la quarta fila de la taula fabricante. La quarta fila també s'ha d'incloure en la resposta.
18. Llista el nom i el preu del producte més barat. (Utilitza solament les clàusules ORDER BY i LIMIT). NOTA: Aquí no podria usar MIN(preu), necessitaria GROUP BY.
19. Llista el nom i el preu del producte més car. (Utilitza solament les clàusules ORDER BY i LIMIT). NOTA: Aquí no podria usar MAX(preu), necessitaria GROUP BY.
20. Llista el nom de tots els productes del fabricant el codi de fabricant del qual és igual a 2.
21. Retorna una llista amb el nom del producte, preu i nom de fabricant de tots els productes de la base de dades.
22. Retorna una llista amb el nom del producte, preu i nom de fabricant de tots els productes de la base de dades. Ordena el resultat pel nom del fabricant, per ordre alfabètic.
23. Retorna una llista amb el codi del producte, nom del producte, codi del fabricador i nom del fabricador, de tots els productes de la base de dades.
24. Retorna el nom del producte, el seu preu i el nom del seu fabricant, del producte més barat.
25. Retorna el nom del producte, el seu preu i el nom del seu fabricant, del producte més car.
26. Retorna una llista de tots els productes del fabricant Lenovo.
27. Retorna una llista de tots els productes del fabricant Crucial que tinguin un preu major que 200 €.
28. Retorna un llistat amb tots els productes dels fabricants Asus, Hewlett-Packardy Seagate. Sense utilitzar l'operador IN.
29. Retorna un llistat amb tots els productes dels fabricants Asus, Hewlett-Packardy Seagate. Fent servir l'operador IN.
30. Retorna un llistat amb el nom i el preu de tots els productes dels fabricants el nom dels quals acabi per la vocal e.
31. Retorna un llistat amb el nom i el preu de tots els productes el nom de fabricant dels quals contingui el caràcter w en el seu nom.
32. Retorna un llistat amb el nom de producte, preu i nom de fabricant, de tots els productes que tinguin un preu major o igual a 180 €. Ordena el resultat, en primer lloc, pel preu (en ordre descendent) i, en segon lloc, pel nom (en ordre ascendent).
33. Retorna un llistat amb el codi i el nom de fabricant, solament d'aquells fabricants que tenen productes associats en la base de dades.
34. Retorna un llistat de tots els fabricants que existeixen en la base de dades, juntament amb els productes que té cadascun d'ells. El llistat haurà de mostrar també aquells fabricants que no tenen productes associats.
35. Retorna un llistat on només apareguin aquells fabricants que no tenen cap producte associat.
36. Retorna tots els productes del fabricador Lenovo. (Sense utilitzar INNER JOIN).
37. Retorna totes les dades dels productes que tenen el mateix preu que el producte més car del fabricant Lenovo. (Sense usar INNER JOIN).
38. Llista el nom del producte més car del fabricant Lenovo.
39. Llista el nom del producte més barat del fabricant Hewlett-Packard.
40. Retorna tots els productes de la base de dades que tenen un preu major o igual al producte més car del fabricant Lenovo.
41. Llesta tots els productes del fabricant Asus que tenen un preu superior al preu mitjà de tots els seus productes.


