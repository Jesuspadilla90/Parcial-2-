Proyecto 1: Lista de Tareas

Descripción

Aplicación web desarrollada con HTML, CSS y TypeScript utilizando la arquitectura MVC (Modelo, Vista y Controlador). Permite administrar tareas personales de forma organizada, registrando títulos, descripciones, prioridades y fechas límite.

Funcionalidades

- Registrar tareas con título y descripción.
- Consultar las tareas registradas.
- Marcar tareas como pendientes o completadas.
- Buscar tareas por su título.
- Eliminar tareas.
- Asignar prioridades: alta, media y baja.
- Establecer fechas límite.
- Validar los datos antes de registrar una tarea.
- Guardar la información mediante localStorage.
- Filtrar y organizar las tareas según las opciones implementadas en la aplicación.

Tecnologías utilizadas

- HTML5
- CSS3
- TypeScript
- Node.js y npm
- Vite
- localStorage

Requisitos

- Tener instalado Node.js.
- Tener instalado Git.
- Contar con un navegador web.

Instrucciones de ejecución

1. Clonar el repositorio

git clone URL_DE_TU_REPOSITORIO

2. Entrar a la carpeta del proyecto

cd lista-tareas

3. Instalar las dependencias

npm install

4. Ejecutar la aplicación

npm run dev

5. Abrir la aplicación

Abrir en el navegador la dirección que aparece en la terminal, normalmente:

"http://localhost:5173/"

Estructura del proyecto

- "index.html": estructura principal de la aplicación.
- "src/main.ts": punto de entrada.
- "src/models/Tarea.ts": modelo de las tareas.
- "src/views/TareaView.ts": vista de la aplicación.
- "src/controllers/TareaController.ts": controla las acciones y la interacción.
- "src/services/StorageService.ts": administra el almacenamiento de datos.
- "src/styles/styles.css": estilos de la aplicación.
- "capturas/": evidencias del funcionamiento del proyecto.
<img width="720" height="1610" alt="image" src="https://github.com/user-attachments/assets/4ad16226-a643-4e14-bfc0-1adfca30ad54" />


Autor

Proyecto académico desarrollado para la asignatura correspondiente.
