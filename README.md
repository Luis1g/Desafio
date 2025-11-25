## **Desafio Practicando Python para Data Science: Challenge Alura Store**

###  **Proposito**

- El propósito del análisis realizado es ayudar al Sr. Juan a decidir que tienda de su cadena Alura Store debe vender para inciar un nuevo emprendimiento. 

### **Estructura**
La estructura del proyecto y organización de los archivos se muestra a continuación;

1. Extracción de los datos
    Los datos de las tiendas se encuentran en 4 archivos CSV de la carpeta "base-de-datos-challenge1-latam". Los datos se extraen y organizan en DatasFlames, utilizando la biblioteca pandas.

2. Analisis
    * Analisis de facturación: Se obtienen los ingresos totales por tienda y se muestran los resultados en una grafica de barras para su mejor comparación.

    * Ventas por categoria: Se analizan el numero de productos vendidos por categoria para las 4 tiendas. La mejor manera de visualizar estos datos es con graficos de pastel. Estos graficos de pastel indican el porcetanje que le corresponde a cada categoria en ventas.

    * valoración media de tienda: Calificación promedio por tienda: Se obtienem el promedio de calificaciones que los consumidores le dan a la tienda donde compraron algún producto.

    * Productos mas y menos vendidos: Se muestran los productos mas y menos vendidos. La función que muestra los resultados se puede modificar para mostrar n producto mas y menos vendidos. 

    * Valor de envio promedio por tienda: ¿Cúal es el costo promedio que el cosumidor debe pagar por envio de su producto? 

### **Graficos**
Los graficos se realizan con el paquete matplotlib y se pueden modificar sin eliminar el "import matplotlib.pyplot as plt" del codigo.

### **Extra**

Analizamos la influencia que puede tener la ubicación de los compradores de la tienda con un mapa interactivo. En el mapa se observa la ubicación a donde se envian las compras.

Se usa folium para crear el mapa interactivo. Este paquete crea un archivo .html que se encarga de mostrar el mapa. 
- Para evitar cualquir error, no modificar este archivo .html.