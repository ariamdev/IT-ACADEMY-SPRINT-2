[![ES](https://img.shields.io/badge/ES-red.svg?logo=googletranslate&logoColor=white)](https://github.com/ariamdev/IT-ACADEMY-SPRINT-2/blob/main/SPRINT%202/Tasca%20S2%2002%20MySQL%20queries/README.es.md)
[![CAT](https://img.shields.io/badge/CAT-yellow.svg?logo=googletranslate&logoColor=white)](https://github.com/ariamdev/IT-ACADEMY-SPRINT-2/blob/main/SPRINT%202/Tasca%20S2%2002%20MySQL%20queries/README.cat.md)


<a name="eng"></a>
2. MySQL queries 
=

Learning to query a SQL database.

>**How are the activities organized?**
>
>Each theme contains 3 levels of difficulty. The higher the level, the greater the difficulty. Likewise, the same level may contain more than one exercise.
>
>🌟**Level 1**
>
>You will certify your level 1 if you build 37 correct queries, 20 of which must be from the University diagram.
>
>⭐🌟**Level 2**
>
>You will have level 2 if you build between 37 and 56 correct queries, 20 of which will have to be from the University diagram.
>
>⭐⭐🌟**Level 3**
>
>Level 3 if you manage to correctly build more than 56 correct queries (20 of them must be from the University diagram).


📍 [Store Database](https://github.com/ariamdev/IT-ACADEMY-SPRINT-2/tree/main/SPRINT%202/Tasca%20S2%2002%20MySQL%20queries/Tienda)
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

📍 [University Database](https://github.com/ariamdev/IT-ACADEMY-SPRINT-2/tree/main/SPRINT%202/Tasca%20S2%2002%20MySQL%20queries/Universidad)
-

Please download the database of the schema universidad.sql file, view the E-R diagram in an editor and make the following queries:

1. Returns a list with the first surname, second surname and the name of all students. The list must be sorted alphabetically from minor to major by the first surname, second surname and name.
2. Find the name and two surnames of the students who have not registered their phone number in the database.
3. Returns the list of students who were born in 1999.
4. Returns the list of teachers who have not registered their telephone number in the database and also their NIF ends in K.
5. Returns the list of the subjects taught in the first semester, in the third year of the degree that has the identifier 7.
6. Returns a list of teachers together with the name of the department to which they are linked. The list must return four columns, first surname, second surname, name and name of the department. The result will be sorted alphabetically from minor to major by surnames and name.
7. Return a list with the name of the subjects, year of start and year of end of the school year of the student with NIF 26902806M.
8. Returns a list with the name of all the departments that have teachers who teach a subject in the Degree in Computer Engineering (Pla 2015).
9. Returns a list with all students who have enrolled in a subject during the 2018/2019 school year.

Resolve the following 6 queries using LEFT JOIN and RIGHT JOIN clauses.

1. Returns a list with the names of all the teachers and the departments they have linked. The list must also show those teachers who do not have any associated department. The list must return four columns, department name, first surname, second surname and teacher name. The result will be sorted alphabetically from minor to major by the department name, surnames and name.
2. Returns a list with teachers who are not associated with a department.
3. Returns a list with departments that do not have associate professors.
4. Returns a list with teachers who do not teach any subject.
5. Returns a list of subjects that do not have an assigned teacher.
6. Returns a list with all departments that have not taught courses in any school year.

Summary queries:

1. Returns the total number of students.
2. Calculates how many students were born in 1999.
3. Calculates how many teachers there are in each department. The result must only show two columns, one with the name of the department and the other with the number of teachers in this department. The result must only include departments that have associate professors and must be ranked from greater to lower by the number of teachers.
4. Return a list with all departments and the number of teachers in each of them. Keep in mind that there may be departments that do not have associate professors. These departments must also appear on the list.
5. Returns a list with the name of all existing degrees in the database and the number of subjects each has. Note that there may be degrees that do not have associated subjects. These degrees must also appear in the list. The result must be sorted from highest to lowest by the number of subjects.
6. Returns a list with the name of all the existing degrees in the database and the number of subjects that each one has, of the degrees that have more than 40 associated subjects.
7. Returns a list showing the name of the degrees and the sum of the total number of credits available for each type of subject. The result must have three columns: name of the degree, type of subject and the sum of the credits of all the subjects that are of this type.
8. Returns a list showing how many students have enrolled for a subject in each of the school courses. The result will have to show two columns, one column with the start year of the school year and the other with the number of students enrolled.
9. Returns a list of the number of subjects taught by each teacher. The list must take into account those teachers who do not teach any subject. The result will show five columns: id, name, first surname, second surname and number of subjects. The result will be sorted from major to minor by the number of subjects.
10. Returns all the data of the youngest student.
11. Returns a list with teachers who have an associated department and do not teach any subject.

---

<a name="es"></a>
2. MySQL queries 
=

Aprender a consultar una base de datos SQL.

>**Como se organizan las actividades?**
>
>Cada tema contiene 3 niveles de dificultad. A mayor nivel, mayor dificultad. Así mismo, un mismo nivel puede contener más de un ejercicio.
>
>🌟Nivel 1
>
>Si construyes 37 consultas correctas, 20 de las cuales tendrán que ser del diagrama Universidad.
>
>⭐🌟Nivel 2
>
>Tendrás nivel 2 si construyes entre 37 y 56 consultas correctas, 20 de las cuales tendrán que ser del diagrama Universidad.
>
>⭐⭐🌟Nivel 3
>
>Nivel 3 si consigues construir correctamente más de 56 consultas correctas (20 de ellas tendrán que ser del diagrama Universidad)


📍 [Base de datos Tienda](https://github.com/ariamdev/IT-ACADEMY-SPRINT-2/tree/main/SPRINT%202/Tasca%20S2%2002%20MySQL%20queries/Tienda)
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

📍 [Base de datos Universidad](https://github.com/ariamdev/IT-ACADEMY-SPRINT-2/tree/main/SPRINT%202/Tasca%20S2%2002%20MySQL%20queries/Universidad)
-

Por favor, descarga la base de datos del fichero *schema_*universidad.*sql, visualiza el diagrama E-R en un editor y efectúa las siguientes consultas:

1. Devuelve un listado con el primer apellido, segundo apellido y el nombre de todos los/las alumnos. El listado tendrá que estar ordenado alfabéticamente de menor a mayor por el primer apellido, segundo apellido y nombre.
2. Averigua el nombre y los dos apellidos de los alumnos que no han dado de alta su número de teléfono en la base de datos.
3. Devuelve el listado de los alumnos que nacieron en 1999.
4. Devuelve el listado de profesores/se que no han dado de alta su número de teléfono en la base de datos y además su NIF acaba en K.
5. Devuelve el listado de las asignaturas que se imparten en el primer cuatrimestre, en el tercer curso del grado que tiene el identificador 7.
6. Devuelve un listado de los profesores/se junto con el nombre del departamento al cual están vinculados. El listado tiene que devolver cuatro columnas, primer apellido, segundo apellido, nombre y nombre del departamento. El resultado estará ordenado alfabéticamente de menor a mayor por los apellidos y el nombre.
7. Devuelve un listado con el nombre de las asignaturas, año de inicio y año de fin del curso escolar del alumno/a con NIF 26902806M.
8. Devuelve un listado con el nombre de todos los departamentos que tienen profesores/se que imparten alguna asignatura en el Grado en Ingeniería Informática (Pla 2015).
9. Devuelve un listado con todos los alumnos que se han matriculado en alguna asignatura durante el curso escolar 2018/2019.

Resuelve las 6 siguientes consultas utilizando las cláusulas *LEFT *JOIN y *RIGHT *JOIN.

1. Devuelve un listado con los nombres de todos los profesores/se y los departamentos que tienen vinculados. El listado también tiene que mostrar aquellos profesores/se que no tienen ningún departamento asociado. El listado tiene que devolver cuatro columnas, nombre del departamento, primer apellido, segundo apellido y nombre del profesor/a. El resultado estará ordenado alfabéticamente de menor a mayor por el nombre del departamento, apellidos y el nombre.
2. Devuelve un listado con los profesores/se que no están asociados a un departamento.
3. Devuelve un listado con los departamentos que no tienen profesores/se asociados.
4. Devuelve un listado con los profesores/se que no imparten ninguna asignatura.
5. Devuelve un listado con las asignaturas que no tienen un profesor/a asignado.
6. Devuelve un listado con todos los departamentos que no han impartido asignaturas en ningún curso escolar.

Consultas resumen:

1. Devuelve el número total de alumnos que hay.
2. Calcula cuántos alumnos nacieron en 1999.
3. Calcula cuántos profesores/se hay en cada departamento. El resultado solo tiene que mostrar dos columnas, una con el nombre del departamento y otra con el número de profesores/se que hay en este departamento. El resultado solo tiene que incluir los departamentos que tienen profesores/se asociados y tendrá que estar ordenado de mayor a menor por el número de profesores/se.
4. Devuelve un listado con todos los departamentos y el número de profesores/se que hay en cada uno de ellos. Tenga en cuenta que pueden existir departamentos que no tienen profesores/se asociados. Estos departamentos también tienen que aparecer en el listado.
5. Devuelve un listado con el nombre de todos los grados existentes en la base de datos y el número de asignaturas que tiene cada uno. Ten en cuenta que pueden existir grados que no tienen asignaturas asociadas. Estos grados también tienen que aparecer en el listado. El resultado tendrá que estar ordenado de mayor a menor por el número de asignaturas.
6. Devuelve un listado con el nombre de todos los grados existentes en la base de datos y el número de asignaturas que tiene cada uno, de los grados que tengan más de 40 asignaturas asociadas.
7. Devuelve un listado que muestre el nombre de los grados y la suma del número total de créditos que hay para cada tipo de asignatura. El resultado tiene que tener tres columnas: nombre del grado, tipo de asignatura y la suma de los créditos de todas las asignaturas que hay de este tipo.
8. Devuelve un listado que muestre cuántos alumnos se han matriculado de alguna asignatura en cada uno de los cursos escolares. El resultado tendrá que mostrar dos columnas, una columna con el año de inicio del curso escolar y otra con el número de alumnos matriculados.
9. Devuelve un listado con el número de asignaturas que imparte cada profesor/a. El listado tiene que tener en cuenta aquellos profesores/se que no imparten ninguna asignatura. El resultado mostrará cinco columnas: *id, nombre, primer apellido, segundo apellido y número de asignaturas. El resultado estará ordenado de mayor a menor por el número de asignaturas.
10. Devuelve todos los datos del alumno/a más joven.
11. Devuelve un listado con los profesores/se que tienen un departamento asociado y que no imparten ninguna asignatura.

---

<a name="cat"></a>
2. MySQL queries 
=

Aprendre a consultar una base de dades SQL.

>**Com s'organitzen les activitats?**
>
>Cada tema conté 3 nivells de dificultat. A major nivell, major dificultat. Així mateix, un mateix nivell pot contenir més d'un exercici.
>
>🌟Nivell 1
>
>Certificaràs el teu nivell 1 si construeixes 37 consultes correctes, 20 de les quals hauran de ser del diagrama Universitat.
>
>⭐🌟Nivell 2
>
>Tindràs nivell 2 si construeixes entre 37 i 56 consultes correctes, 20 de les quals hauran de ser del diagrama Universitat.
>
>⭐⭐🌟Nivell 3
>
>Nivell 3 si aconsegueixes construir correctament més de 56 consultes correctes (20 d'elles hauran de ser del diagrama Universitat).

📍 [Base de dades Tenda](https://github.com/ariamdev/IT-ACADEMY-SPRINT-2/tree/main/SPRINT%202/Tasca%20S2%2002%20MySQL%20queries/Tienda)
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


📍 [Base de dades Universitat](https://github.com/ariamdev/IT-ACADEMY-SPRINT-2/tree/main/SPRINT%202/Tasca%20S2%2002%20MySQL%20queries/Universidad)
-

Si us plau, descàrrega la base de dades del fitxer schema_universidad.sql, visualitza el diagrama E-R en un editor i efectua les següents consultes:

1. Retorna un llistat amb el primer cognom, segon cognom i el nom de tots els/les alumnes. El llistat haurà d'estar ordenat alfabèticament de menor a major pel primer cognom, segon cognom i nom.
2. Esbrina el nom i els dos cognoms dels alumnes que no han donat d'alta el seu número de telèfon en la base de dades.
3. Retorna el llistat dels alumnes que van néixer en 1999.
4. Retorna el llistat de professors/es que no han donat d'alta el seu número de telèfon en la base de dades i a més el seu NIF acaba en K.
5. Retorna el llistat de les assignatures que s'imparteixen en el primer quadrimestre, en el tercer curs del grau que té l'identificador 7.
6. Retorna un llistat dels professors/es juntament amb el nom del departament al qual estan vinculats. El llistat ha de retornar quatre columnes, primer cognom, segon cognom, nom i nom del departament. El resultat estarà ordenat alfabèticament de menor a major pels cognoms i el nom.
7. Retorna un llistat amb el nom de les assignatures, any d'inici i any de fi del curs escolar de l'alumne/a amb NIF 26902806M.
8. Retorna un llistat amb el nom de tots els departaments que tenen professors/es que imparteixen alguna assignatura en el Grau en Enginyeria Informàtica (Pla 2015).
9. Retorna un llistat amb tots els alumnes que s'han matriculat en alguna assignatura durant el curs escolar 2018/2019.

Resol les 6 següents consultes utilitzant les clàusules LEFT JOIN i RIGHT JOIN.

1. Retorna un llistat amb els noms de tots els professors/es i els departaments que tenen vinculats. El llistat també ha de mostrar aquells professors/es que no tenen cap departament associat. El llistat ha de retornar quatre columnes, nom del departament, primer cognom, segon cognom i nom del professor/a. El resultat estarà ordenat alfabèticament de menor a major pel nom del departament, cognoms i el nom.
2. Retorna un llistat amb els professors/es que no estan associats a un departament.
3. Retorna un llistat amb els departaments que no tenen professors/es associats.
4. Retorna un llistat amb els professors/es que no imparteixen cap assignatura.
5. Retorna un llistat amb les assignatures que no tenen un professor/a assignat.
6. Retorna un llistat amb tots els departaments que no han impartit assignatures en cap curs escolar.

Consultes resum:

1. Retorna el nombre total d'alumnes que hi ha.
2. Calcula quants alumnes van néixer en 1999.
3. Calcula quants professors/es hi ha en cada departament. El resultat només ha de mostrar dues columnes, una amb el nom del departament i una altra amb el nombre de professors/es que hi ha en aquest departament. El resultat només ha d'incloure els departaments que tenen professors/es associats i haurà d'estar ordenat de major a menor pel nombre de professors/es.
4. Retorna un llistat amb tots els departaments i el nombre de professors/es que hi ha en cadascun d'ells. Tingui en compte que poden existir departaments que no tenen professors/es associats. Aquests departaments també han d'aparèixer en el llistat.
5. Retorna un llistat amb el nom de tots els graus existents en la base de dades i el nombre d'assignatures que té cadascun. Tingues en compte que poden existir graus que no tenen assignatures associades. Aquests graus també han d'aparèixer en el llistat. El resultat haurà d'estar ordenat de major a menor pel nombre d'assignatures.
6. Retorna un llistat amb el nom de tots els graus existents en la base de dades i el nombre d'assignatures que té cadascun, dels graus que tinguin més de 40 assignatures associades.
7. Retorna un llistat que mostri el nom dels graus i la suma del nombre total de crèdits que hi ha per a cada tipus d'assignatura. El resultat ha de tenir tres columnes: nom del grau, tipus d'assignatura i la suma dels crèdits de totes les assignatures que hi ha d'aquest tipus.
8. Retorna un llistat que mostri quants alumnes s'han matriculat d'alguna assignatura en cadascun dels cursos escolars. El resultat haurà de mostrar dues columnes, una columna amb l'any d'inici del curs escolar i una altra amb el nombre d'alumnes matriculats.
9. Retorna un llistat amb el nombre d'assignatures que imparteix cada professor/a. El llistat ha de tenir en compte aquells professors/es que no imparteixen cap assignatura. El resultat mostrarà cinc columnes: id, nom, primer cognom, segon cognom i nombre d'assignatures. El resultat estarà ordenat de major a menor pel nombre d'assignatures.
10. Retorna totes les dades de l'alumne/a més jove.
11. Retorna un llistat amb els professors/es que tenen un departament associat i que no imparteixen cap assignatura.


