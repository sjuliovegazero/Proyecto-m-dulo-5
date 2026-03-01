README Análisis de Datos: Proyecto ComercioYA
Proyecto módulo 5 por SJV

Contexto del Proyecto

Este proyecto surge de la necesidad de la empresa ComercioYA de transformar datos históricos de ventas en decisiones estratégicas fundamentadas. El objetivo principal es aplicar técnicas de EDA (Exploratory Data Analysis) para comprender el comportamiento de los clientes y mejorar la estrategia de ventas.

Tecnologías Utilizadas

•Python: Lenguaje principal.
•Pandas & NumPy: Procesamiento y limpieza de datos.
•Seaborn & Matplotlib: Visualización y estadística.
•Statsmodels: Modelado de regresión lineal.
 
Estructura del Análisis (Paso a Paso)

Siguiendo los requerimientos del programa Alkemy, el análisis se divide en 6 lecciones clave:

1. Análisis Inicial de Datos (IDA)
•Identificación de variables cuantitativas y categóricas.
•Tratamiento de valores nulos e inconsistencias para asegurar la calidad.

2. Estadística Descriptiva
•Cálculo de medidas de tendencia central (media, mediana, moda) y dispersión (desviación estándar).
•Detección de outliers mediante boxplots para entender casos atípicos en las ventas.

3. Análisis de Correlación
•Construcción de una matriz de correlación heatmap para cuantificar la relación entre variables.
•Cálculo del Coeficiente de Pearson (R) para validar la fuerza de las asociaciones.

4. Modelado Predictivo
•Implementación de modelos de regresión lineal simple y múltiple con statsmodels.
•Evaluación mediante métricas de error: R^2, MSE y MAE.

5. Visualización Avanzada
•Uso de pairplot y jointplot para representar relaciones complejas entre múltiples variables simultáneamente.
•Análisis de densidad de ventas por sucursal mediante violinplot.

6. Reporte Final y Exportación
•Generación de gráficos personalizados y exportación a formato PDF.
 
Hallazgos Principales
•Impacto de la Cantidad: Se observó que el volumen de productos vendidos tiene una correlación significativa con el ingreso total, sugiriendo una estrategia basada en rotación de inventario.
•Eficacia de las Sucursales: Las visualizaciones permitieron detectar qué sucursales operan con mayor regularidad y cuáles presentan picos de ventas inusuales.
