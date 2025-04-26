📦 Proyecto Prototípico: Análisis de Medicamentos en Iztapalapa (2024)
Autor: Brandon Uriel García Sánchez
Materia: Proyecto Prototípico Interdisciplinario
Universidad: Universidad Rosario Castellanos
Año: 2024

🧠 Descripción del Proyecto
Este proyecto fue desarrollado con fines educativos y tiene como objetivo principal proyectar el consumo de medicamentos en centros de salud de Iztapalapa, así como analizar el control de calidad en los pesos de unidades farmacéuticas.

Se abordó un enfoque interdisciplinario, combinando conocimientos de programación, estadística, análisis de datos y salud pública. Para lograrlo, se trabajó con Python utilizando librerías como NumPy, Pandas y Matplotlib.

🎯 Objetivos
Proyectar el consumo de medicamentos de alto costo y de uso crónico en la alcaldía Iztapalapa para el año 2024.

Estimar el impacto económico del suministro de estos medicamentos en función de la población proyectada y la incidencia de las enfermedades.

Simular procesos de control de calidad mediante análisis estadístico de peso en puntos de control tipo A, B y C.

Generar visualizaciones que permitan evaluar el comportamiento de las muestras dentro del lote.

🧪 Estructura del Código
MEDICAMENTOS
Diccionario que contiene información detallada de medicamentos costosos y crónicos usados en México:

peso_base

variacion

precio_aproximado

uso clínico

incidencia poblacional estimada

proyeccion_consumo_medicamentos()
Calcula la cantidad estimada de personas que podrían requerir cada medicamento en 2024, y el costo anual aproximado para el sistema de salud local.

generar_muestra_medicamentos()
Simula el peso de unidades farmacéuticas con variaciones dentro del margen permitido, para representar lotes de producción.

analizar_punto_control()
Realiza un análisis estadístico de los pesos de un lote de 200 unidades, e imprime:

Peso total

Peso promedio

Desviación estándar

Visualización gráfica del peso por unidad

main()
Ejecuta el flujo principal del análisis:

Proyección de consumo

Simulación de control de calidad para cada medicamento en 3 puntos distintos (A, B, C)

