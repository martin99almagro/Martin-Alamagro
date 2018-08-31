# Integrantes:
Martin-Almagro

# Negocio:
Administrador-de-proyectos.


# ENDPOINTS. 
Cod-err:404, 415

get /proyectos 

get /proyectos/id 

get /proyectos/id/tareas 

get /proyectos/id/tareas/id

get /proyectos/id/tareas/id/empleados

get /empleados

get /empleados/id

Cod-err:404, 405, 403

delete /proyectos/id

delete /proyectos/id/tareas/id

delete /empleados/ID

delete /proyectos/id/tareas/id/empleados/id

Cod-err: 411, 405, 403

post /proyectos/id

post /proyectos/id/tareas/id

post /empleados/id

post /proyectos/id/tareas/id/empleados/id

Cod-err:404, 405, 411, 403

put /proyectos/id

put /proyectos/id/tareas/id

put /empleados/id

# ENTIDADES
PROYECTO:

Id
Nombre
Fecha-de-inicio
Fecha-de-entrega
Costo-Total

TAREA:
Id
Nombre
Tiempo-estimado
Tiempo-realizado
Costo
Id-Proyecto

EMPLEADO:
DNI
Nombre
Apellido
Costo_horas
Id-Tarea
Id_Proyecto
