# codigos-tfg-tranvia
# Evaluación Ambiental y Dispersión Atmosférica - Ampliación Tranvía de Murcia

Repositorio con el código en Python desarrollado para la modelización de la dispersión de contaminantes, el cálculo de la neutralidad de carbono y el diagrama de araña correspondientes al Trabajo de Fin de Grado 'Análisis del impacto ambiental de la ampliación del
Tranvía en Murcia' (Grado en Física, Universidad de Murcia). 

El proyecto analiza el impacto físico-ambiental de la ampliación de la red del Tranvía desde la Plaza Circular hacia los barrios del sur (El Carmen y El Palmar).

##  Contenido del repositorio

* **`codigos-tfg-ampliacion-tranvia-jfng.ipynb`**: Cuaderno de Jupyter interactivo con el análisis completo, paso a paso, incluyendo el tratamiento de datos y la generación de gráficas.
* **`codigos-tfg-ampliacion-tranvia-jfng.html`**: Versión estática exportada del cuaderno para su visualización directa en el navegador sin necesidad de ejecutar código.
* **`codigos-tfg-ampliacion-tranvia-jfng.py`**: Script de Python consolidado con la implementación del modelo gaussiano de dispersión atmosférica.
* **`dispersion_NOx_PM25.png`**: Mapa de isolíneas generado por el modelo mostrando la dispersión de NOx y PM2.5 sobre el callejero.
* **`emisiones_evitadas_pentagono (1).png`**: Gráfico radial que ilustra la reducción de los diferentes contaminantes tras la implementación del proyecto.
* **`neutralidad carbono (1).png`**: Gráfica del punto de equilibrio (payback) para alcanzar la neutralidad de carbono en función del ciclo de vida del proyecto.

##  Herramientas y Librerías

El análisis y las simulaciones se han desarrollado utilizando el siguiente ecosistema de librerías de Python:
* `numpy` y `scipy`: Para el cálculo matricial y la implementación matemática del modelo gaussiano.
* `matplotlib`: Para la generación de gráficos de evaluación ambiental.
* `contextily` y `pyproj`: Para el renderizado de mapas base georreferenciados y transformaciones de coordenadas.

##  Ejecución

Para reproducir el modelo de dispersión atmosférica localmente, instala las dependencias necesarias y ejecuta el script principal:

```bash
pip install numpy scipy matplotlib contextily pyproj
python codigos-tfg-ampliacion-tranvia-jfng.py
