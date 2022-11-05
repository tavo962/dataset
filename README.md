# Ejercicios

Nota: Los comandos vistos en clase son para el DBMS SQL Server 2022, en este caso se debe realizar con MySQL, por lo que los comandos pueden variar un poco.

1. Mostrar todos los registros de este dataset.
2. Mostrar los primeros 100 registros de este dataset.
3. Mostrar los últimos 100 registros de este dataset.
4. Mostrar el conteo total de registros de este dataset.
5. Mostrar todos los pacientes que ingresaron entre el 20 de Enero de 2022 y el 28 de Febrero de 2022.
6. Mostrar todos los pacientes que ingresaron en el rango anterior, pero que tuvieron síntomas desde enero de 2022.
7. Mostrar los registros de pacientes que ingresaron en el rango anterior, pero que tienen diabetes con el valor 2.
8. Realizar el query anterior pero ahora cambiando el valor 2 de diabetes por un texto “Si”.
9. Hacer el query anterior pero agregando un atributo nuevo al query que se llame "Realizado por" y en el valor debe contener el nombre, ejemplo: "Gus".
10. Se deben mostrar todos los registros que contengan letras en mayúsculas.

## Funciones que pueden ayudar a la tarea

```sql
-- Ayuda a poner una condicional para cambiar una columna
IF( condition, value_true, value_false ) AS "nombre_columna"

-- Ayuda a buscar por medio de un patrón
SELECT * FROM mexico.humans WHERE id_registro LIKE "0%";

-- Agregar una columna
SELECT 'Gus' AS nombre;
```