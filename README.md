# Práctica Northwind en PostgreSQL

## Autor
- Rubén García

## Herramientas
- PostgreSQL: 18
- pgAdmin: 4

## Instrucciones para reproducir el trabajo
Para preparar el entorno y cargar la base de datos, sigue estos pasos:

1. **Instalar PostgreSQL 18** y **pgAdmin 4** (asegúrate de incluir las *Command Line Tools*).
2. Conectar al servidor mediante pgAdmin o psql con el usuario `postgres`.
3. Crear la base de datos vacía forzando la codificación UTF-8 para evitar problemas de caracteres:
   ```sql
   CREATE DATABASE northwind WITH ENCODING = 'UTF8' TEMPLATE = template0;
   ```
4. Conectarse a la nueva base de datos `northwind`.
5. Abrir el script `northwind.sql` desde el Query Tool de pgAdmin y ejecutarlo para generar las tablas, insertar los datos y crear las restricciones de integridad.

## Diagrama ER
A continuación se muestra el modelo Entidad-Relación autogenerado tras importar la base de datos:

![Diagrama Entidad-Relación](img/diagrama-er.png)

## Índice
- [Consultas de análisis](respuestas.md)
