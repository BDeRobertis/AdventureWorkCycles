# AdventureWorkCycles
Este informe presenta un análisis exhaustivo de las ventas de Adventure Works, con el objetivo de proporcionar una visión clara del desempeño de la compañía y guiar la toma de decisiones estratégicas.A través de la exploración de indicadores claves de rendimiento  y la identificación de tendencias significativas, buscamos empoderar a la organización para optimizar sus estrategias de ventas y alcanzar sus objetivos de crecimiento.
En línea con la misión de Adventure Works de fomentar la exploración y la aventura, este análisis se adentra en los datos de ventas para descubrir nuevas oportunidades y territorios inexplorados. Al comprender los patrones de compra de los clientes, evaluar la eficacia de las campañas de marketing y medir el rendimiento de los equipos de ventas, Adventure Works puede trazar un rumbo hacia el éxito continuo en un mercado dinámico y competitivo.


Desarrollo del proyecto
Informe de Avance del Proyecto: Análisis de Ventas de Adventure Works
Preparación y Limpieza de Datos
1.	Restauración de la Base de Datos: Se ha restaurado con éxito la base de datos de Adventure Works en SQL Server, garantizando la disponibilidad de los datos necesarios para el análisis.
2.	Importación de Tablas: Se han importado las tablas relevantes de la base de datos, asegurando que se incluya toda la información pertinente para el análisis de ventas.
3.	Conexión de Datos Externos: Se ha establecido una conexión entre la tabla DimCustomer en Excel y Power BI, permitiendo la integración de datos adicionales del cliente.
4.	Limpieza de Datos en DimCustomer: Se han eliminado columnas irrelevantes de la tabla DimCustomer, optimizando el conjunto de datos y mejorando la eficiencia del análisis.
5.	Combinación de Columnas: Se ha realizado una operación de "merge" para combinar columnas específicas dentro de la tabla DimCustomer, consolidando información relacionada.
6.	Eliminación de Filas en Blanco: Se han eliminado filas en blanco de la tabla DimCustomer, asegurando la integridad de los datos y evitando posibles errores en el análisis.
7.	Combinación de Tablas (DimCustomer y DimGeography): Se han combinado las tablas DimCustomer y DimGeography utilizando claves comunes (city, stateprovincecode, stateprovincename), enriqueciendo los datos del cliente con información geográfica.
8.	Combinación de Tablas (DimProduct y DimProductSubcategory): Se han combinado las tablas DimProduct y DimProductSubcategory para obtener el productcategorykey, y luego se extrajeron los nombres de categoría y subcategoría de producto en inglés (englishproductcategoryname y englishproductsubcategoryname), mejorando la claridad y comprensión de los datos del producto.
Transformación y Modelado de Datos
1.	Creación de Columna Personalizada (ShortMonth): Se ha creado una columna personalizada llamada "ShortMonth" en la tabla DimDate, que muestra el nombre del mes en formato abreviado, facilitando la visualización y el análisis de datos temporales.
2.	Deshabilitación de Carga de Tablas: Se ha deshabilitado la carga para las tablas DimGeography, DimProductCategory y DimProductSubcategory, optimizando el rendimiento de Power BI al excluir tablas que no se utilizarán activamente en el informe.
3.	Configuración de Tabla de Fechas: Se ha marcado la columna "FullDateAlternateKey" de la tabla DimDate como la tabla de fechas principal, permitiendo un análisis temporal preciso y la creación de relaciones con otras tablas basadas en fechas.
4.	Creación de Columna de Trimestre: Se ha creado una columna llamada "Trimestre" que indica el trimestre correspondiente a cada fecha, facilitando el análisis de ventas por períodos trimestrales.
5.	Inicio de Creación de Medidas: Se ha comenzado el proceso de creación de medidas en Power BI, lo que permitirá realizar cálculos y análisis personalizados sobre los datos de ventas.

