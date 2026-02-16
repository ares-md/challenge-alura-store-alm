# challenge-alura-store-alm
Repositorio de datos para analisis del challenge alura store G-9 ORACLE

📊 Análisis de Optimización Logística y Market Share con Python
Este proyecto presenta un análisis integral de una red de retail distribuida geográficamente. Utilizando Google Colab y librerías de ciencia de datos, procesamos métricas de ventas, costos operativos y satisfacción del cliente para optimizar la rentabilidad del negocio y tomar decisiones de cierre de sucursales basadas en datos.

🚀 Herramientas Utilizadas
Entorno: Google Colab

Lenguaje: Python 3.x

Análisis de Datos: Pandas, NumPy

Visualización: Matplotlib, Seaborn, Folium (Mapas interactivos)

Algoritmos: Normalización de datos, Clustering Geográfico y Distancia Euclidiana.

📈 Resumen del Análisis
1. Cuadro de Mando Integral (KPIs Cruzados)
Desarrollamos una matriz de desempeño que cruza:

Ventas Totales: Volumen de ingresos por tienda.

Calificación Promedio: NPS y satisfacción del cliente.

Costo de Envío: Eficiencia logística por sucursal.

Dominancia Top 10: Cuota de mercado de cada tienda sobre los productos más vendidos a nivel nacional.

2. Market Share Geográfico
Implementamos una tabla dinámica con formato de calor para medir la penetración de cada tienda en diferentes ciudades.

Formato: Porcentajes con 2 decimales y totales monetarios.

Insight: Identificación de monopolios internos y zonas de canibalización.

3. Índice de Eficiencia Operativa (IEO)
Creamos un modelo de scoring ponderado (Ranking 1.0) para calificar las tiendas:

30% Ventas | 20% Calificación | 30% Costo de Envío | 20% Dominancia Top 10.

4. Matriz Estratégica de 4 Cuadrantes
Visualización avanzada que clasifica las sucursales en:

Líderes: Alto mercado y alta eficiencia.

Gigantes en Riesgo: Alto mercado pero ineficientes.

Joyas Eficientes: Operación óptima con bajo volumen.

Zona Crítica: Candidatos a cierre.

📍 Análisis Geoespacial y Decisión de Cierre
Uno de los hitos del proyecto fue la simulación de absorción de mercado. Mediante el cálculo de distancias euclidianas y solapamiento de cobertura, determinamos la viabilidad de cierre de la sucursal con menor puntaje.

Caso de Estudio: Tienda 4

Cobertura Compartida: 100% (Canibalización total por Tiendas 2 y 3).

Distancia promedio: < 2.0 unidades de las sucursales líderes.

Decisión: Cierre estratégico para ahorro de costos fijos y transferencia de facturación ($1,038M) a nodos más eficientes.

Gemini said
Este es un esquema profesional, estructurado y visual para tu README.md. Está diseñado para resaltar tus habilidades en Data Science, Logística y Toma de Decisiones Estratégicas.

📊 Análisis de Optimización Logística y Market Share con Python
Este proyecto presenta un análisis integral de una red de retail distribuida geográficamente. Utilizando Google Colab y librerías de ciencia de datos, procesamos métricas de ventas, costos operativos y satisfacción del cliente para optimizar la rentabilidad del negocio y tomar decisiones de cierre de sucursales basadas en datos.

🚀 Herramientas Utilizadas
Entorno: Google Colab

Lenguaje: Python 3.x

Análisis de Datos: Pandas, NumPy

Visualización: Matplotlib, Seaborn, Folium (Mapas interactivos)

Algoritmos: Normalización de datos, Clustering Geográfico y Distancia Euclidiana.

📈 Resumen del Análisis
1. Cuadro de Mando Integral (KPIs Cruzados)
Desarrollamos una matriz de desempeño que cruza:

Ventas Totales: Volumen de ingresos por tienda.

Calificación Promedio: NPS y satisfacción del cliente.

Costo de Envío: Eficiencia logística por sucursal.

Dominancia Top 10: Cuota de mercado de cada tienda sobre los productos más vendidos a nivel nacional.

2. Market Share Geográfico
Implementamos una tabla dinámica con formato de calor para medir la penetración de cada tienda en diferentes ciudades.

Formato: Porcentajes con 2 decimales y totales monetarios.

Insight: Identificación de monopolios internos y zonas de canibalización.

3. Índice de Eficiencia Operativa (IEO)
Creamos un modelo de scoring ponderado (Ranking 1.0) para calificar las tiendas:

30% Ventas | 20% Calificación | 30% Costo de Envío | 20% Dominancia Top 10.

4. Matriz Estratégica de 4 Cuadrantes
Visualización avanzada que clasifica las sucursales en:

Líderes: Alto mercado y alta eficiencia.

Gigantes en Riesgo: Alto mercado pero ineficientes.

Joyas Eficientes: Operación óptima con bajo volumen.

Zona Crítica: Candidatos a cierre.

📍 Análisis Geoespacial y Decisión de Cierre
Uno de los hitos del proyecto fue la simulación de absorción de mercado. Mediante el cálculo de distancias euclidianas y solapamiento de cobertura, determinamos la viabilidad de cierre de la sucursal con menor puntaje.

Caso de Estudio: Tienda 4

Cobertura Compartida: 100% (Canibalización total por Tiendas 2 y 3).

Distancia promedio: < 2.0 unidades de las sucursales líderes.

Decisión: Cierre estratégico para ahorro de costos fijos y transferencia de facturación ($1,038M) a nodos más eficientes.

🛠️ Cómo ejecutar en Google Colab

Descarga y Copia el código AluraStoreLatam-ALM.ipynb en tu google drive.

Ejecuta las celdas de visualización para generar los mapas de calor interactivos (Folium).

✒️ Autor
Alvaro Luis Medina - https://linkedin.com/in/alvaro-luis-medina-almendares

*Gracias a los mentores de Alura Latam por el compartir los conocimientos y los dataset para hacer posible la realización de este proyecto*
