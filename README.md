# Astronomía Estelar: Análisis de Datos y Modelado en Python

![Python](https://img.shields.io/badge/Python-Data_Analysis-blue)
![Jupyter](https://img.shields.io/badge/Tools-Jupyter_Notebook-orange)
![License](https://img.shields.io/badge/License-MIT-green)

Este repositorio contiene una colección de 9 proyectos desarrollados como parte de la materia Astronomía Estelar (ciclo 2021A) de la Facultad de Ciencias Astronómicas y Geofísicas de la Universidad Nacional de La Plata (UNLP). 

El objetivo de esta colección es documentar el flujo de trabajo en astrofísica estelar, observacional y teórica, abarcando desde la aplicación de modelos numéricos fundamentales hasta el procesamiento de imágenes FITS, el análisis de series temporales y la interacción con bases de datos astronómicas (SIMBAD, OGLE, Hipparcos).

## 🛠️ Tecnologías y Herramientas

* **Lenguaje:** Python 3
* **Análisis de Datos:** `numpy`, `pandas`
* **Astronomía y Procesamiento:** `astropy`, `astroquery`, `specutils`
* **Visualización:** `matplotlib`
* **Entorno:** Jupyter Notebook

## 🗂️ Índice de Proyectos

Cada carpeta contiene el código fuente en Jupyter Notebook, los conjuntos de datos correspondientes y un informe detallado en formato PDF.

| **ID** | **Nombre del proyecto** | **Descripción** |
| :---: | :--- | :--- |
| **01** | **Radiación Estelar y Cuerpo Negro** | Implementación de la función de Planck y las aproximaciones de Wien y Rayleigh-Jeans. Manejo de unidades físicas y constantes fundamentales. |
| **02** | **Sistema Astronómico de Magnitudes y Colores** | Análisis de sistemas fotométricos (Johnson UBVRI). Convolución de espectros estelares con curvas de sensibilidad de filtros para determinar índices de color. |
| **03** | **Efectos de la Atmósfera Terrestre y Fotometría** | Procesamiento inicial de imágenes FITS. Realización de fotometría de apertura y determinación de la extinción atmosférica mediante la Ley de Bouguer. |
| **04** | **Efecto del Material Interestelar** | Estudio de la extinción y el enrojecimiento interestelar. Automatización de consultas a la base de datos SIMBAD utilizando `astroquery` para obtener parámetros fotométricos. |
| **05** | **Clasificación Espectral I: Ecuaciones de Boltzmann y Saha** | Modelado teórico de atmósferas estelares. Resolución numérica para determinar el equilibrio térmico y las fracciones de ionización/excitación del Hidrógeno en función de la temperatura. |
| **06** | **Clasificación Espectral II** | Análisis de espectros unidimensionales utilizando `specutils`. Identificación de líneas de absorción para clasificar estrellas en el sistema Morgan-Keenan. |
| **07** | **Velocidades Radiales y Efecto Doppler** | Análisis de series temporales espectrales. Medición de desplazamientos de líneas (He I, Na I) y ajuste de modelos matemáticos sinusoidales para inferir parámetros dinámicos de sistemas estelares. |
| **08** | **Diagrama Hertzsprung-Russell** | Procesamiento de catálogos masivos (>2000 estrellas de Hipparcos). Creación de diagramas multidimensionales para correlacionar luminosidad, temperatura, metalicidad y gravedad superficial. |
| **09** | **Estrellas Variables como Indicadores de Distancia** | Análisis poblacional de estrellas Cefeidas en las Nubes de Magallanes (datos OGLE). Construcción de la relación período-luminosidad para la medición de distancias galácticas. |
