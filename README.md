# P10-Test-A-B
Análisis de Test A/B y priorización de hipótesis (ICE/RICE) para tienda online.

📊 P10 — Test A/B & Priorización de Hipótesis (ICE / RICE)

📁 Proyecto del Bootcamp de Análisis de Datos — TripleTen
👤 Autor: Aldo Daniel Galván

🧠 Descripción general del proyecto

Este proyecto simula el rol de un analista de datos en una tienda online. El objetivo es:

Priorizar hipótesis de crecimiento utilizando los frameworks
✔ ICE (Impact, Confidence, Effort)
✔ RICE (Reach, Impact, Confidence, Effort)

Analizar un experimento A/B real para determinar si la nueva variante mejora
Conversión
Ingresos
Tamaño promedio de pedido (AOV)

Se utilizaron datos de pedidos, visitas y transacciones reales.

🛠️ Tecnologías utilizadas

Python
pandas
numpy
matplotlib
seaborn
SciPy
Estadística inferencial
A/B Testing
EDA

ICE / RICE

📌 Metodología del proyecto
1️⃣ Priorización de hipótesis

Cálculo del puntaje ICE y ordenamiento
Cálculo del puntaje RICE y ordenamiento
Comparación entre ambos frameworks
Explicación técnica de por qué cambia la prioridad cuando se incorpora Reach

2️⃣ Análisis del Test A/B
✔ Limpieza de datos

Detección de usuarios repetidos en ambos grupos
Normalización de fechas
Revisión de duplicados y valores atípicos

✔ Análisis exploratorio (EDA)

Ingresos acumulados por grupo
AOV acumulado por grupo
Diferencia relativa entre A y B
Conversión diaria
Dispersión de pedidos por usuario y precios

✔ Detección de anomalías
Percentiles 95 y 99 para pedidos y precios
Filtrado para análisis robusto

✔ Pruebas estadísticas
Conversión (raw y filtrado)
AOV (raw y filtrado)
Determinación de significancia (p-value)

📈 Resultados principales
Las métricas iniciales favorecían al grupo B, pero contenía más outliers.
Después del filtrado, las diferencias se redujeron notablemente.
No existió una diferencia estadísticamente significativa en conversión ni en tamaño de pedido.
🧪 Conclusión del experimento
