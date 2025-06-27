# Challenge_Alura_Store


## 📊 1. Propósito del Análisis
Este proyecto de Análisis de Datos usando Python en Google Colab  tiene como objetivo realizar un análisis exploratorio de datos sobre las ventas de la tienda Alura Store. A través del análisis de métricas clave como ingresos, cantidades vendidas, costos de envío y comportamiento por tienda, se busca una recomendación estratégica para el cierre de una tienda, así como identificar oportunidades de mejora y patrones de consumo.

📌 Entre los objetivos específicos destacan:
- Determinar cuál es la tienda más rentable.
- Analizar el desempeño de los productos más y menos vendidos.
- Calcular el costo de envío promedio por tienda.
- Formular una recomendación final sobre qué tienda convendría vender.

## 🏗️ 2. Estructura del Proyecto
a) Análisis del siguiente dataset csv manipulado con pandas:

- **Producto y Categoría:** Artículos vendidos y sus calificaciones.
- **Precio y Envío:** Valores de venta y costos asociados.
- **Fecha y ubicación de compra:** Información temporal y geográfica.
- **Evaluación de compra:** Comentarios de clientes.
- **Tipo de Pago y Cuotas:** Métodos utilizados por los clientes.
- **Coordenadas Geográficas:** Ubicación de las transacciones.

b) Creación de visualizaciones de datos usando la biblioteca Matplotlib.

c) Redacción de un informe final detallado, orientado a la toma de decisiones.


## 👩‍🔬 3. Insights Obtenidos
**📈 Ventas por Tienda**
Se identificó que una tienda genera consistentemente mayores ingresos, lo cual podría deberse a una mejor ubicación o estrategia de precios.

**🔝 Productos Más Vendidos**
Utilizando agrupamiento por producto y sumatoria de cantidades, se hallaron los artículos y categorías más populares, lo cual orienta decisiones de stock y marketing.

**🚚 Costos de Envío**
El análisis del costo de envío promedio por tienda reveló diferencias significativas que pueden estar afectando la rentabilidad.

## 📓 4. Instrucciones para Ejecutar el Notebook
Para ejecutar este análisis en tu entorno local:

Clona el repositorio o descarga los archivos.

```
git clone https://github.com/tu_usuario/AluraStoreLatam.git
cd AluraStoreLatam
```

Instala las dependencias necesarias.
Asegúrate de tener instalado Python 3.8+ y luego ejecuta:

```
pip install pandas matplotlib seaborn jupyter
```

Abre el notebook en Jupyter.

```
jupyter notebook AluraStoreLatamResuelto.ipynb
```

Ejecuta todas las celdas para ver el análisis completo.

Desde el menú de Jupyter: `Cell > Run All`.


O bien, descargando el archivo `.ipnyb` y abriéndolo directamente en Colab [![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Naereen/badges)

