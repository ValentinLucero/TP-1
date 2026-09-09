# Proyecto Gestor de Tareas

Este proyecto fue desarrollado como Trabajo Práctico para la materia, representando nuestros primeros pasos en JavaScript.

Fecha: 14/09/2026

# Descripción
Aplicación de consola en JavaScript que permite gestionar tareas. El sistema permite crear, buscar, modificar y cambiar el estado de distintas tareas mediante un menú interactivo.

# Contexto del trabajo
Implementamos una solución basada en recursividad, utilizando funciones que se vuelven a llamar a sí mismas dentro de los callbacks de readline.

En lugar de usar bucles tradicionales (como while), el flujo del programa se mantiene activo mediante funciones como bloqueTrabajo, que se invocan nuevamente después de cada acción del usuario. Esto permite simular un ciclo continuo de ejecución sin bloquear el programa.

# Funcionalidades principales
- Creación de tareas
- Búsqueda de tareas
- Edición de tareas
- Cambio de estado
- Visualización según estado

# Características técnicas
- Uso de Node.js para ejecución en consola
- Manejo de entradas con readline
- Uso de arrays y objetos para almacenar datos
- Validaciones de entrada del usuario
- Control del flujo mediante recursividad en callbacks

# Estructura del proyecto
- GestionTareas: Trabajo principal
- Calculadora: Segundo trabajo 
- package.json: configuración del proyecto  

# Tecnologías
- JavaScript
- Node.js

# Ejecución
Ejecutar el archivo principal con: node GestionTareas.js
