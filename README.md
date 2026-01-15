# Superstore Sales & Profitability Analysis 📊

Este proyecto consiste en el desarrollo de un ecosistema analítico integral en **Power BI** diseñado para transformar datos transaccionales en insights estratégicos. El objetivo principal es monitorear el rendimiento de ventas y diagnosticar la salud financiera de una cadena de retail masiva.

Dataset: https://www.kaggle.com/datasets/vivek468/superstore-dataset-final

## 🚀 Vista Previa del Proyecto
*Página 1: Performance Overview*
<img width="994" height="558" alt="Screenshot_1" src="https://github.com/user-attachments/assets/7892f22a-0a2f-4c7e-9719-79f6cca3e037" />

*Página 2: Performance Analysis*
<img width="995" height="558" alt="Screenshot_2" src="https://github.com/user-attachments/assets/159ddad9-3987-4689-a8b4-e995f5b57c05" />


---

## 🛠️ Habilidades Técnicas Aplicadas

### 1. Modelado de Datos
- **Arquitectura:** Implementación de un modelo en estrella (Star Schema).
- **Tablas:** Separación de tablas de hechos (Order / Order Details) y tablas de dimensiones (Customer, Product).
- **Calendario:** Creación de una tabla `Calendar` personalizada mediante DAX para análisis de inteligencia de tiempo.

### 2. Desarrollo DAX (Medidas Clave)
- **Crecimiento Interanual (YoY):** Cálculo dinámico comparando el periodo actual frente al anterior.
- **Eficiencia:** Creación de la medida `Profit Margin %` para evaluar la rentabilidad real.
- **Agregaciones:** Volumen de órdenes, promedio de descuentos ponderado y ventas totales.

### 3. Visualización y UX/UI
- **Navegación:** Panel lateral interactivo con botones de navegación entre páginas.
- **Exploración IA:** Uso del *Decomposition Tree* para el desglose jerárquico de ventas.
- **Diagnóstico:** Gráfico de dispersión (*Scatter Chart*) para analizar la correlación entre Descuentos y Ganancia.
- **Filtros:** Sistema de segmentación por año, mes y modo de envío, incluyendo un botón de "Limpiar filtros".

---

## 📈 Hallazgos de Negocio
- Se identificó la correlación negativa entre el incremento de descuentos y el margen neto en subcategorías específicas.
- El análisis geográfico reveló los 5 estados con mayor volumen de ventas, permitiendo enfocar estrategias logísticas.
- La evolución mensual permitió detectar picos de estacionalidad y meses con crecimiento de ventas pero baja rentabilidad.

---

## ✉️ Contacto
Si tienes alguna pregunta o quieres conectar para hablar de datos, ¡no dudes en escribirme!

Marco Ortega - https://www.linkedin.com/in/ortegamarco03/
