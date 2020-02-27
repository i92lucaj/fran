## Modificar los datos de un investigador.

**ID:** 07.
**Descripción:** Se modifican los datos del investigador.

**Actores principales:** Administrador.

**Precondiciones:**
* Qué haya algún investigador en el sistema.


**Flujo principal:**
1. El administrador desea modificar a un investigador de la base de datos del sistema.
1. El administrador busca y localiza al investigador cuyos datos se van a modificar (caso de uso <02>).
1. El administrador introduce los nuevos datos del investigador, véase, nombre completo, domicilio...
1. El sistema comprueba que el investigador modificado no tenga los mismos datos que otro investigador de la base de datos.
1. El sistema muestra por pantalla los nuevos datos del investigador.
1. El administrador, mediante un cuadro de diálogo, le da el visto bueno a la modificación.
1. El sistema almacena la información del investigador en la base de datos.
1. El sistema muestra por pantalla, que el investigador ha sido modificado. 

**Postcondiciones:**
* Que se haya efectuado el cambio correctamente.

 
**Flujos alternativos:**
2.a. Si el investigador no existe, se muestra un mensaje de error.
5.a. Si los datos introducidos no son válidos, se muestra un mensaje de error.
5.b. Si el investigador modificado coincide con otro investigador en cuánto a datos se refiere, se muestra un mensaje de error.
7.a. Si el administrador no confirma los cambios, los datos del investigador no se modifican.
