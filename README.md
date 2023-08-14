# Proyecto turnos de centro de estética.
Este proyecto consiste en una API REST que permite la toma de turnos de un centro de estética. Las entidades presentes son usuarios, empleados, servicios y turnos.

## Pruebas
Ejecute npm install en la terminal, instalando así todas las dependencias; y luego npm start.

- Rutas base:
   - http://localhost:5300/usuarios/
    - http://localhost:5300/empleados/
    - http://localhost:5300/servicios/
    - http://localhost:5300/turnos/
      
- Visualización de los listados de cada entidad:
    - GET + ruta

- Visualización de una entidad:
    - GET + ruta + /ID

- Creación de una entidad:
    - POST + ruta

- Modificación de una entidad:
    - PUT + ruta + /ID

- Eliminación de una entidad:
    - DELETE + ruta + /ID

- Visualización del porcentaje de turnos que se encuentran disponibles:
    - GET + ruta turnos + /porcentajeTurnosDisponibles

