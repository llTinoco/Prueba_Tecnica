# README - Prueba Técnica: Construcción de una Base de Datos y Análisis Básico

## Objetivo
Este ejercicio tuvo como finalidad evaluar habilidades técnicas en la manipulación y análisis de datos utilizando herramientas como Excel, Power BI y Python. El objetivo principal fue construir una base de datos estructurada y realizar análisis básicos para extraer información útil.

## Herramienta Utilizada
Para esta prueba se utilizó **Python**, aprovechando sus capacidades para la manipulación de datos con **pandas** y la normalización de estructuras de bases de datos.

## Desarrollo del Ejercicio

### Parte 1: Construcción de la Base de Datos
1. **Importación de Datos**
   - Se partió de una tabla con datos sobre ventas, incluyendo cliente, producto, categoría, cantidad, precio unitario, región y fecha.
   - Se cargaron los datos en un DataFrame de pandas.
   
2. **Normalización de Datos**
   - Se identificaron redundancias en los datos.
   - Se crearon tablas separadas para **clientes, productos y regiones** para mejorar la organización y evitar duplicaciones.
   - Se establecieron relaciones entre las tablas para formar una estructura relacional adecuada.
   
3. **Exportación de la Base de Datos**
   - Una vez estructurada la base de datos, se exportó a un archivo en formato .csv o .xlsx para facilitar su posterior análisis.

### Parte 2: Análisis Básico
1. **Cálculo del Total de Ingresos por Región**
   - Se agruparon los datos por región y se calculó el ingreso total (Cantidad * Precio Unitario).

2. **Identificación del Cliente con Mayor Volumen de Compra**
   - Se agruparon las ventas por cliente y se sumaron las cantidades de productos comprados.
   - Se identificó el cliente con mayor volumen de compra.

3. **Ingreso Promedio por Categoría de Producto**
   - Se agruparon los datos por categoría de producto y se calculó el ingreso promedio.

### Parte 3: Consulta Adicional (Opcional)
- Se implementó un análisis de los **productos más vendidos**, basado en la cantidad total de unidades vendidas.
- Este análisis puede ser útil para la toma de decisiones en estrategias de inventario y ventas.

## Resultados
Los resultados de los cálculos fueron generados y presentados en formato de tabla en Python, mostrando métricas clave para el análisis de ventas.

## Conclusiones
- **La normalización de la base de datos permitió eliminar redundancias y mejorar la organización de los datos.**
- **El uso de pandas facilitó la manipulación y análisis de los datos, permitiendo cálculos rápidos y eficientes.**
- **La segmentación de ingresos y volumen de compra proporcionó información valiosa para la toma de decisiones estratégicas.**

## Archivos Entregables
- **Script en Python (.py)** con la construcción y análisis de la base de datos.
- **Archivo .csv o .xlsx** con la base de datos normalizada y los resultados de los cálculos.

