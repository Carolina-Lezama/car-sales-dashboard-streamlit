# car-sales-dashboard-streamlit

## Aplicación Web de Análisis de Vehículos

## Descripción del Proyecto

Esta aplicación web interactiva fue desarrollada como parte del Sprint 7 enfocado en herramientas de desarrollo de software. El objetivo principal es demostrar habilidades prácticas en el desarrollo completo de una aplicación de datos, desde el análisis exploratorio hasta el despliegue en la nube.

El proyecto integra análisis de datos, visualización interactiva y desarrollo web, permitiendo a los usuarios explorar información de vehículos en venta de forma dinámica.

---

## Objetivo

- Construir una aplicación web interactiva para análisis de datos
- Aplicar análisis exploratorio (EDA)
- Implementar visualizaciones dinámicas
- Desplegar una aplicación funcional en la nube

---

## Dataset

Archivo utilizado:
- vehicles_us.csv

El dataset contiene información sobre anuncios de venta de vehículos, incluyendo:

- Precio
- Kilometraje (odometer)
- Año del vehículo
- Tipo de vehículo
- Condición
- Otras características relevantes

---

## Funcionalidades

La aplicación permite a los usuarios:

- Visualizar histogramas de variables numéricas
- Crear diagramas de dispersión para analizar relaciones entre variables
- Generar gráficos de forma dinámica mediante:
  - Botones
  - Checkboxes
- Interfaz adaptable a distintos dispositivos

---

## Visualizaciones Implementadas

- Histograma:
  - Distribución del kilometraje de los vehículos

- Gráfico de dispersión:
  - Relación entre variables como precio vs kilometraje

---

## Metodología

### 1. Análisis Exploratorio de Datos (EDA)

- Realizado en Jupyter Notebook
- Uso de Plotly para visualizaciones iniciales
- Identificación de patrones y relaciones entre variables

### 2. Desarrollo de la Aplicación

- Framework: Streamlit
- Manipulación de datos con Pandas
- Visualizaciones interactivas con Plotly

### 3. Despliegue

- Plataforma: Render
- Integración con GitHub
- Configuración de entorno mediante requirements.txt

---

## Tecnologías Utilizadas

- Python
- Pandas
- Plotly
- Streamlit
- Jupyter Notebook
- Git y GitHub
- Render

---

## Cómo Ejecutar el Proyecto Localmente

1. Clonar el repositorio:

git clone <repo_url>


2. Crear entorno virtual:

python -m venv env


3. Activar entorno:

source env/bin/activate (Linux/Mac)
env\Scripts\activate (Windows)

4. Instalar dependencias:

pip install -r requirements.txt

5. Ejecutar la aplicación:

streamlit run app.py
---

## Aplicación en Producción

La aplicación está desplegada y disponible en:

https://projecto-7.onrender.com

Nota: En el plan gratuito de Render, la aplicación puede tardar unos segundos en activarse si estuvo inactiva.

---

## Conclusiones

- Se desarrolló exitosamente una aplicación web interactiva funcional
- Streamlit permite crear dashboards de forma rápida y eficiente
- Plotly facilita la visualización dinámica de datos
- El despliegue en la nube permite compartir el proyecto públicamente

---

