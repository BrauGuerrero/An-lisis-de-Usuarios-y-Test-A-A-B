# An-lisis-de-Usuarios-y-Test-A-A-B
Análisis del comportamiento de usuarios en una app de alimentos: estudio del embudo de conversión y validación de un test A/A/B para evaluar el impacto de un cambio de fuente en la experiencia del usuario.


## 📋 Descripción general
Este proyecto analiza el comportamiento de usuarios en una aplicación móvil de productos alimenticios.  
El objetivo fue identificar cuellos de botella en el embudo de conversión y evaluar los resultados de un test **A/A/B** para determinar si un cambio en las fuentes tipográficas afectaba la interacción de los usuarios.

A través del análisis exploratorio y la prueba de hipótesis, se compararon tres grupos de usuarios:
- **Grupo A1 y A2:** Control (fuentes originales)
- **Grupo B:** Experimental (fuentes nuevas)

## 🎯 Objetivos
- Analizar el embudo de conversión y detectar en qué etapas los usuarios abandonan.
- Verificar la correcta segmentación de los grupos A/A mediante comparación estadística.
- Evaluar el impacto de las nuevas fuentes sobre la conversión.
- Determinar si existen diferencias estadísticamente significativas entre los grupos.

## 🧠 Metodología
1. **Preparación de datos:** limpieza, verificación de tipos y creación de variables temporales.  
2. **Exploración inicial:** revisión de eventos, usuarios y periodo representativo de datos.  
3. **Análisis del embudo de conversión:** identificación de etapas críticas.  
4. **Pruebas A/A/B:** contraste de hipótesis entre grupos mediante pruebas estadísticas.  

## 📊 Dataset
El archivo principal es `logs_exp_us.csv`, que contiene:
- `EventName`: nombre del evento.
- `DeviceIDHash`: identificador único de usuario.
- `EventTimestamp`: marca temporal del evento.
- `ExpId`: identificador de experimento (246 y 247: control; 248: prueba).

## ⚙️ Tecnologías utilizadas
- **Python (Pandas, NumPy, Matplotlib, SciPy, Plotly)**  
- **Jupyter Notebook** para análisis interactivo  
- **Estadística inferencial** para pruebas de hipótesis  

## 💡 Resultados
- Se identificaron los puntos de mayor abandono en el embudo.  
- No se encontraron diferencias significativas entre los grupos de control (A/A), confirmando la validez del test.  
- El cambio de fuentes **no afectó significativamente** el comportamiento de los usuarios.  

## 📁 Estructura del repositorio
logs_exp_us.csv
Análisis de Usuarios y Test AAB.ipynb
README.md
