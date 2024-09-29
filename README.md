
# ENTORNOS DE CONDA PARA DIFERENTES PROYECTOS 

## Índice
1. [Descripción General](#descripción-general)
2. [Instalación](#instalación)
3. [Uso](#uso)
4. [Entornos Disponibles](#entornos-disponibles)


## Descripción General
Este proyecto tiene como objetivo proporcionar entornos de Conda preconfigurados para el desarrollo de pipelines de bioinformática. 
Está dirigido a científicos, investigadores y cualquier persona interesada en la bioinformática, facilitando la instalación y uso de herramientas esenciales en este campo.

Cada entorno está diseñado para cubrir necesidades específicas dentro de la bioinformática, con un enfoque en la organización y simplicidad.
Utiliza canales como conda-forge, bioconda y defaults, e incluye programas básicos como FastQC y otros necesarios para el análisis de datos biológicos.

Este proyecto nace de una necesidad personal para mantener organizados mis entornos de trabajo y compartir esta organización con la comunidad,
permitiendo que otros también puedan beneficiarse de estos entornos preconfigurados para sus propios proyectos.

## Instalación
### 1. Instalar Conda
Conda es un gestor de entornos y paquetes. Conda facilita la instalación de la mayoría de los paquetes que necesitamos, aunque no todo está disponible de forma predeterminada. 
Su verdadero valor radica en la gestión eficiente de entornos, evitando conflictos de versiones entre programas. 
Por ejemplo, si el Programa A necesita una versión de una librería, pero el Programa C requiere otra, Conda permite crear entornos separados para que ambos funcionen sin problemas. 
Además, verifica automáticamente las dependencias al instalar nuevos paquetes, mejorando la reproducibilidad y simplificando el manejo de entornos.

Si no tienes Conda instalado, puedes instalar Miniconda. Aquí te dejo las instrucciones: 
  La página de descarga de Miniconda es: [aqui](https://conda.io/en/latest/miniconda.html). 
  Sigue las instrucciones de instalación según tu sistema operativo.

### 2. Comandos basicos: 
<img width="939" alt="Captura de pantalla 2024-09-29 a las 20 26 42" src="https://github.com/user-attachments/assets/135c239c-1d14-4235-b575-8cb55fbe83c5">
      
## Uso
Los diferentes entornos de Conda en este repositorio están diseñados para ser utilizados en una variedad de proyectos de bioinformática que iré subiendo con el tiempo. 
Cada entorno está configurado con las herramientas y bibliotecas necesarias para facilitar tareas específicas, asegurando que cada proyecto funcione sin problemas y sin conflictos de dependencias.

A medida que vayas explorando los proyectos, encontrarás instrucciones detalladas sobre cómo utilizar cada entorno en particular. Esto incluirá:

1. Activación del entorno: Antes de ejecutar cualquier script o análisis, necesitarás activar el entorno correspondiente. Esto se hace con el siguiente comando:
```bash
conda activate nombre-del-entorno
```
2. Ejecución de scripts: Una vez activado el entorno, podrás ejecutar los scripts o programas diseñados para ese proyecto específico.
Las instrucciones sobre cómo hacerlo estarán incluidas en cada proyecto.

3. Dependencias y versiones: Cada entorno está configurado para trabajar con versiones específicas de bibliotecas, lo que mejora la reproducibilidad de los resultados.
4. Si es necesario, se proporcionará información sobre cómo instalar paquetes adicionales o realizar ajustes en el entorno.



## Entornos Disponibles
1. Basic_env
2. Genomic_Human



