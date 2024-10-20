[![EN](https://img.shields.io/badge/EN-blue.svg)](#eng)
[![ES](https://img.shields.io/badge/ES-red.svg)](#es)
[![CAT](https://img.shields.io/badge/CAT-yellow.svg)](#cat)


<a name="eng"></a>
⭐🌟 Level 2
-

#### [EN] 📍 Exercise 1 - YouTube
We will try to make a simple model of what the database would be like for a reduced version of YouTube.

From each user we save a unique identifier:
+ Email.
+ Password.
+ Username.
+ Date of birth.
+ Gender.
+ Country.
+ Postal code.


A user publishes videos. From each video we save a unique identifier:
+ A title.
+ A description.
+ A size.
+ The name of the video archive.
+ Duration of the video.
+ A thumbnail.
+ The number of reproductions.
+ The likes number.
+ The dislike number.

A video can have three different states: public, hidden and private. A video can have many tags. A label is identified by a unique identifier and a tag name.
It is interesting to save who is the user who publishes the video and on what date / time he does it.

A user can create a channel. A channel has a unique identifier:
+ A name.
+ A description.
+ A date of creation.


A user can subscribe to the channels of other users. A user can give a like or dislike to a video once. 
It will be necessary to bring a record of the users who have given like and dislike to a certain video and on what date/time they did it.


A user can create playlists with the videos they like. Each playlist has a unique identifier:
+ A name.
+ A date of creation.
+ A state that indicates that it can be public or private.


A user can write comments in a given video. Each comment is identified by a unique identifier:
+ The text of the comment.
+ The date/time at which it was made.


A user can mark a comment as I like it or not. You will have to bring a record of the users who have marked a comment as I like it or not, 
and on what date/time they did.

---

<a name="es"></a>
⭐🌟Nivel 2
-

#### [ES] 📍 Ejercicio 1 - YouTube
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

---

<a name="cat"></a>
⭐🌟Nivell 2
-

#### [CAT] 📍 Exercici 1 - YouTube
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

