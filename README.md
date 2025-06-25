# 🎮 Análisis de Ventas de Videojuegos - Ice
Exploración de tendencias de ventas y mercados regionales con Python

## 📌 Introducción
La tienda online **Ice** distribuye videojuegos globalmente y desea planear una estrategia de marketing efectiva para 2017. Para lograrlo, se analizarán datos históricos hasta 2016 sobre ventas, plataformas, géneros y calificaciones.

Este análisis permitirá identificar plataformas prometedoras, géneros populares, y diferencias entre los mercados de América del Norte, Europa y Japón.

## 🎯 Problema de negocio
El éxito de un videojuego depende de múltiples factores: plataforma, género, reseñas, y región de venta. Ice necesita identificar patrones que ayuden a lanzar campañas segmentadas, seleccionar géneros relevantes y optimizar su catálogo.

## 🔍 Objetivos del proyecto
✔ Preparar los datos eliminando valores atípicos y faltantes  
✔ Analizar ventas por año, plataforma, género y región  
✔ Evaluar la correlación entre calificaciones y ventas  
✔ Comparar patrones de consumo entre regiones  
✔ Validar hipótesis estadísticas con pruebas adecuadas  

## ❓ Preguntas clave
- ¿Qué plataformas dominaron en ventas históricamente?  
- ¿Qué géneros son los más populares y rentables?  
- ¿Qué regiones compran más videojuegos?  
- ¿Influyen las calificaciones de usuarios y críticos en las ventas?  
- ¿Existen diferencias en las preferencias entre Japón, Europa y América del Norte?

## 📊 Métricas clave

📌 Por plataforma y género:  
- Ventas globales, en NA, EU y JP  
- Número de lanzamientos por año  
- Duración promedio de vida útil

📌 Por producto:  
- Calificación promedio de usuarios y críticos  
- Distribución por clasificación ESRB  
- Comparación de ventas con calificaciones

📌 Estadísticas:  
- Pruebas de hipótesis: diferencias por región y calificación  
- Correlación: reseñas vs ventas  

## 🗂 Descripción del conjunto de datos
Fuente: Ice (datos simulados a partir de ventas históricas)  
Período: 1980 - 2016  
Campos clave:

- `Name`, `Platform`, `Year_of_Release`, `Genre`  
- `NA_sales`, `EU_sales`, `JP_sales`, `Global_sales`  
- `Critic_Score`, `User_Score`, `Rating`

## ⚙️ Proceso de análisis
📌 Realizado en Python usando Pandas, NumPy, Matplotlib, Seaborn y SciPy

### Paso 1: Revisión de datos
✔ Detección y tratamiento de valores faltantes  
✔ Conversión de tipos de datos  
✔ Análisis inicial de distribución de lanzamientos

### Paso 2: Exploración y visualización
✔ Análisis por año, plataforma y género  
✔ Gráficos de barras, cajas y diagramas de dispersión  
✔ Evaluación de ventas en función de las reseñas

### Paso 3: Análisis regional
✔ Comparación entre NA, EU y JP  
✔ Identificación de géneros más vendidos por región  
✔ Preferencias culturales y patrones únicos

### Paso 4: Pruebas estadísticas
✔ Hipótesis: diferencias de ventas según calificación y región  
✔ Uso de pruebas t para validar significancia  

## 📁 Estructura del repositorio
📂 data  
 └── video_game_sales.csv  

📂 notebooks  
 └── Proyecto_Sprint6_FINAL.ipynb  

📂 insights  
 └── summary.md  

## 📬 Contacto
📧 Correo: jessica.elizondo.t@gmail.com  
🔗 LinkedIn: https://www.linkedin.com/in/jessica-elizondo-t
