# API REST

## Descripción
Esta API permite gestionar usuarios y autenticación dentro del sistema.

## Endpoints

### GET /users
Obtiene la lista de todos los usuarios registrados.

**Respuesta:**
```json
{
  "status": "success",
  "data": [
    {
      "id": 1,
      "name": "Juan"
    }
  ]
}
