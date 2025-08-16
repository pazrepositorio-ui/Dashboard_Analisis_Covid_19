# 🧬 Análisis Estratégico de Expansión para BIOGENESYS

Este proyecto integrador analiza datos de salud y contexto socioeconómico en América Latina con el objetivo de identificar ubicaciones estratégicas para la expansión de la empresa farmacéutica **BIOGENESYS**. Se utilizaron herramientas de limpieza, modelado y visualización de datos con **Python** y **Power BI**, abarcando indicadores de COVID-19, vacunación, enfermedades crónicas, estructura poblacional y condiciones económicas.

📊 Proyecto: Análisis Exploratorio y Dashboard Interactivo  
👩‍💻 Autora: María Paz Camino  
🎓 DA-PT07 | Analista de Datos  

---

## 🎯 Objetivo

Guiar decisiones de expansión farmacéutica en seis países de LATAM (Argentina, Brasil, Chile, Colombia, México y Perú), integrando datos sanitarios y demográficos para obtener **insights visuales** y **recomendaciones estratégicas**.

---

## ⚙️ Etapas del Proyecto

### 1. **Limpieza y Transformación de Datos**
- Dataset inicial: 12 millones de registros.
- Filtros aplicados:
  - Fechas posteriores al 01/01/2021.
  - Países objetivo seleccionados.
  - Valores nulos tratados con técnicas `ffill` y `bfill`.
  - Variables seleccionadas y reducción de columnas.
- Dataset final limpio: 3.744 registros.

### 2. **EDA (Exploratory Data Analysis)**
- Gráficos comparativos: población, casos, muertes, enfermedades crónicas, vacunación.
- **Heatmaps** de correlación entre variables clave.
- **Scatterplots** para detectar relaciones (ej. temperatura vs casos).
- Estadísticas descriptivas con funciones y bucles personalizados.
- Análisis por género, etnia y tipo de población (rural/urbana).
- Aplicación de funciones `map()`, `filter()`, `reduce()` y `apply()` para procesamiento eficiente.

### 3. **Visualización en Power BI**
- Dashboard con 4 secciones:
  - Perfil Demográfico
  - Correlaciones y Dispersión
  - Evolución Epidemiológica
  - Conclusiones y Recursos
- Interactividad con segmentadores, bookmarks y navegación por botones.

---

## 🧠 Principales Insights

- **Brasil y México** concentran los mayores casos y fallecimientos.
- **Chile y Argentina** presentan los mayores índices de desarrollo humano.
- **México** tiene la prevalencia más alta de **diabetes** (13%).
- **Chile** lidera en **tabaquismo**.
- Las **vacunas** fueron aplicadas con mayor volumen en Brasil y México.
- No se observa correlación directa entre temperatura y mortalidad.

---

## ✅ Recomendaciones de Expansión

- **Priorizar Brasil y México** por:
  - Escala poblacional.
  - Alta incidencia de COVID-19.
  - Alta prevalencia de enfermedades crónicas.
  - Capacidad demostrada de logística sanitaria.
- Evaluar programas preventivos enfocados en **diabetes y tabaquismo**.
- Aprovechar el aprendizaje del modelo de vacunación masiva.

---

## 💡 Reflexiones Finales

> _"Este proyecto integrador me permitió aplicar conocimientos clave de análisis de datos, estadística, visualización y programación. La experiencia me ayudó a consolidar habilidades técnicas en Python y Power BI, y a comprender la relevancia del enfoque analítico para decisiones organizacionales."_  
> — María Paz Camino

---

## 📂 Archivos incluidos

- 📄 `Informe_BIOGENESYS_PazCamino.pdf`: Informe completo del análisis.
- 📊 `dashboard_BIOGENESYS.pbix`: Archivo Power BI (opcional).
- 📁 `datos/DatosFinalesFiltrado.csv`: Dataset procesado.

---

## 🌐 Contacto

- 📧 pazrepositorio@gmail.com  
- 🔗 [LinkedIn](https://www.linkedin.com/in/pazcamino)  
- 💼 [GitHub](https://github.com/pazcaminoDA)

---

_Gracias por visitar este proyecto. Tu feedback es bienvenido._
