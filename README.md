# Modelo Proyecto - Optimización de Redes Eléctricas

## Descripción General

Este repositorio alberga un Jupyter Notebook especialmente diseñado para abordar desafíos complejos en la optimización de redes eléctricas. El proyecto se enfoca en desarrollar y aplicar modelos matemáticos sofisticados para analizar y mejorar la eficiencia de las redes eléctricas. El objetivo principal es ofrecer una herramienta robusta y versátil que pueda ser utilizada tanto en contextos académicos como profesionales para facilitar la toma de decisiones en el diseño y operación de redes eléctricas.

## Contenidos del Notebook

### 1\. Librerías Necesarias

El notebook comienza importando todas las librerías necesarias para su ejecución:

- `Gurobipy`: Para correr el modelo de optimización.
- `math`: Para operaciones matemáticas complejas.
- `networkx`: Manejo y visualización de grafos.
- `matplotlib.pyplot`: Dibujar los grafos.
- `xlsxwriter`: Escribir resultados en archivos Excel.

### 2\. Datos y Escenarios de Prueba

Se detallan los datos y escenarios de prueba para ejecutar el modelo en diferentes redes eléctricas. Esta sección incluye:

- Conversión de unidades para mantener consistencia en los cálculos.
- Carga de datos para 14, 33, 84 y 136 nodos. Incluyendo arcos y nodos con sus respectivas especificaciones.

### 3\. Modelo de Optimización

En esta sección crucial, se despliegan dos variantes del modelo de optimización:

#### 3.1 Modelo Base

- Se describe el modelo matemático base utilizado para la optimización de redes.
- Se detallan las variables, las restricciones y la función objetivo del modelo.
- Se explica cómo este modelo puede ser aplicado para resolver problemas estándar de redes eléctricas.

#### 3.2 Modelo Mejorado

- Se introduce una versión avanzada del modelo base, incorporando mejoras y refinamientos.
- Se describe cómo estas mejoras contribuyen a una mayor eficiencia y precisión en la optimización de redes.
- Se discuten casos de estudio o escenarios donde este modelo mejorado ofrece ventajas significativas sobre el modelo base.

### 4\. Visualización de Resultados

Sección dedicada a la visualización de los resultados del modelo de optimización, utilizando gráficos y tablas para una mejor comprensión.

### 5\. Exportación de Resultados

Instrucciones y código para exportar los resultados obtenidos en formatos útiles como Excel o imágenes.

## Uso del Notebook

Para utilizar este notebook, simplemente clone el repositorio y ejecute el notebook en un entorno que soporte Jupyter, como Anaconda o JupyterLab. Asegúrese de tener todas las librerías necesarias instaladas.

## Contribuciones

Las contribuciones son bienvenidas. Si desea contribuir al proyecto, por favor haga un fork del repositorio y envíe un pull request con sus mejoras.

## Licencia

Este proyecto está bajo la Licencia MIT. Vea el archivo `LICENSE` para más detalles.

## Contacto

Para más información o consultas, por favor abra un issue en este repositorio.

## Autores

Camilo Aguilar León (c.aguilarl@uniandes.edu.co)

Esteban Céspedes Díaz (e.cespedes@uniandes.edu.co)

## Universidad de los Andes
