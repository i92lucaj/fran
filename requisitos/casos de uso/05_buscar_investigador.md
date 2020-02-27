## Buscar a un investigador en el sistema.

**ID:** 05.
**Descripción:** Se introduce uno de los datos personales de un investigador y se busca su ficha en la base de datos.

**Actores principales:** Administrador.

**Precondiciones:**
* Qué el investigador ya exista en la base de datos del sistema.

**Flujo principal:**
1. El administrador desea buscar a un investigador en el sistema.
2. El administrador abre el cuadro de diálogo de buscar a un investigador.
3. El administrador introduce uno de los datos del investigador.
4. El sistema busca al investigador en la base de datos.
5. El sistema muestra la información del investigador.
6. El sistema muestra un cuadro de acción, en el que están las opciones; ver proyectos del investigador, añadir a un nuevo proyecto, eliminar de un proyecto y volver al menú inicial. 

**Postcondiciones:**
* Ninguna.

**Flujos alternativos:**
5.a. Si no existe el investigador se muestra un mensaje de error.
