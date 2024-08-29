# Análisis de Clientes del Mall usando KMeans Clustering

Este proyecto utiliza un dataset de clientes de un centro comercial para realizar un análisis de segmentación de clientes utilizando el algoritmo de clustering KMeans. A través de este análisis, se busca identificar grupos de clientes con características similares basadas en su edad, ingreso anual y puntaje de gasto.

## Requisitos

El código fue desarrollado y ejecutado en Google Colab, por lo que no es necesario instalar dependencias localmente si utilizas esta plataforma. Sin embargo, si decides ejecutar el código localmente, necesitarás instalar las siguientes librerías de Python:

- pandas
- scikit-learn
- matplotlib
- seaborn
- mpl_toolkits

Puedes instalarlas utilizando pip:

```bash
pip install pandas scikit-learn matplotlib seaborn
```

# Análisis de Clientes del Mall usando KMeans Clustering

Este proyecto utiliza un dataset de clientes de un centro comercial para realizar un análisis de segmentación de clientes utilizando el algoritmo de clustering KMeans. A través de este análisis, se busca identificar grupos de clientes con características similares basadas en su edad, ingreso anual y puntaje de gasto.

## Descripción del Código

### Carga y Exploración del Dataset:

- Se carga el dataset `Mall_Customers.csv` y se realiza una exploración inicial para verificar la existencia de valores nulos y analizar las características de las variables.

### Preprocesamiento de Datos:

- Se seleccionan las variables `Age`, `Annual Income (k$)` y `Spending Score (1-100)` para el análisis, excluyendo `CustomerID` y `Genre`.
- Se normalizan los datos utilizando `StandardScaler` para garantizar que todas las variables tengan la misma escala.

### Aplicación de KMeans:

- Se aplica el algoritmo de KMeans para segmentar a los clientes en 3 clusters.

### Análisis y Visualización:

- Se añaden los resultados del clustering al DataFrame original y se visualiza la distribución de los clusters.
- Se crean gráficos para observar las relaciones entre las variables y cómo se agrupan los clientes en función de los clusters.

### Visualización 3D:

- Se realiza una visualización 3D de los clusters en función de la edad, ingreso anual y puntaje de gasto de los clientes.

## Ejecución en Google Colab

Para ejecutar este proyecto en Google Colab, sigue estos pasos:

1. Sube el archivo `Mall_Customers.csv` a tu entorno de Google Colab.
2. Copia y pega el código en una celda de código en Google Colab.
3. Ejecuta la celda y observa los resultados directamente en tu navegador.

## Resultados

El análisis permite identificar diferentes grupos de clientes con características similares, lo que puede ser útil para estrategias de marketing, análisis de comportamiento del consumidor, entre otros.

## Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue o realiza un pull request para mejoras o nuevas ideas.
