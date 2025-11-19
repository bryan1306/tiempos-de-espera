# 🩺 Análisis de Tiempos de Atención en Servicios de Salud

Este proyecto analiza los tiempos de espera de pacientes en un servicio ambulatorio, con el objetivo de identificar patrones, cuellos de botella y oportunidades de mejora operativa.
Todo el desarrollo se realizó en un único archivo Jupyter Notebook, lo que permite seguir el flujo completo del análisis de manera clara y directa.

📄 Estructura del Proyecto

El proyecto está organizado en un solo archivo:

analisis_tiempos_atencion.ipynb

Este notebook contiene:
Generación del dataset,
Limpieza de datos,
Análisis Exploratorio de Datos (EDA),
Gráficos y visualizaciones clave,
Conclusiones e insights,
Oportunidades de mejora.

📊 Descripción del Dataset

El dataset contiene 4.000 registros y fue generado de forma sintética para simular un entorno real de atención en salud.

Incluye las siguientes variables:

Variable	Descripción
patient_id	ID único del paciente
age	Edad
gender	Género (M/F)
appointment_type	Tipo de consulta
doctor	Médico asignado
day_of_week	Día de la semana
scheduled_time	Hora programada (minutos)
arrival_time	Hora real de llegada
start_time	Inicio de la atención
end_time	Fin de la consulta
service_time_min	Duración de la atención
waiting_time_min	Tiempo de espera

🧪 Tecnologías Utilizadas

Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook

🔍 Flujo del Proyecto

1. Generación de datos
Se creó un dataset realista utilizando distribuciones típicas del sector salud (diferencias entre hora programada, llegada y atención real).

3. Limpieza de datos
Eliminación de tiempos negativos o imposibles.
Conversión de formatos de hora.
Validación de rangos.

4. EDA (Exploratory Data Analysis)
Incluye:
Distribución del tiempo de espera
Comparación por tipo de consulta
Comparación por médico
Identificación de días de mayor demanda
Relación entre edad y tiempo de espera

📈 Principales Insights

Los tiempos de espera se concentran entre 10 y 40 minutos.
Las consultas de urgencias muestran mayor variabilidad en espera.
Algunos médicos presentan tiempos de espera sistemáticamente más altos.
Los días martes y jueves tienden a registrar mayor congestión.
No se encontró relación fuerte entre la edad del paciente y el tiempo de espera.


🧭 Líneas de Trabajo Futuro

Crear un dashboard interactivo con Dash o Power BI.
Implementar un modelo de predicción de tiempos de espera.
Integrar datos reales (no simulados).
Agregar segmentación por especialidad o nivel de urgencia.

👤 Autor

Bryan Barrios Carlier
Analista de Datos | Python | SQL | Power BI | Storytelling de Datos
