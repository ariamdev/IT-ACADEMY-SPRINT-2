[![EN](https://img.shields.io/badge/EN-blue.svg)](https://github.com/ariamdev/IT-ACADEMY-SPRINT-2/blob/main/SPRINT%202/Tasca%20S2%2001%20%20Estructura%20de%20dades%20-%20MySQL/README.md)
[![ES](https://img.shields.io/badge/ES-red.svg)](https://github.com/ariamdev/IT-ACADEMY-SPRINT-2/blob/main/SPRINT%202/Tasca%20S2%2001%20%20Estructura%20de%20dades%20-%20MySQL/README.es.md)


**1. Estructura de dades - MySQL**
=

Aprendre a modelar bases de dades SQL.


>**Com s'organitzen les activitats?**
>
>Cada tema conté 3 nivells de dificultat. A major nivell, major dificultat. Així mateix, un mateix nivell pot contenir més d'un exercici.


🌟 Nivell 1
-

#### 📍 [Exercici 1 - Òptica](https://github.com/ariamdev/IT-ACADEMY-SPRINT-2/tree/main/SPRINT%202/Tasca%20S2%2001%20%20Estructura%20de%20dades%20-%20MySQL/n1exercici1)
Una òptica, anomenada “Cul d'Ampolla”, vol informatitzar la gestió dels clients/es i vendes d'ulleres.

En primer lloc, l'òptica vol saber quin és el proveïdor de cadascuna de les ulleres. En concret vol saber de cada proveïdor:
+ El nom
+ L'adreça (carrer, número, pis, porta, ciutat, codi postal i país)
+ Telèfon
+ Fax
+ NIF.

La política de compres de l'òptica es basa que les ulleres d'una marca es compraran a un únic proveïdor (així en podrà treure més bons preus), 
però poden comprar ulleres de diverses marques a un proveïdor. De les ulleres vol saber:
+ La marca.
+ La graduació de cadascun dels vidres.
+ El tipus de muntura (flotant, pasta o metàl·lica).
+ El color de la muntura.
+ El color de cada vidre.
+ El preu.

Dels clients/es vol emmagatzemar:
+ El nom.
+ L'adreça postal.
+ El telèfon.
+ El correu electrònic.
+ La data de registre.
+ Quan arriba un/a client/a nou, emmagatzemar el/la client/a que li ha recomanat l'establiment (sempre que algú li hagi recomanat).

El nostre sistema haurà d’indicar qui ha sigut l’empleat/da que ha venut cada ullera.

#### 📍 [Exercici 2 - Pizzeria](https://github.com/ariamdev/IT-ACADEMY-SPRINT-2/tree/main/SPRINT%202/Tasca%20S2%2001%20%20Estructura%20de%20dades%20-%20MySQL/n1exercici2#cat)
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

⭐🌟Nivell 2
-

#### 📍 [Exercici 1 - YouTube](https://github.com/ariamdev/IT-ACADEMY-SPRINT-2/tree/main/SPRINT%202/Tasca%20S2%2001%20%20Estructura%20de%20dades%20-%20MySQL/n2exercici1)
Tractarem de fer un model senzill de com seria la base de dades per a una versió reduïda de YouTube.

De cada usuari/ària guardem un identificador únic:
+ Email.
+ Password.
+ Nom d'usuari/ària.
+ Data de naixement.
+ Sexe.
+ País.
+ Codi postal.


Un usuari/ària publica vídeos. De cada vídeo guardem un identificador únic:
+ Un títol.
+ Una descripció.
+ Una grandària.
+ El nom de l'arxiu de vídeo.
+ Durada del vídeo.
+ Un thumbnail.
+ El nombre de reproduccions.
+ El número de likes.
+ El número de dislikes.

Un vídeo pot tenir tres estats diferents: públic, ocult i privat. 
Un vídeo pot tenir moltes etiquetes. Una etiqueta s'identifica per un identificador únic i un nom d'etiqueta. 
Interessa guardar qui és l'usuari/ària que publica el vídeo i en quina data/hora el fa.

Un usuari/ària pot crear un canal. Un canal té un identificador únic:
+ Un nom.
+ Una descripció.
+ Una data de creació.


Un usuari/ària es pot subscriure als canals d'altres usuaris/es. 
Un usuari/ària pot donar-li un like o un dislike a un vídeo una única vegada. 
Caldrà portar un registre dels usuaris/es que li han donat like i dislike a un determinat vídeo i en quina data/hora ho van fer.


Un usuari/ària pot crear playlists amb els vídeos que li agraden. Cada playlist té un identificador únic:
+ Un nom.
+ Una data de creació.
+ Un estat que indica que pot ser pública o privada.


Un usuari/ària pot escriure comentaris en un vídeo determinat. Cada comentari està identificat per un identificador únic:
+ El text del comentari.
+ La data/hora en la qual es va realitzar.


Un usuari/ària pot marcar un comentari com m'agrada o no m'agrada. 
Caldrà portar un registre dels usuaris/es que han marcat un comentari com m'agrada/no m'agrada, i en quina data/hora ho van fer.

