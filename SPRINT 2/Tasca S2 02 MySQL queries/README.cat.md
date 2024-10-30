[![ES](https://img.shields.io/badge/ES-red.svg?logo=googletranslate&logoColor=white)](https://github.com/ariamdev/IT-ACADEMY-SPRINT-2/blob/main/SPRINT%202/Tasca%20S2%2002%20MySQL%20queries/README.es.md)
[![EN](https://img.shields.io/badge/EN-blue.svg?logo=googletranslate&logoColor=white)](https://github.com/ariamdev/IT-ACADEMY-SPRINT-2/blob/main/SPRINT%202/Tasca%20S2%2002%20MySQL%20queries/README.md)

2.MySQL queries 
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

