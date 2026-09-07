# Sistema de Inventario para Almacén de Barrio
Nombre: Lucas Bolaño Pérez
Asignatura: Construcción de Software

## Descripción
Aplicación web construida con React 19 y Vite para gestionar el inventario de un pequeño almacén. Permite registrar, listar, editar y eliminar productos (CRUD), manteniendo los datos persistentes en Firebase Firestore en tiempo real. La interfaz está dividida en componentes reutilizables, incluyendo un formulario, una tabla de listado y un resumen financiero del inventario.

## Instrucciones de Instalación y Ejecución

1. Clonar el repositorio.
2. Abrir la terminal en la carpeta del proyecto.
3. Instalar las dependencias ejecutando: npm install
4. Configurar las credenciales de Firebase:
   - Crear un archivo llamado .env en la raíz del proyecto.
   - Copiar el contenido del archivo .env.example hacia el nuevo archivo .env.
   - Llenar los valores en el archivo .env con las credenciales de un proyecto real de Firebase Firestore (el archivo .env no se sube al repositorio por seguridad).
5. Ejecutar el servidor de desarrollo local: npm run dev
6. Abrir la URL proporcionada en el navegador 