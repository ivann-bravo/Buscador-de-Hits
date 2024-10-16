# Buscador-de-Hits
Trabajo práctico cuatrimestral que formó parte de la evaluación final de la materia <strong>Seminario de Lenguajes</strong> - Orientado a aplicaciones móviles. Se trabajó con *Kotlin*.

### Login - Register - Logout
El usuario se debe registrar para poder acceder a la app. Al iniciar sesión se valida que el usuario esté registrado, en caso de que no lo esté, mostrará un error de credenciales incorrectas. También, puede recordar los datos de inicio de sesión para futuras visitas. Al hacer esto, se envía una notificación dando aviso de que las credenciales del usuario han sido recordadas.

### Búsqueda de Hits
Dentro de esta pantalla podemos buscar a nuestro artista favorito y nos aparecerá su canción más escuchada. Esto lo logramos gracias a consumir la [API de Genius](https://docs.genius.com), que nos da una lista de artistas con sus hits. En nuestro caso solo tomamos el primer elemento de la lista de hits.
Mostramos en pantalla el nombre de la canción, la fecha de lanzamiento y su portada.


### Mostrar álbumes
Esta pantalla pertenece a la primer entrega del trabajo, muestra albumes de la banda Radiohead con datos locales, sin consumir ninguna API.