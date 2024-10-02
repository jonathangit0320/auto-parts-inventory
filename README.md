# Análisis de Datos de Almacén (WMS)

Este proyecto utiliza un conjunto de datos de piezas de automóviles para realizar un análisis de gestión de almacenes (WMS) utilizando SQLite, Pandas y visualizaciones con Matplotlib y Seaborn.

## Descripción

El objetivo de este proyecto es crear una base de datos que almacene información sobre piezas de automóviles, incluyendo datos de almacenamiento, categorías de productos y unidades disponibles. Se realizan varios análisis para evaluar el inventario y ayudar en la toma de decisiones.

## Estructura de la Base de Datos

La base de datos `AUTO_PARTS.db` contiene una tabla llamada `LOCATION_WMS` con las siguientes columnas:

- `storage_date` (DATE): Fecha de recepción de la pieza.
- `location` (TEXT): Ubicación en el almacén.
- `item` (TEXT): Identificador del producto.
- `product` (TEXT): Nombre del producto.
- `category` (TEXT): Categoría del producto.
- `units` (INTEGER): Cantidad de unidades en almacenamiento.

## Análisis Realizados

1. **Conteo de Productos por Categoría**: Se cuenta cuántos productos hay en cada categoría.
2. **Total de Unidades por Ubicación**: Se calcula el total de unidades almacenadas en cada ubicación.
3. **Filtrar Productos con Bajo Stock**: Se identifican productos con menos de un umbral específico de unidades.
4. **Visualización de Productos por Categoría**: Se crea un gráfico de barras que muestra el número de productos por categoría.

## Requisitos

- Python 3.x
- Pandas
- Matplotlib
- Seaborn
- SQLite3

## Instalación

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu_usuario/tu_repositorio.git
   cd tu_repositorio

