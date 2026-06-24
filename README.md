# telecom-analysis
Proyecto 6: Análisis de una empresa de telecomunicaciones
## Descripción del proyecto
Este proyecto desarrolla un análisis exploratorio de datos (EDA) para ConnectaTel, una empresa de telecomunicaciones con operaciones en México y Colombia.

El objetivo es comprender cómo los clientes utilizan los servicios móviles de llamadas y mensajería, identificar patrones de consumo, detectar comportamientos atípicos y segmentar a los usuarios según sus características demográficas y de uso. Los hallazgos obtenidos permiten generar recomendaciones para optimizar la oferta comercial, mejorar la experiencia del cliente y apoyar estrategias de retención (churn).
## Objetivos del Análisis
- Analizar el comportamiento de los usuarios según edad, plan contratado y nivel de consumo.
- Identificar segmentos de clientes con patrones de uso diferenciados.
- Detectar valores atípicos (outliers) y evaluar su impacto en el negocio.
- Evaluar la calidad de los datos y aplicar procesos de limpieza y preparación.
- Generar recomendaciones para la creación y optimización de planes móviles.
## Datasets Utilizados
- `plans.csv:` los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra).
- `users_latam.csv:` información de clientes: edad, ciudad, fecha de registro, plan contratado.
- `usage.csv:` el detalle de uso real: llamadas (duración) y mensajes (longitud).
## Etapas del Análisis
***1. Carga y Exploración de Datos***
- Importación de datasets.
- Revisión de estructura y tipos de datos.
- Validación de dimensiones y variables.
  
***2. Evaluación de Calidad de Datos***
- Identificación de valores faltantes.
- Detección de registros inconsistentes.
- Revisión de fechas fuera del rango esperado.
- Identificación de valores atípicos.
  
***3. Limpieza y Preparación***
- Conversión de formatos de fecha.
- Tratamiento de valores inválidos.
- Exclusión de registros fuera del período de análisis.
- Validación de datos faltantes estructurales.

***4. Análisis Exploratorio (EDA)***
- Estadísticas descriptivas.
- Distribución de edades.
- Análisis de llamadas y mensajes.
- Análisis de consumo por tipo de usuario.
- Identificación de outliers.
  
***5. Segmentación de Clientes***
- Segmentación por edad.
- Segmentación por nivel de uso.
- Comparación entre planes contratados.
  
***6. Conclusiones y Recomendaciones***
- Identificación de oportunidades de negocio.
- Recomendaciones para optimización de planes.
- Hallazgos relevantes para estrategias de retención.

## Cómo Ejecutar el Proyecto en Google Colab
1. Descargar el archivo .ipynb.
2. Acceder a Google Colab: https://colab.research.google.com 
3. Seleccionar **Archivo → Subir Notebook**
4. Cargar el archivo: S7 Version-Estudiante-Project-ConnectaTel.ipynb
5. Subir los archivos CSV utilizados en el análisis.
6. Ejecutar las celdas en orden.

## Guía de Reproducción 
1. Descargar los datasets: `users.csv`, `usage.csv` y `plans.csv`
2. Ubicar los archivos en el mismo directorio del notebook.
3. Ejecutar las secciones en el siguiente orden:
   - Carga de datos
   - Evaluación de calidad
   - Limpieza y preparación
   - Análisis exploratorio
   - Segmentación
   - Conclusiones
4. Verificar que las librerías indicadas estén instaladas.
5. Comparar los resultados obtenidos con las conclusiones documentadas en el notebook.
