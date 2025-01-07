# Optimización Numérica y Combinatoria  

Este proyecto aborda dos importantes problemas de optimización: **optimización numérica** y **optimización combinatoria**, implementando diversos algoritmos para explorar su desempeño.  

## Objetivo del Proyecto  

El objetivo es aplicar y analizar diferentes técnicas de optimización, tanto clásicas como heurísticas, para resolver problemas específicos:  

### Parte 1: Optimización Numérica  
- Se optimizan funciones de prueba comunes en dos y tres dimensiones:  
  - Función de Rosenbrock   
  - Función Goldstein-Price  

- **Algoritmos implementados**:  
  1. **Método de descenso por gradiente** con condiciones iniciales aleatorias.  
  2. **Métodos heurísticos**:  
     - Algoritmos evolutivos  
     - Optimización por enjambre de partículas  
     - Evolución diferencial  

- **Visualizaciones**:  
  Se incluyen GIFs animados y videos que muestran el proceso de optimización, tanto para el descenso por gradiente como para los métodos heurísticos.  

- **Discusión**:  
  Se comparan los resultados en términos del valor final de la función objetivo y el número de evaluaciones realizadas.  

### Parte 2: Optimización Combinatoria  
- **Problema abordado**: El problema del vendedor viajero aplicado a las 32 capitales de los Estados Unidos Mexicanos.  
  - El costo de desplazamiento entre ciudades considera:  
    - El valor de la hora del vendedor (parámetro ajustable).  
    - El costo de los peajes.  
    - El costo del combustible, basado en el vehículo elegido.  

- **Algoritmos implementados**:  
  1. Algoritmo de colonias de hormigas  
  2. Algoritmos genéticos  

## Requisitos de Ejecución  

Para ejecutar los notebooks:  
1. **Descargar los archivos del repositorio**.  
2. Asegurarse de que las rutas a los archivos CSV (o de datos) sean correctas.  
3. Ejecutar las celdas correspondientes en los Jupyter Notebooks.  

**Nota importante**: El proyecto está diseñado para ser reproducible. Por favor, verifique que las dependencias necesarias están instaladas en su entorno (puede consultar los encabezados de cada notebook para más detalles).  
