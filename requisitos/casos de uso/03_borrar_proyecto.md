## Eliminar un proyecto.

**ID:** 03.
**Descripción:** Se elimina un proyecto de la base de datos.

**Actores principales:** Administrador.

**Precondiciones:**
* Qué haya algún proyecto en la base de datos.


**Flujo principal:**
1. El administrador desea eliminar un proyecto de la base de datos del sistema.
1. El administrador abre el cuadro de diálogo de eliminar un proyecto de la base de datos.
1. El administrador busca y localiza el proyecto cuyos datos de van a eliminar.
1. El administrador confirma en el cuadro de diálogo entrante de qué quiere eliminar.
1. El sistema borra de la base de datos del propio sistema el proyecto. 

**Postcondiciones:**
* Que se haya efectuado el cambio correctamente.
* Que no se encuentre el proyecto en la base de datos.
 
**Flujos alternativos:**
4.a. Si el proyecto no existe, se muestra un mensaje de error.
5.a. Si el administrador cancela la eliminación de dicho proyecto de la base de datos, se vuelve al menú principal.
