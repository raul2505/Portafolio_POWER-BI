# Credit Card Transaction Report Dashboard

Este proyecto presenta un **Dashboard Dinámico en Power BI** que proporciona información detallada sobre **transacciones con tarjetas de crédito** y **perfiles de clientes**. El desafío principal de este proyecto fue desarrollar un sistema robusto que pueda manejar grandes volúmenes de datos, generar informes precisos y ofrecer una experiencia fácil de usar para el análisis de transacciones.

## Descripción del Proyecto

El objetivo principal de este reporte es proporcionar una visión integral y dinámica de las transacciones realizadas con tarjetas de crédito, enfocándose en los siguientes aspectos clave:

- **Análisis de Transacciones**: Resumen de las transacciones realizadas, incluyendo datos como montos, fechas y lugares de compra.
- **Perfil de Clientes**: Información detallada sobre los clientes que realizaron las transacciones, incluyendo segmentos y patrones de comportamiento.
- **Visualizaciones Interactivas**: Gráficos y tablas interactivas que permiten explorar las métricas de forma dinámica.

### Desafíos y Soluciones

El proyecto enfrentó varios desafíos, tales como:

- **Integración de Datos**: Se integraron datos provenientes de múltiples fuentes, lo cual requirió un proceso de limpieza y transformación de datos utilizando **Power Query** para asegurar que la información estuviera en el formato correcto y pudiera ser procesada eficientemente.
- **Manejo de Grandes Volúmenes de Datos**: Debido a la gran cantidad de transacciones, se implementaron técnicas para optimizar la carga y procesamiento de datos en Power BI, como la eliminación de duplicados y la aplicación de filtros eficientes.
- **Obtención de Información Significativa**: Se trabajó en la creación de medidas y cálculos complejos en DAX para proporcionar métricas clave como el gasto promedio, frecuencia de transacciones, entre otros.

## Características del Dashboard

- **Filtros Dinámicos**: Permite filtrar por diferentes parámetros como rango de fechas, tipo de tarjeta, ubicación de transacción, entre otros.
- **Visualizaciones**: Incluye gráficos de barras, líneas y mapas interactivos que permiten explorar las tendencias de las transacciones y el comportamiento del cliente.
- **KPIs Clave**: Indicadores clave de rendimiento (KPIs) como el monto total gastado, el número total de transacciones y el promedio de gasto por cliente.

## Requisitos

- **Power BI Desktop**: Necesitarás Power BI Desktop para abrir y modificar el archivo `.pbix`.
- **Acceso a Fuentes de Datos**: El proyecto puede requerir que tengas acceso a las fuentes de datos de las transacciones con tarjetas de crédito para actualizar los datos.

## Instrucciones de Uso

1. **Descargar el archivo**: Clona o descarga el repositorio.
2. **Abrir en Power BI**: Abre el archivo `.pbix` en Power BI Desktop.
3. **Actualizar los Datos**: Si tienes acceso a las fuentes de datos, actualiza las conexiones para cargar la información más reciente.
4. **Explorar el Dashboard**: Interactúa con los filtros y visualizaciones para explorar el informe y obtener información sobre las transacciones y los clientes.

## Estructura del Proyecto

- `Credit_Card_Transactions_Report.pbix`: El archivo principal de Power BI que contiene el dashboard.
- `Power_Query_Scripts.txt`: Contiene los scripts utilizados en Power Query para la transformación de datos.
- `README.md`: Este archivo de documentación.

## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.
