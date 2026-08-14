# Prueba Técnica — Data Engineer

Repositorio desarrollado como parte de una **prueba técnica para postulación al cargo de Data Engineer**.

La solución fue implementada en **Databricks** utilizando **PySpark** y **Delta Lake**, con foco en transformación de datos, calidad, cargas incrementales y manejo de información histórica.

## Objetivo

Resolver los ejercicios propuestos aplicando buenas prácticas de ingeniería de datos y dejando documentadas las principales decisiones técnicas.

La prueba cubre:

- Transformación de datos desde Bronze hacia Silver.
- Normalización y tipificación de datos.
- Manejo de estructuras anidadas y arrays.
- Tratamiento de valores nulos.
- Escritura y particionamiento de tablas Delta.
- Corrección de un `MERGE` incremental.
- Prevención de duplicados.
- Uso de claves de negocio compuestas.
- Implementación de cargas incrementales mediante watermark.

## Tecnologías utilizadas

- Python
- PySpark
- Databricks
- Delta Lake
- Spark SQL

---



## Resultado

La solución implementa los tres escenarios solicitados y deja las transformaciones, reglas de negocio y validaciones documentadas dentro del notebook para facilitar su revisión y mantenimiento.
