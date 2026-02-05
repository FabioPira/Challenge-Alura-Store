# Análisis de Tiendas – Alura Store

Este proyecto tiene como objetivo analizar el desempeño de las cuatro tiendas de la cadena **Alura Store**, con el fin de recomendar cuál de ellas debería vender el Sr. Juan para iniciar un nuevo emprendimiento.

El análisis se realizó a partir de datos históricos de ventas, considerando indicadores financieros, comportamiento de los clientes y desempeño por categoría de producto.

---

## Objetivo del análisis

Evaluar y comparar las tiendas de Alura Store para identificar la menos eficiente, utilizando métricas clave que permitan una toma de decisión objetiva y fundamentada en datos.

---

## Ítems analizados

En este proyecto se analizaron los siguientes aspectos:

- Ingresos totales por tienda  
- Volumen de ventas (cantidad de productos vendidos)  
- Ventas por categoría de producto  
- Top 5 de categorías con mayor aporte a los ingresos  
- Tienda con mayor participación en las categorías más relevantes  
- Calificación promedio de los clientes por tienda  
- Productos más vendidos y menos vendidos  
- Análisis del costo de envío promedio por tienda  
  - Este indicador fue descartado como factor decisivo, ya que no presenta variaciones significativas entre tiendas y mantiene una proporción constante respecto al precio de venta.

---

## Metodología

1. **Carga y unificación de datos**  
   Se cargaron los datos de las cuatro tiendas desde archivos CSV y se unificaron en un solo DataFrame, asignando correctamente el identificador de tienda a cada registro.

2. **Análisis exploratorio y descriptivo**  
   Se analizaron métricas clave como ingresos, categorías, calificaciones y productos vendidos.

3. **Visualización de datos**  
   Se generaron gráficos utilizando **Matplotlib** para facilitar la interpretación de los resultados y resaltar las diferencias entre tiendas.

4. **Síntesis y conclusión**  
   Se integraron los resultados cuantitativos y visuales para formular una recomendación final.

---

## Herramientas utilizadas

- **Python**
- **Pandas** (manipulación y análisis de datos)
- **Matplotlib** (visualización)
- **Google Colab**
- **GitHub**

---

## Conclusión

A partir del análisis realizado, se concluye que la **Tienda 4** es la opción más adecuada para ser vendida. Esta tienda presenta:

- Los **menores ingresos totales**.
- Un **menor volumen de ventas** en comparación con las demás tiendas.
- Bajo desempeño incluso dentro de las **categorías que mayor aporte realizan a los ingresos** del negocio.

En contraste, las Tiendas 1, 2 y 3 muestran un mejor desempeño financiero 

---

## Autor

**Fabio Pira**  
Proyecto desarrollado como parte del *Challenge de Data Science – Alura Latam*
