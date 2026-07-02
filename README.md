\# Análisis de Ventas — Tienda de Música (Chinook)



\## Objetivo

Identificar qué géneros musicales generan más ingresos y analizar el 

comportamiento de compra por país, usando SQL sobre una base de datos relacional.



\## Herramientas

\- Python (sqlite3, Pandas, Matplotlib, Seaborn)

\- SQL (SQLite)

\- Jupyter Notebook



\## Dataset

Chinook Database — base de datos de ejemplo de una tienda de música digital, 

con tablas de clientes, facturas, canciones, artistas y géneros.



\## Hallazgos principales

1\. Rock es el género más rentable, con $826.65 en ingresos, más del doble 

&#x20;  que el segundo género (Latin, $382.14).

2\. Estados Unidos es el mercado más importante en volumen de ingresos ($523.06), 

&#x20;  con 13 clientes.

3\. Chile y República Checa, pese a tener muy pocos clientes, presentan el 

&#x20;  gasto promedio más alto por cliente ($46.62 y $45.12 respectivamente).

4\. Recomendación: mantener el foco en Rock y EE.UU. por volumen, y explorar 

&#x20;  el potencial de mercados pequeños de alto valor como Chile o República Checa.



\## Visualizaciones



!\[Ingresos por género](images/ingresos\_por\_genero.png)



!\[Ingresos por país](images/ingresos\_por\_pais.png)



!\[Gasto promedio por país](images/gasto\_promedio\_pais.png)



\## Cómo ejecutar este proyecto

1\. Clona el repositorio

2\. Instala dependencias: `pip install pandas matplotlib seaborn jupyter notebook`

3\. Abre `analisis-sql.ipynb` con Jupyter Notebook

