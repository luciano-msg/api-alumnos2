# api-alumnos

Taller 2 - Serverless (CS2032 Cloud Computing - UTEC 2026-2)

API REST serverless con 5 lambdas (CRUD de alumnos) desplegadas en AWS Lambda + API Gateway con Serverless Framework.

## Lambdas

- `ListarAlumnos.py` - POST /alumnos/listar
- `CrearAlumno.py` - POST /alumnos/crear
- `BuscarAlumno.py` - POST /alumnos/buscar
- `ModificarAlumno.py` - POST /alumnos/modificar
- `EliminarAlumno.py` - POST /alumnos/eliminar

## Deploy

```
serverless deploy
```
