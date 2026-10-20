Proyecto 1: Lista de Tareas

Descripción

Este proyecto consiste en una aplicación web para administrar tareas personales, desarrollada con HTML, CSS y TypeScript utilizando la arquitectura MVC (Modelo, Vista y Controlador).

La aplicación permite registrar tareas, consultar la información, buscar tareas, cambiar su estado y eliminarlas. También permite organizar las tareas mediante prioridades y fechas límite, facilitando su administración.

Funcionalidades

- Agregar tareas con título y descripción.
- Mostrar las tareas registradas.
- Marcar tareas como pendientes o completadas.
- Buscar tareas por su título.
- Eliminar tareas.
- Asignar prioridad alta, media o baja.
- Establecer fechas límite.
- Validar los datos antes de registrar una tarea.
- Guardar las tareas en localStorage para conservar la información al recargar la página.
- Consultar estadísticas de las tareas, si están habilitadas en la versión entregada.

Tecnologías utilizadas

- HTML
- CSS
- TypeScript
- Vite
- localStorage

Instrucciones de ejecución

1. Clonar el repositorio

git clone URL_DE_TU_REPOSITORIO

2. Ingresar a la carpeta del proyecto

cd lista-tareas

3. Instalar las dependencias

npm install

4. Ejecutar la aplicación

npm run dev

5. Abrir el proyecto

Después de ejecutar el comando anterior, abrir en el navegador la dirección que aparece en la terminal, normalmente "http://localhost:5173/".

Estructura del proyecto

- "index.html": contiene la estructura principal de la aplicación.
- "src/main.ts": inicia la aplicación.
- "src/models/Tarea.ts": define la información de las tareas.
- "src/views/TareaView.ts": muestra las tareas en la interfaz.
- "src/controllers/TareaController.ts": administra las acciones del usuario.
- "src/services/StorageService.ts": gestiona el almacenamiento de las tareas.
- "src/styles/styles.css": contiene los estilos de la aplicación.
- "capturas/": contiene las evidencias del funcionamiento del proyecto.

Evidencias del proyecto

En esta sección se incluyen capturas de pantalla que muestran la interfaz y las funcionalidades implementadas en la aplicación.

captura 1 : Pantalla principal 
<img width="1917" height="961" alt="1" src="https://github.com/user-attachments/assets/34b71ce5-0f90-4bf3-87d3-ab9731f66866" />

captura 2 :  Registar una tarea 
<img width="1407" height="737" alt="image" src="https://github.com/user-attachments/assets/582decac-8d21-4052-bfa7-faaf7d23fe54" />


captura 3 : lista de tareas registradas 
<img width="1511" height="672" alt="captura 3" src="https://github.com/user-attachments/assets/961b944b-2072-4629-a80d-76dbefcd8a60" />

captura 4 : Prioridades y fechas limites 
<img width="1317" height="961" alt="image" src="https://github.com/user-attachments/assets/b6d0b76b-7522-4ff4-911a-d7245e10af83" />






Conclusión

Con este proyecto se aplica la arquitectura MVC para organizar el código y separar la información, la interfaz y la lógica de funcionamiento. Además, se practica el uso de TypeScript y el almacenamiento local para desarrollar una aplicación web funcional.
