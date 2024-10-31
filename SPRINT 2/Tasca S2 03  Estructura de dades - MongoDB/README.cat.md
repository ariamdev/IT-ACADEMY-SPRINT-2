[![EN](https://img.shields.io/badge/EN-blue.svg?logo=googletranslate&logoColor=white)](https://github.com/ariamdev/IT-ACADEMY-SPRINT-2/blob/main/SPRINT%202/Tasca%20S2%2003%20%20Estructura%20de%20dades%20-%20MongoDB/README.md)
[![ES](https://img.shields.io/badge/ES-red.svg?logo=googletranslate&logoColor=white)](https://github.com/ariamdev/IT-ACADEMY-SPRINT-2/blob/main/SPRINT%202/Tasca%20S2%2003%20%20Estructura%20de%20dades%20-%20MongoDB/README.es.md)

3.Estructura de dades - MongoDB
=

Aprendre a modelar bases de dades NoSQL.


>**Com s'organitzen les activitats?**
>
>Cada tema conté 3 nivells de dificultat. A major nivell, major dificultat. Així mateix, un mateix nivell pot contenir més d'un exercici.


🌟 Nivell 1
-

Una òptica, anomenada “Cul d'Ampolla”, vol informatitzar la gestió dels clients/es i vendes d'ulleres.

En primer lloc, l'òptica vol saber quin és el proveïdor de cadascuna de les ulleres. 

- En concret vol saber de cada proveïdor: El nom, l'adreça (carrer, número, pis, porta, ciutat, codi postal i país), telèfon, fax, NIF.
- De les ulleres es vol saber: La marca, la graduació de cadascun dels vidres, el tipus de muntura (flotant, pasta o metàl·lica), el color de la muntura, el color de cada vidre i el preu.
- Dels clients/es vol emmagatzemar: El nom, l'adreça postal, el telèfon, el correu electrònic, la data de registre.
- Quan arriba un/a client/a nou, emmagatzemar el/la client/a que li ha recomanat l'establiment (sempre que algú li hagi recomanat).
- El nostre sistema haurà d’indicar qui ha sigut l’empleat/da que ha venut cada ullera. Defineix quin dia/hora es realitza la venda.

#### 📍 [Exercici 1](https://github.com/ariamdev/IT-ACADEMY-SPRINT-2/tree/main/SPRINT%202/Tasca%20S2%2003%20%20Estructura%20de%20dades%20-%20MongoDB/Nivell%201/Exercici1)

Imagina que tenim la següent interfície gràfica, des del punt de vista d’un client de l'Òptica. Com dissenyaries la base de dades que facilités la informació?

![opticaSQL](https://github.com/user-attachments/assets/5d6b4ba8-0394-4bae-b1fa-5a032e164001)

#### 📍 [Exercici 2](https://github.com/ariamdev/IT-ACADEMY-SPRINT-2/tree/main/SPRINT%202/Tasca%20S2%2003%20%20Estructura%20de%20dades%20-%20MongoDB/Nivell%201/Exercici2)

I si el punt de vista fos de la interfície fossin les ulleres?

![opticaSQL2](https://github.com/user-attachments/assets/d6b684f2-1e6d-4a0b-a530-c205e3979bcb)

⭐🌟 Nivell 2
-

#### 📍 [Exercici 1](https://github.com/ariamdev/IT-ACADEMY-SPRINT-2/tree/main/SPRINT%202/Tasca%20S2%2003%20%20Estructura%20de%20dades%20-%20MongoDB/Nivell%202/Exercici1)

T’han contractat per a dissenyar una web que permeti fer comandes de menjar a domicili per Internet.

Tingues en compte les següents indicacions per a modelar com seria la base de dades del projecte:

- Per a cada client/a emmagatzemem un identificador únic: Nom, cognoms, adreça, codi postal, localitat, província, número de telèfon.
- Una persona pot realitzar moltes comandes, però una única comanda només pot ser realitzat per una única persona. De cada comanda s'emmagatzema un identificador únic: Data/hora de realització, si la comanda és per a repartiment a domicili o per a recollir en botiga, la quantitat de productes que s'han seleccionat de cada tipus, el preu total a més d’una nota amb informació addicional.

Una comanda pot constar d'un o diversos productes.

- Els productes poden ser pizzes, hamburgueses i begudes.
- De cada producte s'emmagatzema un identificador únic: Nom, descripció, imatge, preu. En el cas de les pizzes existeixen diverses categories que poden anar canviant de nom al llarg de l'any.

Una comanda és gestionada per una única botiga i una botiga pot gestionar moltes comandes.

- De cada botiga s'emmagatzema un identificador únic: Adreça, codi postal, localitat, província.
- En una botiga poden treballar molts empleats/des i un empleat/da només pot treballar en una botiga. De cada empleat/da, s'emmagatzema un identificador únic: Nom, cognoms, NIF, Telèfon, si treballa com a cuiner/a o repartidor/a.
- Per a les comandes de repartiment a domicili interessa guardar qui és el repartidor/a que fa el lliurament de la comanda i la data/hora del moment del lliurament.

 ![image](https://github.com/user-attachments/assets/10322547-898c-47f0-8d02-4e52e1385ffb)
