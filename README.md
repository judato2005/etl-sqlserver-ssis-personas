# etl-sqlserver-ssis-personas
Descripción

Implementación de procesos ETL mediante SQL Server y SQL Server Integration Services (SSIS), utilizando un conjunto de datos de personas almacenado inicialmente en Excel.

El proyecto contempla la extracción, transformación, validación y carga de información hacia un modelo relacional y posteriormente hacia un modelo multidimensional tipo esquema estrella.

Objetivos

Implementar un proceso ETL mediante cursores en SQL Server.

Realizar la limpieza y validación de los registros provenientes de Excel.

Implementar un paquete SSIS para cargar información desde Excel hacia el modelo relacional.

Implementar un segundo paquete SSIS para cargar la información depurada hacia un modelo multidimensional.

Aplicar reglas de validación, tratamiento de datos y detección de duplicados.

Realizar consultas analíticas sobre el modelo multidimensional.

Verificar que las ejecuciones repetidas no generen duplicados.

Tecnologías utilizadas

SQL Server

SQL Server Management Studio (SSMS)

Visual Studio Community 2026

SQL Server Integration Services (SSIS)

Microsoft Excel

Procesos ETL

Proceso 1: Cursor SQL Server

Procesamiento de los registros cuyo SourceRowId se encuentra entre 1 y 100, realizando limpieza, validación, conversión de valores monetarios y cálculo del balance mensual.

Proceso 2: Excel → Modelo relacional

Carga y transformación de los 1.000 registros del archivo Excel mediante componentes nativos de SSIS.

Proceso 3: Modelo relacional → Modelo multidimensional

Carga de la información depurada hacia un Data Warehouse con esquema estrella, utilizando dimensiones y una tabla de hechos.

Estado del proyecto

En desarrollo.

Integrantes

Integrante 1: Julian David Tovar Delgadillo

Integrante 2: Felipe Navarro Jamaica

Integrante 3: Michelle Pedraza Gonzalez


Repositorio

Este repositorio contiene los scripts SQL, paquetes SSIS, evidencias y documentación correspondientes al proyecto académico.
