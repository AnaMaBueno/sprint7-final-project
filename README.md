 Objetivo

Analizar la base de clientes para identificar segmentos por edad y nivel de uso, detectar problemas de calidad de datos y generar recomendaciones de negocio para mejorar retención, engagement y crecimiento.

🗂 Datasets Utilizados

plans.csv → información de los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra)
users.csv → información de los clientes (edad, ciudad, fecha de registro, plan, churn)
usage.csv → detalle del uso real de los servicios (llamadas y mensajes)

Total registros: ~40,000

Etapas del Análisis

Exploración de datos: revisión de tipos, nulos y distribuciones.

Limpieza: conversión a fechas (datetime), manejo de nulos y valores inválidos.

Segmentación: análisis por edad y nivel de uso.

Visualización: gráficos de distribución de clientes y consumo.

Insights y recomendaciones: identificación de segmentos clave y sugerencias de negocio.

Cómo Ejecutar el Notebook

Abrir el notebook en Google Colab o Jupyter Notebook.

Instalar librerías si no están:

pip install pandas matplotlib seaborn

Cargar los archivos de datos en la misma carpeta que el notebook o vincularlos desde Google Drive.

Ejecutar las celdas de arriba hacia abajo para reproducir análisis y gráficos.

📝 Guía de Reproducción

Confirmar que los archivos .csv o .xlsx existan y tengan nombres correctos.

Asegurarse de que las fechas (reg_date, churn_date, date) estén en formato datetime.

Ejecutar todas las celdas en orden para generar las tablas, segmentaciones y gráficos automáticamente.
