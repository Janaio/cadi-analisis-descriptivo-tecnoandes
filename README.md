# 📊 Análisis Descriptivo Empresarial — Caso TecnoAndes

Repositorio oficial del taller práctico de **Análisis Descriptivo de Datos** desarrollado para el CADI de *Business Analytics & Data Intelligence*.

**Autor:** Luis Fernando Forero Mendoza  
**Tecnologías:** Python 3.10+ (`pandas`, `numpy`, `matplotlib`, `seaborn`) · Google Colab

---

## 📁 Estructura del Repositorio

| Archivo | Descripción |
|---|---|
  | `Entregable Fer - BI.ipynb` | Notebook principal documentado con el pipeline de validación, estadística descriptiva univariada/bivariada, detección de outliers (Tukey), visualizaciones e interpretación de negocio. |
| `Datos limpios en Excel.xlsx` | Conjunto de datos curado previamente (414 registros transaccionales, 7 variables) utilizado como fuente primaria del análisis. |
| `README.md` | Documentación ejecutiva e instrucciones de reproducibilidad del repositorio. |

---

## 🎯 Marco Metodológico y Objetivos

El análisis se fundamenta en la **Guía Analítica Empresarial** y en el marco conceptual de *Harvard Business School Online* (*"What is Descriptive Analytics? 5 Examples"*), abarcando:
1. **Ingesta y Auditoría Contable:** Validación del 100% de integridad matemática sobre las 414 transacciones registradas.
2. **Caracterización Estadística Univariada:** Cálculo de métricas de tendencia central (Media, Mediana, Moda), dispersión (Desviación Estándar, IQR, Coeficiente de Variación) y forma (Asimetría y Curtosis).
3. **Detección de Valores Atípicos:** Aplicación del criterio intercuartílico de Tukey para aislar compras corporativas B2B.
4. **Visualización y Análisis Bivariado:** Panel de distribuciones, Curva de Pareto (Ley 80/20), Matriz de Calor Regional vs. Producto y Serie Cronológica con Media Móvil Trimestral (3-MMA).
5. **Estrategia Basada en Evidencia:** Recomendaciones operativas para gestión de portafolio, expansión geográfica y efectividad de la fuerza de ventas.

---

## 🚀 Instrucciones de Ejecución en Google Colab

1. Descarga o abre directamente el archivo `Entregable Fer - BI.ipynb` en Google Colab.
2. Carga el archivo `Datos limpios en Excel.xlsx` en el panel lateral de archivos de Colab 
3. Selecciona **Entorno de ejecución → Ejecutar todas** (`Ctrl + F9`).
