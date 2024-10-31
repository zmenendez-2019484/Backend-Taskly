# Backend - Taskly

## Descripción
Taskly es una aplicación de gestión de tareas y proyectos desarrollada con Node.js y Express. Este backend proporciona una API RESTful para que los usuarios puedan crear proyectos, gestionar tareas, y colaborar en equipo mediante roles de acceso y permisos específicos.

## Funcionalidades
- **Autenticación y Autorización**: Implementación de JWT para un acceso seguro y gestión de permisos por roles.
- **Gestión de Proyectos y Tareas**: CRUD completo para proyectos y tareas, con la capacidad de añadir subtareas y organizar prioridades.
- **Enlaces de Invitación**: Los usuarios pueden invitar a otros mediante enlaces únicos para unirse a proyectos, simplificando el proceso de colaboración.
- **Roles Personalizados**: Distintos niveles de acceso para propietarios, editores y lectores en cada proyecto.

## Tecnologías Utilizadas
- **Node.js** y **Express**: API robusta y escalable.
- **MongoDB** y **Mongoose**: Base de datos NoSQL para almacenamiento flexible de datos.
- **JWT**: Manejo seguro de sesiones.
- **Helmet y Rate Limiting**: Seguridad adicional para proteger la API.
