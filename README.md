# proyecto-sakila-automation-group-2
Proyecto de introducción a automatización con Python, SQL y Excel:

1-Extracción:
-El módulo src/config.py carga todos los datos necesarios para realizar la conexión: Host, Usuario, Contraseña...desde el archivo de configuración .env
-El módulo src/sakila_ETL.py ejecuta todas las consultas SQL que contiene para extraer los distintos datos.
-Con la librería de conexión de datos establecemos la conexióon y recuperamos los resultados como un dataframe.

2- Transformación:
-Transformamos los datos dentro de la base de datos.
-Se crea con Pandas por ejemplo un Dataframe listo para facilitar la exportación.

3-Excel:
-Cargamos el CSV en Excel, así podremos trabajar los distintos tipos de datos de las siguientes maneras:
·Creación de tablas dinámicas
·Representación gráfica a raíz de las tablas dinámicas para representar la información de una manera más visual (EJ: gráficos de columnas, de barras, circular, etc...)
·Con estos elementos el siguiente paso será crear un dashboard en el que poder analizar el comportamiento de clientes,
la distribución geográfica de ingresos, las tendencias temporales de alquileres y pagos y un top 10 de clientes que más gastan.

