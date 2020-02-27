## Añadir un nuevo proyecto al sistema

**ID:** 01.
**Descripción:** Se introducen los datos del nuevo proyecto y el sistema lo almacena.

**Actores principales:** Administrador.

**Precondiciones:**
* Qué haya espacio suficiente para almacenar un nuevo proyecto en el sistema.


**Flujo principal:**
1. El administrador desea ingresar en el sistema un nuevo proyecto.
2. El administrador abre el cuadro de diálogo de añadir proyecto.
3. El administrador introduce los datos del nuevo proyecto, y selecciona el presupuesto, la solicitud y los investigadores.
4. El sistema comprueba que no exista otro proyecto con los mismos datos.
5. El sistema almacena la información del nuevo proyecto en la base de datos.
6. El sistema muestra por pantalla que el proyecto se ha añadido. 

**Postcondiciones:**
* Un nuevo proyecto se ha añadido a la base de datos.
* Se muestran al administrador si la operación llevada a cabo ha tenido éxito o no.

**Flujos alternativos:**
4.a. Si existe un proyecto con esos datos se muestra un mensaje de error.
