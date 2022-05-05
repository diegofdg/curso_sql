# **Enunciado Ejercicio 1**

## Parte 1:

Crear tres tablas definidas con la siguiente estructura:

* Mascotas:
    * Campos: ID, NOMBRE, ID_DUEÑO, SERVICIO
* Personas:
	* Campos: ID, NOMBRE, APELLIDO, COD_ZIP, TLF

* Direcciones:
	* Campos: ZIP, NOMBRE, ZONA_RUTA
	
## Parte 2:

1) Agrega una PRIMARY KEY al campo ID en las tablas Mascotas y Personas y al campo ZIP en la tabla Direcciones.
2) Agrega una FOREIGN KEY al campo ID_DUEÑO en la tabla Mascotas que referencie al campo ID de la tabla Personas.
3) Agrega una FOREIGN KEY al campo COD_ZIP en la tabla Personas que referencie al campo ZIP de la tabla Direcciones.
4) Agrega una columna llamada EMAIL a la tabla Personas.
5) Agrega una UNIQUE CONSTRAINT a la columna EMAIL de la tabla Personas.
6) Cambia el nombre a la columna NOMBRE de la tabla Mascotas por PRIMER_NOMBRE.
7) Cambia el tipo de dato a la columna RUTA en la tabla Direcciones por CHART(12).