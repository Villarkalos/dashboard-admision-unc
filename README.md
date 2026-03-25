# 📊 Dashboard Admisión UNC en Cifras

## 🧠 Contexto
¿Qué hace que un reporte de Power BI sea realmente profesional?

Este proyecto responde esa pregunta mediante el desarrollo de un dashboard analítico sobre los procesos de admisión de la Universidad Nacional de Cajamarca (UNC), construido desde cero con enfoque en análisis, visualización y toma de decisiones.

---

## 🎯 Problema de negocio
Las universidades gestionan grandes volúmenes de datos en procesos de admisión:

- ¿Qué carreras son más demandadas?
- ¿Dónde existe mayor competencia?
- ¿Cómo varía la tasa de admisión entre sedes?

Sin un sistema de visualización, estas respuestas permanecen ocultas en datos tabulares o reportes estáticos.

---

## 📊 Fuente de datos

Los datos utilizados en este proyecto provienen de información pública disponible en el portal institucional de la Universidad Nacional de Cajamarca.

- Datos extraídos a partir de reportes oficiales publicados por la universidad
- Procesados y estructurados manualmente para su análisis
- Consolidados en una única tabla analítica

⚠️ **Limitación actual:**
No se dispone de información detallada a nivel de postulante (como puntajes individuales o rankings completos por examen), por lo que el análisis se centra en métricas agregadas como postulantes, ingresantes y tasas.

---

## ⚙️ Solución desarrollada

### 🔹 Fuente estructurada
Dataset consolidado con:
- Examen
- Carrera
- Modalidad
- Postulantes
- Ingresantes
- Fecha

---

### 🔹 Transformación (Power Query)
- Limpieza y estandarización de nombres de carrera
- Extracción de sede desde campos de texto
- Creación de variables temporales (Año, Mes, Periodo)
- Asignación de coordenadas geográficas por sede

---

### 🔹 Modelo DAX (Arquitectura analítica)

El modelo se organiza en 8 capas funcionales:

1. KPIs principales  
2. Análisis temporal (variaciones, tendencias)  
3. Rankings dinámicos  
4. Competitividad (ratio postulantes/vacante)  
5. Análisis por sede  
6. Dispersión estadística  
7. Textos dinámicos  
8. HTML personalizado  

---

## 🎨 Innovación clave

Uso de HTML dentro de Power BI mediante medidas DAX para:

- Navegación entre páginas tipo aplicación
- KPIs con diseño personalizado
- Glosario integrado dentro del reporte
- Títulos dinámicos según filtros activos

Este enfoque permite superar las limitaciones visuales estándar de Power BI.

---

## 📊 Estructura del reporte

- 🏠 **Portada**: resumen ejecutivo con KPIs principales  
- 📈 **Vista general**: análisis agregado de postulantes e ingresantes  
- 🔍 **Vista particular**: análisis de competitividad y detalle por carrera  
- 📘 **Guía de lectura**: explicación del modelo y métricas  

---

## 📸 Vistas del dashboard

<img width="1295" height="705" src="https://github.com/user-attachments/assets/560e4273-914e-4226-8783-40079ab42057" />
<img width="1285" height="724" src="https://github.com/user-attachments/assets/791d5883-4cf1-4d2b-9c5d-5b09eef1ce99" />
<img width="1280" height="719" src="https://github.com/user-attachments/assets/d3bb634a-64b6-47e2-9269-036df8e9c0b5" />
<img width="1266" height="722" src="https://github.com/user-attachments/assets/fa168fe9-914d-4206-a3de-9dcabf80f071" />

---

## 🚀 Resultado

Dashboard interactivo que permite:

- Identificar carreras con mayor demanda
- Analizar niveles de competencia
- Detectar brechas de admisión por carrera
- Evaluar distribución geográfica de postulantes

---

## 📌 Potencial de mejora

El proyecto puede escalar incorporando:

- Puntajes individuales por postulante  
- Rankings completos por examen  
- Análisis predictivo de ingreso  
- Modelos de probabilidad de admisión  

Esto permitiría un nivel más profundo de analítica (predictiva y prescriptiva).

---

## 🤖 Uso de Inteligencia Artificial

La inteligencia artificial fue utilizada como herramienta de apoyo para:

- Optimización de lógica DAX  
- Mejora del diseño visual  
- Validación de enfoque analítico  

El criterio analítico y la construcción del modelo fueron desarrollados de forma autónoma.

---

## 👨‍💻 Autor

**Richard Villar Villena**  
Analista de Datos | Power BI | DAX  

---
