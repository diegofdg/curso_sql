# **Enunciado Ejercicio 3**

## Diseñar la base de datos de un cine:

1) Crear el esquema de la base de datos.
2) Crear las siguientes tablas definidas con la siguiente estructura:

* Peliculas:
    * Campos: ID, NOMBRE, LENGTH_MIN
* Clientes:
    * Campos: ID, NOMBRE, APELLIDO, EMAIL
* Salas:
    * Campos: ID, NOMBRE, N_ASIENTOS
* Funciones:
    * Campos: ID, ID_PELICULA, ID_SALA, HORA_INICIO
* Asientos:
    * Campos: ID, FILA, NUMERO, ID_SALA
* Reservaciones:
    * Campos: ID, ID_FUNCION, ID_CLIENTE
* Asientos reservados:
    * Campos: ID, ID_RESERVACION, ID_ASIENTO
	
3) Insertar los datos de prueba para verificar que todo funciona correctamente.