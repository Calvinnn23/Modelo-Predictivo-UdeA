# Modelo Predictivo UdeA - Pruebas Saber Pro Colombia

Este repositorio contiene el desarrollo de un modelo predictivo implementado en Python como parte del proyecto **UDEA/ai4eng 20242**. El objetivo principal es predecir el rendimiento de los estudiantes en las **Pruebas Saber Pro** de Colombia.

## Objetivo del Proyecto

Las **Pruebas Saber Pro** son exámenes estandarizados administrados en Colombia para evaluar la calidad y el nivel de conocimiento de los estudiantes de educación superior. Estas pruebas abarcan cinco componentes genéricos:

1. Inglés  
2. Lectura Crítica  
3. Competencias Ciudadanas  
4. Razonamiento Cuantitativo  
5. Comunicación Escrita  

### **Tarea:**  
Crear un modelo de clasificación que prediga el rendimiento global de los estudiantes en las pruebas Saber Pro. El desempeño será clasificado en una de las siguientes categorías:

- **Bajo**
- **Medio-Bajo**
- **Medio-Alto**
- **Alto**

### **Métrica de Evaluación:**  
La evaluación del modelo se realiza utilizando **accuracy** (precisión), es decir, el porcentaje de aciertos que obtiene el modelo sobre los datos de prueba.

## Estructura del Repositorio

El repositorio está organizado en tres entregas que reflejan el flujo completo del proyecto:

- **Entrega 1 - Exploración de Datos:**  
  Análisis exploratorio del dataset para entender las características sociodemográficas y académicas de los estudiantes. Incluye visualizaciones, estadísticas descriptivas y detección de valores atípicos.

- **Entrega 2 - Preprocesamiento y Limpieza de Datos:**  
  Tratamiento de valores faltantes, codificación de variables categóricas, normalización y transformación de datos. Esta fase asegura que los datos estén listos para ser utilizados en el modelado.

- **Entrega Final - Entrenamiento y Ajuste de Modelos Predictivos:**  
  Entrenamiento de tres modelos de clasificación distintos, ajuste de hiperparámetros y evaluación comparativa de su desempeño. Se selecciona el modelo con mejor rendimiento para la predicción final.

## Descripción del Conjunto de Datos

El conjunto de datos incluye aproximadamente **700,000 registros** de estudiantes y contiene las siguientes categorías de información:

- **Información Socioeconómica:**  
  Datos como el estrato socioeconómico del estudiante, nivel educativo de los padres, entre otros.

- **Información Académica:**  
  Detalles como el programa de estudios, institución educativa, entre otros factores relacionados al rendimiento académico.

