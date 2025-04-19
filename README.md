# 🛍️ Análisis Comparativo de Tiendas - Alura Store

Este proyecto realiza un análisis comparativo entre cuatro tiendas virtuales de **Alura Store**, utilizando datos de ventas, calificaciones de productos, costos de envío y categorías de productos.

## 📊 Objetivo

El objetivo es identificar diferencias clave entre las tiendas en cuanto a:

- Ingresos generados  
- Calificación promedio de productos  
- Costo promedio de envío  
- Distribución de ventas por categoría  
- Productos más y menos vendidos

## 📁 Datos Utilizados

Los datos provienen de archivos `.csv` disponibles públicamente en el repositorio de [Alura Latam - Challenge Data Science](https://github.com/alura-es-cursos/challenge1-data-science-latam).

Archivos utilizados:

- `tienda_1.csv`
- `tienda_2.csv`
- `tienda_3.csv`
- `tienda_4.csv`

Cada archivo contiene información sobre productos vendidos, incluyendo:

- Nombre del producto  
- Precio  
- Categoría  
- Calificación  
- Costo de envío  

## 🧪 Herramientas y Librerías

- `pandas` – manipulación de datos  
- `seaborn` – visualización avanzada  
- `matplotlib` – gráficos personalizados  

## 📈 Visualizaciones Generadas

1. **Bar plots**:
   - Ingresos por tienda
   - Calificación promedio
   - Costo de envío
2. **Gráfico de barras por categoría**: ventas de productos por tipo
3. **Top 5 más y menos vendidos**: visualización por tienda

## 🚀 Ejecución del Proyecto

Para ejecutar el análisis:

1. Asegúrate de tener Python 3 y las siguientes librerías instaladas:

```
pip install pandas matplotlib seaborn
```

2. Ejecuta el script Python en un entorno como Jupyter Notebook o Google Colab.

3. El script descargará automáticamente los datos y generará visualizaciones.

## 🛠️ Notas Técnicas

- Se evitó el uso de columnas inexistentes mediante validación previa.
- Se eliminaron advertencias (`FutureWarning`) de Seaborn usando `hue` y `legend=False`.

## ✅ Resultado Esperado

Un conjunto de gráficos que permiten comparar el rendimiento y comportamiento de cada tienda, brindando insights claros para la toma de decisiones estratégicas.

## 🚧 Próximos Pasos / Mejoras

- 📅 Incorporar análisis temporal si se incluyen fechas de venta.
- 📦 Analizar relación entre categorías y calificación del producto.
- 💰 Incluir métricas de margen de ganancia si se cuenta con costos.
- 🌎 Geolocalización de ventas.


---

