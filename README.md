# task-points-api
API WebSocket para la app de puntuación (Node.js + Socket.io)

```markdown
# Task Points API

Backend de tiempo real para la aplicación de estimación de tareas [`task-points-app`](https://github.com/jcarlosab/task-points-app). Utiliza Node.js, Express y Socket.IO.

## Funcionalidades

- Gestión de salas privadas/públicas.
- Estimaciones en tiempo real vía WebSocket.
- Expiración automática de salas inactivas.
- Logs en consola para depuración.

## Configuración

Crea un archivo `.env` con al menos:

```env
PORT=3000
EXPIRE_MINUTES=10
