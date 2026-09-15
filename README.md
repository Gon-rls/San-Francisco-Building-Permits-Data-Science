# **Ciencia de Datos para permisos de construcción en San Francisco**

## **Análisis exploratorio de permisos de construcción**

Este proyecto presenta un análisis exploratorio de datos sobre los permisos de construcción registrados en la ciudad de San Francisco.

El objetivo es explorar y comprender las características de los permisos, identificar patrones en su distribución, analizar las variables disponibles y estudiar cómo se relacionan factores como el tipo de permiso, el coste estimado, la fecha y la ubicación con la actividad de construcción en la ciudad.

El proyecto se centra en la limpieza, preparación, exploración y visualización de los datos como base para futuros análisis más avanzados.

## **Descripción del proyecto**

El conjunto de datos contiene información sobre permisos de construcción emitidos en San Francisco, incluyendo variables relacionadas con:

* Tipo de permiso.
* Fechas de creación y finalización.
* Coste estimado de los proyectos.
* Estado del permiso.
* Distrito y ubicación geográfica.
* Información relacionada con el desarrollo de los proyectos.

A lo largo del proyecto se realiza un proceso completo de análisis exploratorio para comprender la estructura y calidad de los datos antes de extraer conclusiones.

## **Proceso de análisis**

El proyecto se ha desarrollado siguiendo las siguientes etapas:

### **1. Carga y exploración inicial**

* Carga del conjunto de datos utilizando Pandas.
* Revisión de la estructura y dimensiones del dataset.
* Análisis de los tipos de datos.
* Exploración inicial de las variables disponibles.

### **2. Limpieza y preparación de los datos**

* Identificación y análisis de valores faltantes.
* Eliminación de variables con un porcentaje elevado de valores nulos.
* Tratamiento de valores faltantes mediante diferentes estrategias según el tipo de variable.
* Preparación de variables para facilitar su posterior análisis.

### **3. Análisis exploratorio**

Se estudian las principales características del conjunto de datos mediante diferentes técnicas de análisis y visualización:

* Distribución de variables numéricas mediante histogramas y boxplots.
* Análisis de variables categóricas mediante gráficos de frecuencia.
* Estudio de posibles valores atípicos.
* Análisis de las relaciones entre variables numéricas mediante una matriz de correlación.
* Estudio de los costes estimados según el tipo de permiso.
* Análisis de la distribución temporal de los permisos según el día de la semana.

### **4. Análisis geográfico**

La información geográfica disponible permite estudiar la distribución espacial de los permisos.

Para ello se utilizan las coordenadas de los registros y se crea un mapa interactivo con Folium que permite visualizar las zonas donde se concentra la actividad relacionada con los permisos de construcción.

## **Preguntas de análisis**

A través del análisis exploratorio se busca investigar cuestiones como:

* ¿Cómo se distribuyen los permisos de construcción en la ciudad?
* ¿Qué tipos de permisos aparecen con mayor frecuencia?
* ¿Existen diferencias en el coste estimado según el tipo de permiso?
* ¿Cómo se distribuyen los permisos a lo largo de la semana?
* ¿En qué zonas de San Francisco se concentra una mayor actividad de construcción?
* ¿Qué patrones pueden identificarse a partir de las variables disponibles?

El análisis realizado permite establecer una base para futuros estudios relacionados con los tiempos de tramitación y otros factores asociados a los permisos de construcción.

## **Tecnologías utilizadas**

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Folium
* Google Colab

## **Principales áreas analizadas**

El proyecto combina diferentes perspectivas para obtener una visión general de los datos:

### **Calidad de los datos**

Análisis de valores faltantes, tipos de variables y preparación del dataset.

### **Distribución de los permisos**

Estudio de las variables numéricas y categóricas para identificar patrones y comportamientos relevantes.

### **Coste estimado**

Análisis de las diferencias en el coste de los proyectos según las características de los permisos.

### **Componente temporal**

Exploración de la distribución de permisos según diferentes variables relacionadas con las fechas.

### **Componente geográfico**

Visualización de la localización de los permisos mediante coordenadas y un mapa interactivo de San Francisco.

## **Posibles siguientes pasos**

El análisis exploratorio realizado permite preparar el conjunto de datos para futuras fases del proyecto.

Algunas posibles líneas de continuación son:

* Análisis más detallado de los tiempos de tramitación.
* Creación de nuevas variables a partir de la información temporal.
* Estudio de los factores que pueden estar relacionados con la duración de los permisos.
* Desarrollo de modelos predictivos para estimar el tiempo de tramitación.

## **Estado del proyecto**

**Completado: Análisis Exploratorio de Datos (EDA)**

El proyecto incluye las fases de exploración, limpieza, tratamiento de valores faltantes, análisis estadístico y visualización de los permisos de construcción.

El trabajo actual proporciona una base preparada para continuar profundizando en el análisis y desarrollar futuras extensiones del proyecto.
