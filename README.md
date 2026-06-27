# InvestAI

# Proyecto: Sistema Web para Apoyo en Decisiones de Inversión usando Inteligencia Artificial

## 1. Descripción General del Proyecto
El presente repositorio aloja los archivos fuente correspondientes a la capa de frontend e Interfaz Gráfica de Usuario (GUI) del Sistema Web para Apoyo en Decisiones de Inversión. Este desarrollo se ha estructurado bajo el paradigma de Programación Asistida por Inteligencia Artificial (AI-Assisted Programming), utilizando plataformas generativas (modelos de lenguaje) para producir código funcional y de nivel profesional a partir de especificaciones de requisitos e instrucciones detalladas (prompts).

## 2. Arquitectura Integrada del Sistema
Las interfaces diseñadas reflejan la interacción con la arquitectura subyacente del sistema integral, la cual consta de los siguientes componentes principales:

* **Capa de Ingesta de Datos:** Recepción de información financiera en tiempo real e histórica a través de las APIs de Interactive Brokers, Yahoo Finance y CoinMarketCap.
* **Módulo Core - Modelos Predictivos:** Integración visual de 16 modelos predictivos de Inteligencia Artificial para tareas de clasificación y regresión. Estos incluyen algoritmos como Support Vector Classifier (SVC), Long Short-Term Memory (LSTM), XGBoost, y Procesamiento de Lenguaje Natural (NLP) aplicado a noticias financieras mediante VADER y modelos LLM.
* **Módulos de Estrategia y Backtesting:** Interfaces para la configuración de estrategias de inversión (ej. estrategias de opciones financieras) y visualización de reportes de backtesting procesados con VectorBT, incluyendo los ratios de Sharpe, Sortino y Calmar.
* **Capa de Salida (Dashboards):** Implementación gráfica de tableros de control interactivos, permitiendo la visualización de datos, la toma de decisiones y el envío de señales de operación directas al broker.

## 3. Estructura de Directorios y Funcionalidades
Los archivos se encuentran organizados rigurosamente por módulo de acuerdo con la Especificación de Requisitos de Software (ERS) elaborada previamente. La estructura de diseño abarca:

1. Autenticación de Usuario y Control de Acceso.
2. Visualización de Datos del Mercado.
3. Predicción de Tendencias con SVM y Pronóstico de Precios con LSTM.
4. Análisis de Noticias Financieras mediante NLP.
5. Generación de Estrategias de Inversión y Gestión de Portafolio.
6. Envío de Señales al Broker y Reportes de Backtesting.
7. Dashboard Consolidado de Resultados y Consola de Control de Modelos de IA.

## 4. Instrucciones de Ejecución
1. Proceder con la clonación de este repositorio en el entorno de desarrollo local.
2. Acceder al directorio correspondiente a cada módulo funcional.
3. Para los módulos estáticos y dinámicos construidos en HTML, CSS y JS vanilla, ejecutar los archivos `.html` de manera directa en un navegador web actualizado, sin necesidad de dependencias externas.


## 6. Información Institucional y Autoría
* **Institución:** Universidad Nacional Mayor de San Marcos (UNMSM)
* **Facultad:** Facultad de Ingeniería de Sistemas e Informática
* **Curso:** Introducción al Desarrollo de Software (iDeSo)
* **Fase:** Semana 10 - Diseño GUI con IA Generativa
* **Docente:** Prof. Mg. Ing. Ernesto D. Cancho-Rodríguez, MBA

**Equipo de Trabajo:**
* Adrian Garcia Prado
* Diego Gabriel Jimenez Aguilar
* Abigail Lorena Aroste Lapa
* Alonso Santiago Huayta Bonzano
* Gianpier Joseph Alvarado Veliz
* Cristopher Josue Salazar Huamani
