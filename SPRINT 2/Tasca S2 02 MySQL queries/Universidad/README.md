[![EN](https://img.shields.io/badge/EN-blue.svg)](#eng)
[![ES](https://img.shields.io/badge/ES-red.svg)](#es)
[![CAT](https://img.shields.io/badge/CAT-yellow.svg)](#cat)


<a name="eng"></a>

[EN] 📍 University Database
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
[ES] 📍 Base de datos Universidad
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
[CAT] 📍 Base de dades Universitat
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


