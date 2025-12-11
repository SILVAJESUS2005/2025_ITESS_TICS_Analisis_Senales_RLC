<div align="center">
  
  <br><h1> Simulación y Análisis de Circuito RLC Serie</h1>
  <h3>Análisis de Señales y Sistemas de Comunicación | Ingeniería en TICS</h3>

  <p>
    <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python&logoColor=white" alt="Python">
    <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter">
    <img src="https://img.shields.io/badge/Status-Finalizado-success?style=for-the-badge" alt="Status">
    <br>
    <img src="https://img.shields.io/badge/Numpy-Scientific_Computing-013243?style=flat-square&logo=numpy" alt="Numpy">
    <img src="https://img.shields.io/badge/Scipy-Signal_Processing-0053A0?style=flat-square&logo=scipy" alt="Scipy">
    <img src="https://img.shields.io/badge/Matplotlib-Data_Visualization-11557c?style=flat-square&logo=matplotlib" alt="Matplotlib">
  </p>
</div>

---

##  Descripción del Proyecto

Este proyecto desarrolla una **simulación computacional interactiva** de un circuito RLC en serie, modelado como un sistema lineal de segundo orden.

El objetivo es cerrar la brecha entre la teoría matemática (ecuaciones diferenciales y transformada de Laplace) y la realidad física, permitiendo visualizar cómo los cambios en componentes comerciales ($R, L, C$) afectan drásticamente el comportamiento del sistema en el tiempo y la frecuencia.

###  Características Principales
*  **Modelado Matemático:** Implementación de la Función de Transferencia $H(s)$.
*  **Análisis Temporal:** Visualización de la respuesta al escalón/senoidal (oscilaciones, amortiguamiento).
* Em **Análisis Frecuencial:** Generación automática de diagramas de Bode (Magnitud y Fase).
*  **Automatización:** Script optimizado para generar múltiples casos de estudio con una sola ejecución.

---

##  Tecnologías y Herramientas

Este proyecto fue construido utilizando el ecosistema científico de Python.

| Tecnología | Propósito en el proyecto |
| :--- | :--- |
| <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="30"> **Python** | Lenguaje núcleo para la lógica de simulación. |
| <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/jupyter/jupyter-original-wordmark.svg" width="30"> **Jupyter** | Entorno interactivo para documentar código, texto y resultados. |
| <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/numpy/numpy-original.svg" width="30"> **NumPy** | Manejo eficiente de arrays y cálculos numéricos (vectores de tiempo y frecuencia). |
| <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b2/SCIPY_2.svg/1200px-SCIPY_2.svg.png" width="30"> **SciPy (Signal)** | El motor del proyecto: define las funciones de transferencia (`lti`), simula en el tiempo (`lsim`) y calcula Bode (`bode`). |
| <img src="https://matplotlib.org/_static/images/logo2.svg" width="30"> **Matplotlib** | Generación de las gráficas profesionales de tiempo, espectro y fase. |

---

##  Galería de Resultados

A continuación se presentan algunos de los casos de estudio analizados en el notebook.

| **Caso 1: Subamortiguado (Oscilatorio)** | **Caso 3: Resonancia (Pico Máximo)** |
| :---: | :---: |
| <img src="caso1.png" width="400" alt="Gráfica Caso Subamortiguado"> | <img src="ruta/a/tu/imagen_caso3.png" width="400" alt="Gráfica Caso Resonancia"> |
| *Se observa la oscilación inicial debido a una resistencia baja ($100\Omega$).* | *La frecuencia de entrada coincide con la natural, generando máxima amplificación.* |

<div align="center">

| **Caso 4: Filtro Pasa-Bajas** |
| :---: |
| <img src="caso4.png" width="600" alt="Gráfica Filtro Pasa Bajas"> |
| *A alta frecuencia ($10kHz$), el capacitor atenúa casi por completo la señal de entrada.* |
</div>

---

##  Información Académica

<div align="center">

| Rubro | Detalle |
| :--- | :--- |
| **Institución** | ITESS |
| **Carrera** | Ingeniería en Tecnologías de la Información y Comunicaciones |
| **Materia** | Análisis de Señales y Sistemas de Comunicación |
| **Alumno** | **Jesús López Silva** |
| **Fecha** | Diciembre 2025 |

</div>

---
