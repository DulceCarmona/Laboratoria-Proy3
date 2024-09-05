# Laboratoria-Proy3

## Super Caja: Automatización del Análisis de Riesgo Crediticio
### Objetivo:
  Automatizar el proceso de análisis crediticio mediante técnicas avanzadas de análisis de datos. Clasificar a los clientes por nivel de riesgo para mejorar la toma de decisiones en la concesión de créditos.
### Herramientas y Tecnologías
- BigQuery,
- Looker Studio,
- Google Colab,
- Power BI.
#### Lenguajes de programación:
 - SQL (BigQuery),
 - Python: Jupyter Notebook.
### Procesamiento y Análisis
- Conexión de datos: Los datos fueron conectados a BigQuery y cargados después de descomprimir los archivos.
- Limpieza de datos: Se identificaron y gestionaron valores nulos y duplicados en las tres tablas clave usando SQL.
- Unión de tablas: Mediante el uso de JOIN, se combinaron las tres tablas principales para obtener un dataset con 35,546 registros únicos.
- Creación de variables: Se crearon nuevas variables para medir el riesgo relativo, desglosando los tipos de préstamos y la relación deuda/ingresos.
- Agrupación y visualización de variables: Las variables categóricas se agruparon usando Power BI, visualizando los resultados mediante gráficos de barras y circulares.
- Análisis por cuartiles: Se calcularon cuartiles para segmentar a los clientes y asignarles un score crediticio que los clasifica como "confiables" o "riesgosos".
- Visualización de resultados: Se desarrolló un dashboard interactivo en Looker Studio para facilitar la comprensión del análisis y soportar la toma de decisiones.

## Resultados
El análisis permitió dividir a los clientes en dos categorías principales:

- Buen Pagador:
  - Características: Edad mayor, menor ratio de deuda, ingresos más altos y un historial crediticio más estable.
- Mal Pagador:
  - Características: Más jóvenes, menores salarios, un mayor ratio de deuda y un historial con múltiples moras. Este grupo creció del 1.75% al 7.9% en la proporción total de clientes.
## Estrategias
- Segmentación de clientes vulnerables: Aplicar políticas más estrictas para aquellos con un perfil de mayor riesgo, priorizando la evaluación de jóvenes con altos ratios de deuda y múltiples moras.
- Automatización del análisis: Utilizar el score crediticio generado para automatizar la aprobación de créditos, reduciendo el tiempo de evaluación.
- Monitoreo continuo: Implementar un sistema de monitoreo activo para detectar clientes en riesgo y tomar decisiones proactivas.

# Visualización
#### Dashboard en Looker Studio: https://lookerstudio.google.com/reporting/7b6d89ca-422c-453a-a05f-372a58b380ac
#### Presentación Google Slides: https://docs.google.com/presentation/d/18YoSRRY9MwnyU-Mr30v6Wx73hWpqkF0uRgIbdDG0J8Q/edit?usp=sharing

