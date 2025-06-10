[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/Zu4fxsIs)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=19684116)
# 📊 Plataforma de Análisis del Mercado Laboral Tecnológico 

## 👋 Introducción

Bienvenido a la **Plataforma de Análisis del Mercado Laboral Tecnológico**, una herramienta diseñada para proporcionar insights valiosos y actualizados sobre las oportunidades de empleo para profesionales y estudiantes de carreras como Ingeniería de Sistemas, Desarrollo de Software, Ciencia de la Computación, Informática, Análisis de Datos y otras disciplinas afines en el país.

En un mercado tecnológico en constante evolución, entender las tendencias de la demanda, las habilidades más solicitadas y las expectativas salariales es crucial para la toma de decisiones estratégicas. Esta plataforma busca empoderar a los individuos para orientar su carrera, planificar su formación continua, y ayudar a las instituciones educativas a adaptar sus currículas a las necesidades reales del dinámico sector TI.

Este proyecto utiliza un pipeline de datos que comienza con la **carga y limpieza de ofertas laborales a través de un módulo en Streamlit**, procesa y almacena estos datos en **Amazon S3**, los cataloga con **AWS Glue**, y permite análisis complejos y la creación de un modelo dimensional mediante **Amazon Athena**. Finalmente, los insights se visualizan en un **dashboard interactivo construido con Power BI**, conectado a Athena a través de ODBC.

## 🎯 Objetivos del Proyecto

El objetivo general de este proyecto es:

Desarrollar e implementar una plataforma interactiva y basada en datos que **monitoree, analice y presente de manera clara y accesible las tendencias, requisitos y oportunidades del mercado laboral para profesionales y estudiantes del amplio espectro de carreras tecnológicas y de computación en Perú**, con el fin de facilitar la toma de decisiones estratégicas para esta diversa audiencia, así como para instituciones educativas y empresas del sector.

Para lograr esto, el **dashboard de Power BI** se enfoca en los siguientes objetivos clave:

### Objetivo Principal del Dashboard:

1.  **Visualizar Oportunidades Laborales Detalladas para el Sector TI:**
    *   Mostrar ofertas laborales actualizadas, permitiendo a los usuarios filtrar y explorar por criterios como ubicación geográfica (región), tipo de contrato, modalidad de trabajo, nivel de experiencia requerido, lenguajes de programación, frameworks, bases de datos y herramientas específicas demandadas. El objetivo es que los usuarios de diversas carreras TI puedan identificar rápidamente las oportunidades que mejor se ajustan a su perfil y aspiraciones profesionales.

### Objetivos Secundarios del Dashboard:

2.  **Identificar Roles y Tecnologías Más Demandadas en el Ámbito Tecnológico:**
    *   Permitir a los usuarios visualizar de forma clara cuáles son los roles (ej. Desarrollador Backend, Ingeniero de Datos, Especialista en Ciberseguridad, etc.) y categorías de puestos con mayor demanda en el mercado TI peruano.
    *   Analizar y destacar las habilidades y tecnologías (lenguajes, frameworks, bases de datos, metodologías) más requeridas por las empresas en las diferentes ofertas, ayudando a los profesionales y estudiantes a enfocar su aprendizaje y desarrollo.

3.  **Análisis Geográfico de la Oferta Laboral TI:**
    *   Facilitar la visualización de la distribución de las ofertas laborales del sector tecnológico a lo largo de las diferentes regiones del Perú. Esto ayudará a los usuarios a evaluar las oportunidades por ubicación, entender dónde se concentra la demanda para ciertos perfiles y tomar decisiones informadas sobre posibles reubicaciones o enfoque geográfico en su búsqueda de empleo.

4.  **Evaluar Tendencias Salariales por Especialización y Experiencia en TI:**
    *   Proveer gráficos y visualizaciones interactivas que muestren rangos y promedios salariales (cuando la información esté disponible) para diferentes especializaciones, roles y niveles de experiencia dentro del campo tecnológico. Este análisis ayudará a los usuarios a comprender mejor las expectativas salariales en su área y región, y a negociar de manera más informada.

5.  **Visualizar la Demanda por Niveles Educativos en el Sector Tecnológico:**
    *   Proporcionar gráficos y análisis que muestren la relación entre el nivel educativo requerido (Técnico, Universitario, Magíster, certificaciones, etc.) y las ofertas laborales disponibles en el sector TI. Esto permitirá a los usuarios evaluar cómo los requisitos educativos varían entre diferentes roles y si se alinean con sus estudios actuales o planificados.

## 🛠️ Tecnologías Utilizadas

*   **Procesamiento y Limpieza de Datos:** Python (Pandas) a través de una aplicación en Streamlit.
*   **Almacenamiento de Datos (Data Lake):** Amazon S3.
*   **Catálogo de Datos y ETL (potencial):** AWS Glue.
*   **Motor de Consultas y Modelo Dimensional (Vistas):** Amazon Athena.
*   **Conectividad:** Driver ODBC para Athena.
*   **Visualización y Business Intelligence:** Microsoft Power BI.

---
<!-- Opcional: Añade aquí otras secciones como "Autores", "Estructura del Proyecto", etc. -->
