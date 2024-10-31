[![ES](https://img.shields.io/badge/ES-red.svg?logo=googletranslate&logoColor=white)](https://github.com/ariamdev/IT-ACADEMY-SPRINT-2/blob/main/SPRINT%202/Tasca%20S2%2002%20MySQL%20queries/README.es.md)
[![CAT](https://img.shields.io/badge/CAT-yellow.svg?logo=googletranslate&logoColor=white)](https://github.com/ariamdev/IT-ACADEMY-SPRINT-2/blob/main/SPRINT%202/Tasca%20S2%2002%20MySQL%20queries/README.cat.md)


2.MySQL queries 
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

