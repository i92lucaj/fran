## Modificar un proyecto existente

**ID:** 02.
**Descripción:** Se modifican los datos de un proyecto y el sistema lo almacena.

**Actores principales:** Administrador.

**Precondiciones:**
* Qué exista algún proyecto en el sistema.


**Flujo principal:**
1. El administrador desea modificar los datos de un proyecto.
2. El administrador abre el cuadro de diálogo de modificar proyecto.
3. El administrador introduce el nombre o el id de un proyecto para buscarlo.
4. El sistema comprueba que existe un proyecto con ese nombre o id.
5. El administrador introduce los nuevos datos del nuevo proyecto.
6. El sistema comprueba que no exista otro proyecto con los nuevos datos.
7. El sistema almacena la información del proyecto en la base de datos.
8. El sistema muestra por pantalla que el proyecto se ha modificado. 

**Postcondiciones:**
* Un proyecto se ha modificado.
* Se muestran al administrador si la operación llevada a cabo ha tenido éxito o no.

**Flujos alternativos:**
4.a. Si no existe un proyecto con esos datos se muestra un mensaje de error.
6.a. Si existe ya un proyecto con los nuevos datos se muestra un mensaje de error.