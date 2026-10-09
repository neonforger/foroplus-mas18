# foroplus-mas18

Lista pública de hilos etiquetados (`+18`, `+16`, `+14`, `+prv`, `+hd`) de ForoCoches que usa la
sección opcional "+18" de [ForoPlus](https://github.com/neonforger/foroplus).

- **Rama `datos`**: `paginas/N.json`, 50 hilos por página, en el formato descrito en el código de
  la app (`PaginaMas18.kt`). Es lo único que descarga la app, y solo si el usuario activa la
  sección (viene apagada).
- **Qué hay en cada hilo**: id, título, autor, número de respuestas y etiquetas. Todo es lo que el
  foro ya enseña públicamente; aquí no hay nada de los usuarios de la app.
- **De dónde sale**: un lector de ForoPlus lee el foro como invitado, despacio y respetando sus
  límites. La app no se conecta a ese servidor: solo descarga estos ficheros de GitHub.
