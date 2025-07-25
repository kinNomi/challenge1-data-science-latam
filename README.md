# Análisis de Datos de Tiendas

## Propósito

Este notebook de Google Colab tiene como propósito analizar los datos de ventas de cuatro tiendas diferentes para determinar cuál de ellas sería la más adecuada para vender, considerando diversos factores clave de rendimiento. El análisis se centra en los ingresos totales, ventas por categoría, calificaciones de clientes, productos más y menos vendidos, y costos de envío.

## Estructura del Código

El notebook está organizado en varias secciones, cada una abordando un aspecto específico del análisis:

1.  **Importación de Datos:** Carga los datos de ventas de cuatro archivos CSV alojados en un repositorio de GitHub en DataFrames de pandas.
2.  **Análisis de Facturación:** Calcula y muestra los ingresos totales generados por cada tienda y el ingreso total combinado.
3.  **Ventas por Categoría:** Calcula y muestra las ventas totales para cada categoría de producto en cada tienda.
4.  **Calificación Promedio:** Calcula y muestra la calificación promedio de los clientes para cada tienda.
5.  **Productos Más y Menos Vendidos:** Identifica y muestra los 3 productos que generaron más y menos ingresos en cada tienda. Para esto, se concatenan los datos de todas las tiendas en un único DataFrame.
6.  **Envío Promedio por Tienda:** Calcula y muestra el costo de envío promedio para cada tienda.
7.  **Generación de Gráficos:** Visualiza los ingresos totales por tienda (gráfico de barras), el ingreso promedio por venta (gráfico de línea) y la distribución del total de ingresos entre las tiendas (gráfico de pastel).
8.  **Informe Final:** Presenta un informe estructurado que resume los hallazgos del análisis y recomienda la tienda a vender, justificando la decisión con base en los datos y visualizaciones.

## Uso

Para utilizar este notebook:

1.  Abre el notebook en Google Colab.
2.  Ejecuta cada celda de código secuencialmente.
3.  Examina la salida de cada celda para entender los resultados del análisis.
4.  Consulta los gráficos generados para una representación visual de los datos.
5.  Lee el "Informe Final" para conocer las conclusiones y la recomendación principal.

Los datos utilizados en este notebook provienen de los siguientes archivos CSV:
- [tienda_1.csv](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_1%20.csv)
- [tienda_2.csv](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_2.csv)
- [tienda_3.csv](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_3.csv)
- [tienda_4.csv](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_4.csv)
