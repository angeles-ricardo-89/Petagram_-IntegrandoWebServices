# MyPuppy
Aplicación para curso Desarrollo de aplicaciones con Android

Se eligió como PrimaryColor CYAN #00BCD4, como AccentColor DEPP ORANGE #FF5722, de manera que DarkPrimaryColor quedó como #0097A7.

Para la semana 4 (JavaMail) el correo y password del remitente se almacenan en strings.xml en sender_mail y email_password,
reemplazar los valores por su email y password.

Debido a que hace uso de smtp es necesario que su correo (gmail) esté configurado para permitir acceso a "aplicaciones menos seguras".

# Semana 5

Para la tarea de la semana 5 (Persistencia), usé el siguiente modelo de datos:

![Alt text](/screenshots/PETAGRAM_ER.png?raw=true "ER")

No me pareció tan clara la petición del modelo de datos (una sola tabla y guardar sólo los ultimos 5), así que tomé como base la idea del ejemplo del curso, donde los likes se guardan en una tabla adicional.

la tabla pet almacena a todas las mascotas, la inserción de las mascotas se hace una sola vez al incio de la aplicación.

Cuando se están guardando los likes, se obtienen los ultimos 5 a los que se les ha dado like, del más reciente al más antiguo.

Así cuando el usuario da like (o un huesito) a la mascota, como se ve en la imagen:


![Alt text](/screenshots/Semana5_R1.png?raw=true "Huesito a Rufus")

Al ir al activity de favoritos, la mascota recién "premiada" aparecerá al principio de la lista:

![Alt text](/screenshots/Semana5_R2.png?raw=true "Rufu al principio de la lista de favoritos")

Al tener la aplicación recién instalada, no aparece nada en los favoritos, pues todos empiezan en 0.

Después de varios intentos, creo que al fin me ha quedado claro MVP.

Saludos!
