# 🛍️ Alura Store - Análisis de Rentabilidad de Tiendas

[![Python](https://img.shields.io/badge/Python-3.10-blue.svg)](https://www.python.org/)
[![Colab](https://img.shields.io/badge/Notebook-Google_Colab-orange?logo=googlecolab)](https://colab.research.google.com/)
[![Status](https://img.shields.io/badge/Estado-Completado-brightgreen)]()
<!-- [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) -->

Análisis de datos desarrollado como parte del Challenge de Ciencia de Datos de **Alura Latam**. El objetivo es apoyar al Sr. Juan, dueño de cuatro tiendas, a tomar una decisión informada sobre cuál vender, basándose en datos financieros, operativos y de experiencia del cliente.

---

## 🗂 Tabla de contenidos

- [📌 Objetivo del proyecto](#-objetivo-del-proyecto)
- [🗂️ Conjunto de Datos](#️-conjunto-de-datos)
- [🧪 Metodología](#-metodología)
- [🛠️ Herramientas utilizadas](#️-herramientas-utilizadas)
- [📈 Visualizaciones destacadas](#-visualizaciones-destacadas)
- [✅ Conclusión](#-conclusión)
- [📎 Cómo ejecutar el proyecto](#-cómo-ejecutar-el-proyecto)
- [📩 Contacto](#-contacto)

---

## 📌 Objetivo del proyecto

Analizar el desempeño de las tiendas de forma comparativa para:

- Determinar la rentabilidad y eficiencia operativa.
- Identificar patrones en ventas por producto y categoría.
- Medir la satisfacción del cliente.
- Recomendar, con base en evidencia, cuál tienda debe venderse.

---

## 🗂️ Conjunto de Datos

Los datos se encuentran disponibles como archivos `.csv` públicos alojados en GitHub. Cada archivo corresponde a una tienda distinta y contiene:

- Producto, Categoría del Producto
- Precio, Costo de envío, Fecha de compra
- Vendedor, Lugar de compra
- Calificación, Método de pago, Cuotas
- Coordenadas geográficas (lat, lon)

---

## 🧪 Metodología

El análisis se realizó en un solo notebook de **Google Colab**, estructurado de forma que puede ejecutarse completo sin intervención manual.

Pasos principales:

1. Importación y limpieza de datos.
2. Creación de métricas clave: ingresos netos, ganancia por producto, etc.
3. Agrupación y visualización por tienda, producto, categoría.
4. Análisis temporal de calificaciones (2020–2023).
5. Evaluación de eficiencia en costos de envío.
6. Visualizaciones para comunicar hallazgos.

---

## 🛠️ Herramientas utilizadas

- 🐍 **Python**: Pandas, Matplotlib, Seaborn
- ☁️ **Google Colab**
- 🗃️ **Git & GitHub**
- 📊 Visualización de datos

---

## 📈 Visualizaciones destacadas

- Ingresos brutos vs netos por tienda (barras).
- Participación de cada tienda en el ingreso total (pastel).
- Calificación promedio por tienda a lo largo del tiempo (dispersión + regresión).
- Relación entre satisfacción del cliente e ingresos (dispersión).
- Cantidad y ganancia de productos más y menos vendidos (doble eje Y).
- Comparación entre ingresos brutos y costos de envío (gráfica de áreas).

---

## ✅ Conclusión

Aunque cada tienda tiene características únicas, como la variedad de productos o el nivel de satisfacción del cliente, el análisis integral sugiere que la **Tienda 4** es la menos rentable. A pesar de mantener una buena calificación promedio y bajos costos logísticos, sus ingresos netos y ganancias por transacción están por debajo del resto.

Recomendamos al Sr. Juan considerar la venta de esta tienda para fortalecer su portafolio de negocios.

---

## 📎 Cómo ejecutar el proyecto

1. Abre el notebook en [Google Colab](https://colab.research.google.com/).
2. Ejecuta todas las celdas (`Runtime > Run all`) sin necesidad de modificar el código.
3. Explora los resultados y visualizaciones integradas.
4. Si deseas reutilizarlo, descarga una copia o clona este repositorio.

---

## 📩 Contacto

¿Tienes sugerencias, dudas o comentarios?  
¡Será un gusto conectar contigo!

**Autor:** Francisco Antonio Pérez Gámez  
📧 Email: francisco.apg@outlook.com  
---
