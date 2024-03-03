# Práctica de Modelado de Bases de Datos SQL

En este repositorio se encuentra la solución al enunciado de la práctica que se evalúa en este módulo de KeepCoding.

## Se compone de:

1. Un archivo con el diagrama Entidad/Relación elaborado en [diagrams.net](https://app.diagrams.net/).

2. Un script que se ejecuta en PostgreSQL de forma autónoma. Este script realiza las siguientes acciones con el fin de entregar una consulta que genere un reporte del hipotético "listado de coches activos de Keepcoding":
   - Crea el esquema `flotakc`.
   - Crea las tablas respectivas.
   - Establece las constraints necesarias.
   - Define la tabla que recibe la data a trabajar, e inserta los datos mediante comandos DDL.
   - Inserta los datos de cada entidad, tomando la información de la tabla alimentadora.
   - Borra la tabla alimentadora.
   - Ejecuta la consulta para la generación del reporte.

## Resultado de la consulta:

<img src="https://raw.githubusercontent.com/nataliacamero/sqlModelingPractice/main/Reporte_del_vehiculos_activos.png" alt="img-reporte-vehiculos" width="1000"/>





