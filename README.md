# Desafío Alura Store: Análisis de Datos para Toma de Decisiones

> **Proyecto Práctico de Data Science con Python**

Este proyecto forma parte del **Challenge Alura Store**. El objetivo principal es aplicar técnicas de análisis exploratorio de datos (EDA) para resolver un problema de negocio real.

## Propósito del Proyecto
El cliente, el **Sr. Juan**, necesita tomar una decisión estratégica sobre su cadena de tiendas "Alura Store". El objetivo de este análisis es evaluar el rendimiento de las 4 sucursales para determinar **cuál tienda debe ser vendida** o cerrada para financiar un nuevo emprendimiento.

La decisión se basa en métricas clave como facturación, satisfacción del cliente y eficiencia logística.

## Tecnologías y Herramientas
* **Lenguaje:** Python 3
* **Manipulación de Datos:** Pandas
* **Visualización:** Matplotlib
* **Análisis Geoespacial:** Folium, NumPy

## Estructura del Análisis

### 1. Extracción y Limpieza de Datos
Los datos históricos se encuentran distribuidos en 4 archivos CSV dentro de la carpeta `base-de-datos-challenge1-latam`.
* Se utilizó **Pandas** para la ingesta de datos.
* Se unificaron los archivos en **DataFrames** estructurados para su procesamiento.

### 2. Dimensiones del Análisis
El estudio se centró en 5 indicadores clave de rendimiento (KPIs):

* **Facturación Total:** Comparativa de ingresos brutos por sucursal (Gráfico de Barras).
* **Ventas por Categoría:** Análisis de la composición del inventario y preferencias de consumo (Gráficos de Pastel).
* **Satisfacción del Cliente:** Cálculo de la valoración media (rating) otorgada por los compradores.
* **Top & Bottom Products:** Identificación de los productos más vendidos (Best-sellers) y los de menor rotación. *Nota: La función permite ajustar "n" para ver el top 3, 5 o 10.*
* **Costos Logísticos:** Análisis del valor promedio de envío por tienda.

### 3. Visualización Geoespacial (Extra)
Para entender la cobertura de mercado, se realizó un análisis geográfico utilizando **coordenadas de latitud y longitud**.

* **Herramienta:** Folium.
* **Técnica:** Se mapearon las ubicaciones de entrega de los clientes.
* **Resultado:** Se genera un archivo `mapa_ventas.html`.
    * *Importante:* Este archivo es interactivo y se abre con cualquier navegador web. No debe modificarse manualmente para evitar errores de renderizado.

## Cómo ejecutar el proyecto

1. Asegúrate de tener las librerías instaladas:
   ```bash
   pip install pandas matplotlib folium numpy