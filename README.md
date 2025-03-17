 # Teoria
## *Actividad*:
Investigar y realizar un breve resumen de conceptos basicos de ingeligencia artificial y machine learning
## *Objetivos*: Familiarizarse con los terminos y definiciones fundamentales 

## Temas:
     · Inteligencia artificial
     · Tipo de IA:debil,general y super inteligente
     · Machine learning 
     · Tipos de ML
     · Debe incluir definiciones, ejemplos y aplicaciones practicas de IA y ML
     · Confecionarlo en github con fomato markdown


##     Resumen: Conceptos Básicos de Inteligencia Artificial y Machine Learning

## 1. **Inteligencia Artificial (IA)**

La **Inteligencia Artificial** es el campo de estudio de la informática que se centra en crear sistemas capaces de realizar tareas que normalmente requieren de inteligencia humana. Estas tareas incluyen el procesamiento de lenguaje natural, la toma de decisiones, la percepción visual, entre otras.

### Ejemplo:
- **Asistentes virtuales** como Siri y Alexa, que interactúan con los usuarios a través del lenguaje natural.

### Aplicaciones prácticas:
- Diagnóstico médico asistido por IA.
- Sistemas de recomendación en plataformas como Netflix o Spotify.

---

## 2. **Tipos de Inteligencia Artificial**

Existen tres categorías principales de IA:

- **IA débil (o IA estrecha)**: Sistemas diseñados para realizar tareas específicas.
    - Ejemplo: Chatbots, asistentes virtuales.
  
- **IA general (AGI)**: Sistemas capaces de realizar cualquier tarea cognitiva humana. Aún no existe una IA general real.
    - Ejemplo: Un robot que pueda aprender cualquier tarea.

- **IA superinteligente**: Un tipo de IA que supera la inteligencia humana en todos los aspectos. Aún es teórica.
    - Ejemplo: Una IA que puede superar las capacidades intelectuales humanas.

---

## 3. **Machine Learning (ML)**

El **Machine Learning** es una rama de la IA que permite a las máquinas aprender de los datos sin ser explícitamente programadas. Los algoritmos de ML identifican patrones y hacen predicciones o decisiones sin intervención humana directa.

### Ejemplo:
- Un algoritmo que predice el precio de las viviendas.

### Aplicaciones prácticas:
- Reconocimiento de voz y facial.
- Sistemas de recomendación.

---

## 4. **Tipos de Machine Learning**

- **Aprendizaje supervisado**: El algoritmo aprende de datos etiquetados.
    - Ejemplo: Clasificación de correos electrónicos como spam o no spam.

- **Aprendizaje no supervisado**: El algoritmo encuentra patrones sin etiquetas.
    - Ejemplo: Agrupación de clientes en segmentos de mercado similares.

- **Aprendizaje por refuerzo**: El algoritmo aprende tomando acciones en un entorno, recibiendo recompensas o penalizaciones.
    - Ejemplo: Un robot que aprende a jugar al ajedrez.
    - # CONTINUACION
## - En terminos generales, ¿cuando decimos que manejamos grandes volumenes de datosy cuando no?
## - Repasar librarias de python y investigar sobre pip
## - formato csv
## - pandas
## - dataframme y tabulares

## 1)_ 
  Decimos que manejamos grandes volúmenes de datos cuando tenemos que trabajar con conjuntos de datos que superan las capacidades de las herramientas tradicionales de procesamiento, almacenamiento y análisis. Generalmente, esto se refiere a situaciones en las que:

## Volumen:
La cantidad de datos es muy grande. Esto puede variar dependiendo del contexto, pero típicamente hablamos de terabytes o petabytes de información. Por ejemplo, las empresas que manejan grandes cantidades de datos generados por usuarios o sensores en tiempo real.

## Velocidad:
Los datos se generan a una velocidad muy alta. Esto incluye datos de flujos en tiempo real, como los generados por transacciones financieras, redes sociales o sensores de Internet de las Cosas (IoT).

## Variedad:
Los datos provienen de diferentes fuentes y tienen diferentes formatos. Pueden ser estructurados, semi-estructurados o no estructurados, y pueden incluir texto, imágenes, videos, etc.

## Complejidad:
Los datos son difíciles de analizar y procesar debido a su complejidad o a la necesidad de integrar diferentes fuentes y tipos de datos. Esto puede incluir datos dispersos, inconsistentes o mal estructurados.

## ¿Cuándo no manejamos grandes volúmenes de datos?
Cuando el volumen de datos es pequeño o manejable con tecnologías tradicionales como bases de datos relacionales o hojas de cálculo. Por ejemplo, si solo tenemos unos pocos gigabytes de datos que se pueden procesar en un servidor común sin necesidad de infraestructura especializada como Hadoop o bases de datos NoSQL, no estamos manejando grandes volúmenes.

En resumen, los grandes volúmenes de datos se definen en función de la escala del procesamiento y almacenamiento necesarios, la complejidad de los datos y las herramientas que se requieren para manejarlos.

## 2)_
# Librerías en Python
Las librerías en Python son colecciones de módulos, es decir, archivos que contienen definiciones de funciones, clases y variables, que se pueden utilizar para resolver problemas específicos sin necesidad de escribir todo el código desde cero. Algunas librerías populares y ampliamente utilizadas en Python son:

# NumPy:
Es una librería muy utilizada para cálculos numéricos y álgebra lineal. Permite trabajar con matrices, vectores y otras estructuras de datos numéricas de forma eficiente.

## Instalación:
 - pip install numpy

# Pandas: 
Se usa principalmente para manipulación y análisis de datos. Su estructura de datos principal es el DataFrame, que facilita el manejo de datos tabulares.

## Instalación: 
  - pip install pandas

# Matplotlib: 
Es una librería para crear gráficos y visualizaciones en 2D.

## Instalación: 
  - pip install matplotlib

# Requests: 
Esta librería se utiliza para hacer peticiones HTTP de forma sencilla.

## Instalación:
  - pip install requests

# Flask: 
Es un micro-framework para el desarrollo web que facilita la creación de aplicaciones web y APIs.

## Instalación:
  - pip install flask

# TensorFlow/PyTorch:
Son librerías para aprendizaje automático (machine learning) y redes neuronales profundas (deep learning).

## Instalación: 
   - pip install tensorflow o pip install torch

# Scikit-learn: 
Usada para machine learning y análisis de datos. Ofrece herramientas para clasificación, regresión, clustering y más.

## Instalación: 
   - pip install scikit-learn

# BeautifulSoup:
Librería para analizar documentos HTML y XML, comúnmente utilizada para hacer scraping web.

## Instalación:
   - pip install beautifulsoup4

Estas son solo algunas de las miles de librerías disponibles en el ecosistema Python.
# ¿Qué es pip?
pip es el gestor de paquetes para Python. Es una herramienta utilizada para instalar y gestionar librerías y paquetes de Python que se encuentran en el Python Package Index (PyPI). Con pip, puedes instalar, desinstalar y actualizar las librerías en tu entorno de Python de forma sencilla.

## Comandos más comunes de pip:
Instalar un paquete:

bash

pip install nombre_del_paquete
Instalar una versión específica de un paquete:

bash

pip install nombre_del_paquete==versión
Ejemplo:

bash

pip install numpy==1.21.0
Ver los paquetes instalados:

bash
pip list
Esto te muestra todos los paquetes instalados en tu entorno y sus versiones.

Actualizar un paquete:

bash

pip install --upgrade nombre_del_paquete
Desinstalar un paquete:

bash

pip uninstall nombre_del_paquete
Generar un archivo de requerimientos (recomendado para proyectos):

bash

pip freeze > requirements.txt
Esto crea un archivo requirements.txt que contiene las versiones exactas de todos los paquetes que están instalados en tu entorno.

Instalar paquetes desde un archivo de requerimientos:

bash

pip install -r requirements.txt
Esto instala todos los paquetes listados en el archivo requirements.txt.

Uso común de pip con entornos virtuales:
Es muy común utilizar entornos virtuales para mantener las dependencias de un proyecto separadas de otros proyectos. Los pasos básicos serían:
Crear un entorno virtual:

bash

python -m venv nombre_del_entorno
Activar el entorno virtual:

En Windows:
bash
nombre_del_entorno\Scripts\activate

En macOS/Linux:
bash

source nombre_del_entorno/bin/activate
Instalar paquetes dentro del entorno virtual: Con el entorno activado, puedes usar pip para instalar las librerías que necesites.

Desactivar el entorno virtual:

bash

deactivate
¿Cómo buscar paquetes con pip?
Si no sabes el nombre exacto de un paquete o quieres buscar más información sobre paquetes disponibles, puedes usar:

Buscar paquetes:

bash

pip search término_de_búsqueda
Mostrar información de un paquete:

bash

pip show nombre_del_paquete

Resumen
Las librerías en Python son colecciones de módulos que resuelven problemas específicos y facilitan el desarrollo de programas complejos.
pip es el gestor de paquetes de Python, que te permite instalar, desinstalar y gestionar paquetes desde PyPI.
Para usar pip, puedes ejecutar comandos en la terminal para instalar y manejar las librerías según las necesidades de tu proyecto.
Si tienes más dudas sobre alguna librería o necesitas saber algo más sobre pip, ¡no dudes en preguntar!ç

# 5)_Formato csv

Un formato CSV (Comma-Separated Values, en inglés "valores separados por comas") es un tipo de archivo que se utiliza para almacenar datos en formato de texto plano. Este formato es ampliamente utilizado para representar bases de datos, hojas de cálculo y listas de información en forma tabular.

# 4)_ pandas y dataframe
 Resumiendo
  - Pandas: es una librería de Python que proporciona herramientas poderosas para el análisis y manipulación de datos.
  - DataFrame es la estructura de datos principal de Pandas, representando datos en formato tabular (filas y columnas).
  - El formato tabular es muy común en análisis de datos, y Pandas facilita trabajar con estos datos de forma eficiente.

# ¿Cómo Instalar Pandas con pip?

Para instalar la librería **Pandas** en tu entorno de Python, puedes usar el gestor de paquetes **pip**. Aquí te explico cómo hacerlo paso a paso.

## Paso 1: Verificar si pip está instalado

Primero, asegúrate de que **pip** esté instalado en tu sistema. Abre la terminal o línea de comandos y escribe:

```bash
pip --version




