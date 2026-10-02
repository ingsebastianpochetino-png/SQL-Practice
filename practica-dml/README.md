# Práctica DML - SQLite

## Objetivo

Practicar operaciones DML sobre una base de datos SQLite utilizando una tabla de vendedores.

## Tabla utilizada

La tabla `vendedores` contiene:

- `id`: identificador único del vendedor.
- `nombre`: nombre del vendedor.
- `ventas_totales`: total de ventas realizadas.
- `zona`: zona asignada al vendedor.
- `fecha_ingreso`: fecha de ingreso.

## Operaciones realizadas

### SELECT

Se realizaron consultas para obtener información de los vendedores y filtrar registros según diferentes condiciones, por ejemplo, vendedores pertenecientes a la zona Norte.

### INSERT

Se agregaron nuevos vendedores a la tabla utilizando sentencias `INSERT`.

### UPDATE

Se realizaron dos actualizaciones:

- Se incrementaron en 500 las ventas del vendedor con `id = 2`.
- Se cambió la zona a `Internacional` para los vendedores con más de 10.000 ventas.

### DELETE

Se eliminó un vendedor de prueba utilizando su `id` y se verificó posteriormente que el registro ya no existiera.

## Conceptos principales

Durante la práctica se trabajó con las operaciones:

- `SELECT`: consultar datos.
- `INSERT`: agregar datos.
- `UPDATE`: modificar datos.
- `DELETE`: eliminar datos.
- `WHERE`: filtrar los registros sobre los que se aplica una operación.

Se utilizaron cláusulas `WHERE` en las operaciones `UPDATE` y `DELETE` para evitar modificar o eliminar registros incorrectamente.
