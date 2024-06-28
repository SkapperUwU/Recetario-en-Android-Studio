# Recetario en Android Studio con Java

¡Bienvenido a Recetario! Esta aplicación te permite gestionar tus recetas de cocina de manera sencilla y eficiente. Puedes agregar, actualizar, buscar y listar recetas con ingredientes dinámicos, todo sincronizado en tiempo real con Firebase Firestore.

## Caracteristicas

- Listar recetas: Visualiza todas tus recetas almacenadas en una lista.
- Buscar recetas: Utiliza el buscador para encontrar recetas por nombre en tiempo real.
- Agregar recetas: Añade nuevas recetas con nombres, preparaciones y una lista dinámica de ingredientes.
- Actualizar recetas: Modifica recetas existentes y actualiza su información.
- Eliminar recetas: Elimina recetas que ya no necesitas.

## Tecnologías utilizadas

- Firebase Firestore: Almacenamiento y sincronización en tiempo real de datos.
- Android SDK: Desarrollo de la aplicación nativa para Android.
- Java: Lenguaje de programación principal.
- XML: Diseño de la interfaz de usuario.

## Funcionalidades

### Listar recetas

Al abrir la aplicación, serás recibido con una lista de todas las recetas almacenadas en Firebase Firestore. Cada receta muestra el nombre y opciones para ver detalles, actualizar o eliminar.

<img src="https://github.com/SkapperUwU/Recetario-en-Android-Studio/assets/89941725/d0780dc6-ec5c-4fdf-bdbb-4761dd9e598c" alt="Main activity" height="350">

### Buscar Recetas

Utiliza la barra de búsqueda en la parte superior de la pantalla principal para encontrar recetas por su nombre. La búsqueda se realiza en tiempo real, mostrando los resultados instantáneamente. 

<img src="https://github.com/SkapperUwU/Recetario-en-Android-Studio/assets/89941725/4c7f4280-8e34-4a3b-ba72-5938b997389d" alt="Buscador" height="200">
<img src="https://github.com/SkapperUwU/Recetario-en-Android-Studio/assets/89941725/746964f2-0e03-4705-8277-b723d0f68b78" alt="Buscador con texto" height="200">

### Agregar Recetas

Para agregar una nueva receta, toca el botón de agregar (Nueva receta...). Se abrirá un formulario donde puedes ingresar el nombre de la receta, una imagen, añadir ingredientes dinámicamente y la preparación.

<img src="https://github.com/SkapperUwU/Recetario-en-Android-Studio/assets/89941725/1bc2e24b-3911-4dc4-9ab4-42bef4dc8792" alt="Agregar nueva receta" height="350">

### Actualizar Recetas

Puedes actualizar una receta existente tocando el botón de editar (ícono de lápiz) en la lista de recetas. Esto abrirá el mismo formulario utilizado para agregar recetas, pero pre-poblado con la información actual de la receta seleccionada. Realiza tus cambios y guarda para actualizar la receta en Firestore.

<img src="https://github.com/SkapperUwU/Recetario-en-Android-Studio/assets/89941725/d865d0e0-6c94-4095-9f2a-524ec8e99c73" alt="Actualizar receta" height="350">

### Eliminar Recetas

Para eliminar una receta, toca el botón de eliminar (ícono de papelera) junto a la receta en la lista. Se te pedirá que confirmes la eliminación. Una vez confirmado, la receta se eliminará de Firestore.

<img src="https://github.com/SkapperUwU/Recetario-en-Android-Studio/assets/89941725/774ce035-ada9-4ea1-87f9-7530742fd158" alt="Actualizar receta" height="150">

### Ver Detalles de Recetas
Puedes ver los detalles completos de una receta tocando el botón de ver detalles (ícono de ojo) en la lista de recetas. Esto abrirá una nueva pantalla mostrando toda la información de la receta, incluyendo la lista completa de ingredientes y la preparación.

<img src="https://github.com/SkapperUwU/Recetario-en-Android-Studio/assets/89941725/9b7deb9c-c5c2-4ae0-ad66-48ddb7b47f00" alt="Actualizar receta" height="400">

## Información Adicional

Este proyecto ha sido desarrollado por estudiantes como parte de un trabajo escolar, por lo que aun es suceptible a errores. El objetivo principal es aprender y demostrar competencias en el desarrollo de aplicaciones móviles utilizando Firebase Firestore para el almacenamiento y sincronización de datos en tiempo real.

### Desarrolladores:
Rodriguez Monroy Ariana Estefania  
Jimenez Estrada Jesus  
Cruz Martinez Evelin Lizet

***Tecnologico de Estudios Superiores Oriente del Estado de México***  
***Ingenieria en Sistemas Computacionales***  
***8S12***

