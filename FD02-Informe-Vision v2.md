<center>

[comment]: <img src="./media/media/image1.png" style="width:1.088in;height:1.46256in" alt="escudo.png" />

![./media/media/image1.png](./media/logo-upt.png)

**UNIVERSIDAD PRIVADA DE TACNA**

**FACULTAD DE INGENIERIA**

**Escuela Profesional de Ingeniería de Sistemas**

**Proyecto *Plataforma de Análisis del Mercado Laboral Tecnológico***

Curso: *Inteligencia de Negocios*

Docente: *Mag. Patrick Cuadros Quiroga*


Integrantes:

***Daleska Nicolle Fernandez Villanueva (2021070308)***

***Andree Sebastian Flores Melendez  (2017057494)***

***Mario Antonio Flores Ramos  (2018000597)***


**Tacna – Perú**

***2025***


</center>
<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

---

## CONTROL DE VERSIONES

| Versión | Hecha por | Revisada por | Aprobada por | Fecha      | Motivo         |
|---------|-----------|--------------|--------------|------------|----------------|
| 2.0     | AFM       |              |              | 09/06/2025 | Versión Original |

---

# Plataforma de Análisis del Mercado Laboral Tecnológico

## Documento de Visión

**Versión 2.0**

## ÍNDICE GENERAL

1. [Introducción](#introducción)
   - 1.1 [Propósito](#propósito)
   - 1.2 [Alcance](#alcance)
   - 1.3 [Definiciones, Siglas y Abreviaturas](#definiciones-siglas-y-abreviaturas)
   - 1.4 [Referencias](#referencias)
   - 1.5 [Visión General](#visión-general)
2. [Posicionamiento](#posicionamiento)
   - 2.1 [Oportunidad de negocio](#oportunidad-de-negocio)
   - 2.2 [Definición del problema](#definición-del-problema)
3. [Descripción de los interesados y usuarios](#descripción-de-los-interesados-y-usuarios)
   - 3.1 [Resumen de los interesados](#resumen-de-los-interesados)
   - 3.2 [Resumen de los usuarios](#resumen-de-los-usuarios)
   - 3.3 [Entorno de usuario](#entorno-de-usuario)
   - 3.4 [Perfiles de los interesados](#perfiles-de-los-interesados)
   - 3.5 [Perfiles de los Usuarios](#perfiles-de-los-usuarios)
   - 3.6 [Necesidades de los interesados y usuarios](#necesidades-de-los-interesados-y-usuarios)
4. [Vista General del Producto](#vista-general-del-producto)
   - 4.1 [Perspectiva del producto](#perspectiva-del-producto)
   - 4.2 [Resumen de capacidades](#resumen-de-capacidades)
   - 4.3 [Suposiciones y dependencias](#suposiciones-y-dependencias)
   - 4.4 [Costos y precios](#costos-y-precios)
   - 4.5 [Licenciamiento e instalación](#licenciamiento-e-instalación)
5. [Características del producto](#características-del-producto)
6. [Restricciones](#restricciones)
7. [Rangos de calidad](#rangos-de-calidad)
8. [Precedencia y Prioridad](#precedencia-y-prioridad)
9. [Otros requerimientos del producto](#otros-requerimientos-del-producto)
   - a) [Estándares legales](#estándares-legales)
   - b) [Estándares de comunicación](#estándares-de-comunicación)
   - c) [Estándares de cumplimiento de la plataforma](#estándares-de-cumplimiento-de-la-plataforma)
   - d) [Estándares de calidad y seguridad](#estándares-de-calidad-y-seguridad)
10. [CONCLUSIONES](#conclusiones)
11. [RECOMENDACIONES](#recomendaciones)
12. [WEBGRAFÍA](#webgrafía)

---

## 1. Introducción

### 1.1 Propósito
Este proyecto tiene como propósito desarrollar un dashboard que analice las tendencias del mercado laboral en tecnología, permitiendo a estudiantes y profesionales identificar oportunidades de empleo y mejorar su preparación según las demandas actuales. Proporcionará información relevante sobre ofertas de empleo, habilidades requeridas y tendencias del sector, facilitando la toma de decisiones para la inserción y desarrollo profesional.

### 1.2 Alcance
El sistema proporcionará un análisis detallado del mercado laboral tecnológico a través de una aplicación web. Entre sus principales funcionalidades se incluyen:
- Recopilación y análisis de datos de ofertas de empleo.
- Visualización de tendencias de empleo en gráficos y estadísticas.
- Filtros avanzados para búsquedas personalizadas por tecnologías, experiencia y ubicación.
- Comparador de habilidades del usuario con las demandas del mercado.

### 1.3 Definiciones, Siglas y Abreviaturas

- **SQL (Structured Query Language)**: Lenguaje utilizado para gestionar bases de datos relacionales.
- **TI (Tecnologías de la Información)**: Conjunto de tecnologías utilizadas para gestionar información y comunicación digital.
- **S3**: Amazon S3 es un servicio de almacenamiento en la nube ofrecido por Amazon Web Services (AWS). Está diseñado para almacenar y recuperar cualquier cantidad de datos desde cualquier lugar en la web.

### 1.5 Visión General
Este documento describe los objetivos, alcance y funcionalidades del sistema propuesto. Se detallan los aspectos técnicos, la arquitectura, las tecnologías utilizadas y el impacto esperado en la comunidad. La aplicación busca facilitar el acceso a información relevante para mejorar la empleabilidad y la toma de decisiones profesionales en este campo.

---

## 2. Posicionamiento

### 2.1 Oportunidad de negocio
En la actualidad, el mercado laboral en el área tecnológica está en constante evolución debido a los avances tecnológicos y la creciente demanda de profesionales con habilidades específicas. Sin embargo, muchos estudiantes y egresados enfrentan dificultades para identificar oportunidades laborales acordes a su perfil y nivel de experiencia.

Esta aplicación representa una oportunidad de negocio al ofrecer una plataforma que analiza tendencias del mercado laboral en las áreas de tecnología, proporcionando información clave sobre empleabilidad, tecnologías en demanda y requisitos más solicitados por las empresas. Al facilitar este acceso a datos estructurados, la aplicación permitirá a los usuarios mejorar su preparación y aumentar sus oportunidades de inserción en el mercado laboral.

Además, la aplicación puede ser utilizada por universidades e instituciones educativas para adaptar sus planes de estudio a las necesidades del sector, asegurando que sus egresados tengan mejores oportunidades en el campo profesional.

### 2.2 Definición del problema
Existe una brecha entre la formación de los estudiantes de las carreras de tecnología y afines. Muchos profesionales no cuentan con información suficiente sobre las habilidades más valoradas, los salarios promedio, las ciudades con mayor demanda laboral o las tendencias tecnológicas emergentes.

Esta problemática genera que muchos egresados enfrenten desempleo o subempleo al no contar con información estratégica para mejorar su competitividad profesional.

---

## 3. Descripción de los interesados y usuarios

### 3.1 Resumen de los interesados
Los interesados en este proyecto son todas aquellas personas o entidades que se verán beneficiadas directa o indirectamente por el sistema. Entre ellos se encuentran estudiantes, egresados, profesionales de las carreras de tecnologías, universidades, empresas del sector tecnológico y entidades gubernamentales relacionadas con el empleo y la educación.

### 3.2 Resumen de los usuarios
Los usuarios principales del sistema serán estudiantes y profesionales que deseen conocer el estado del mercado laboral, las tendencias en tecnologías y las habilidades más demandadas. También podrán utilizarlo docentes, universidades y empresas interesadas en ajustar sus planes de estudio o procesos de contratación.

### 3.3 Entorno de usuario
El sistema estará disponible como una aplicación web, accesible desde distintos dispositivos como computadoras, tablets y smartphones. Se priorizará una interfaz intuitiva y fácil de usar, con gráficos interactivos y filtro avanzado.

### 3.4 Perfiles de los interesados
- **Estudiantes de carreras tecnológicas**: Buscan información sobre tendencias laborales para orientar su formación académica y mejorar sus posibilidades de empleo.
- **Egresados y Profesionales**: Necesitan conocer oportunidades laborales, tecnologías en demanda y salarios promedio para optimizar su desarrollo profesional.
- **Universidades y Docentes**: Pueden usar los datos para actualizar sus planes de estudio y adaptarlos a las necesidades del mercado.
- **Empresas de Tecnología**: Buscan conocer la oferta de profesionales en rubros tecnológicos para mejorar sus procesos de reclutamiento.
- **Instituciones de Empleo y Gobierno**: Interesadas en datos estadísticos sobre empleabilidad para diseñar políticas de educación y trabajo.

### 3.5 Perfiles de los Usuarios
- **Usuario Estudiante**: Persona que cursa carreras del área de tecnología y busca orientación sobre tecnologías y habilidades en demanda.
- **Usuario Profesional**: Ingenieros de Sistemas que desean mejorar su perfil laboral y explorar nuevas oportunidades de empleo.
- **Usuario Docente/Académico**: Profesores e investigadores que analizan tendencias laborales para actualizar la enseñanza.

### 3.6 Necesidades de los interesados y usuarios

| Interesado/Usuario          | Necesidades Principales                                           |
|-----------------------------|-------------------------------------------------------------------|
| **Estudiantes**              | Conocer habilidades y tecnologías más demandadas, acceso a oportunidades de empleo. |
| **Egresados/Profesionales**  | Comparar su perfil con el mercado laboral, identificar áreas de mejora. |
| **Universidades/Docentes**   | Obtener datos para actualizar los programas académicos según la demanda laboral. |
| **Empresas**                 | Analizar tendencias para mejorar procesos de reclutamiento y contratación. |
| **Gobierno/Instituciones**   | Acceder a información sobre empleabilidad para diseñar políticas educativas y laborales. |

---

## 4. Vista General del Producto

### 4.1 Perspectiva del producto
La aplicación propuesta es una plataforma digital diseñada para recopilar, analizar y presentar información sobre el mercado laboral tecnológico. Su propósito es ayudar a estudiantes, egresados y profesionales a tomar decisiones informadas sobre su desarrollo profesional al proporcionar datos actualizados sobre tendencias de empleo, tecnologías en demanda y requisitos laborales.

El sistema se integra con fuentes de datos de ofertas de empleo en línea y otras fuentes relevantes para generar reportes y estadísticas en tiempo real. También incluirá herramientas de filtrado, comparaciones de habilidades y visualización de tendencias.

### 4.2 Resumen de capacidades
- **Análisis del Mercado Laboral**: Presentación de estadísticas sobre las tecnologías y habilidades más solicitadas.
- **Filtrado Avanzado**: Permite a los usuarios buscar oportunidades laborales según su nivel de experiencia, ubicación y tecnologías.
- **Predicciones Laborales**: Uso de tendencias históricas para predecir cambios en la demanda de tecnologías y habilidades.
- **Visualización Interactiva**: Gráficos y reportes en tiempo real para facilitar el análisis de datos.

### 4.3 Suposiciones y dependencias
Para el correcto funcionamiento del sistema, se establecen las siguientes suposiciones y dependencias:
- **Acceso a Datos Externos**: Se requiere la disponibilidad de fuentes de datos confiables sobre ofertas de empleo.
- **Conectividad a Internet**: La aplicación estará basada en la nube, por lo que necesita acceso a internet para su uso.
- **Actualización Periódica**: La información debe ser constantemente actualizada para mantener su relevancia.

### 4.4 Costos y precios

| Categoría                  | Costos Total (S/) |
|----------------------------|-------------------|
| **Costos Generales**        | 2,200             |
| **Costos Operativos**       | 2,100             |
| **Costos del Ambiente**     | 400               |
| **Costos de Personal**      | 8,400             |
| **Total**                   | 13,150            |

### 4.5 Licenciamiento e instalación
La aplicación se distribuirá bajo un modelo de **Software como Servicio (SaaS)**, permitiendo el acceso desde cualquier navegador web o aplicación móvil sin necesidad de instalación local.

**Opciones de licenciamiento**:
- **Licencia Comercial**: Acceso a funcionalidades avanzadas mediante suscripción.
- **Licencia Educativa**: Descuentos o acceso gratuito para universidades y estudiantes.

---

## 5. Características del producto
El producto es una aplicación que permite a los usuarios obtener información sobre el mercado laboral tecnológico. Sus características principales incluyen:
- Búsqueda y análisis de empleos por habilidades, experiencia y ubicación.
- Visualización de tendencias sobre tecnologías y herramientas más demandadas.
- Reportes personalizables con gráficos y análisis en tiempo real.

---

## 6. Restricciones
- La calidad y precisión de los datos dependerá de la disponibilidad y exactitud de las fuentes públicas.
- Requiere conexión a internet para acceder a todas las funcionalidades.
- Limitaciones de capacidad del servidor según la cantidad de usuarios concurrentes.
- Compatibilidad garantizada solo para los navegadores más actuales (Chrome, Firefox, Edge).

---

## 7. Rangos de calidad
- **Disponibilidad**: 99% de tiempo en línea.
- **Tiempo de respuesta de la aplicación**: menor a 3 segundos por consulta.
- **Actualización de datos**: semanal o mensual, dependiendo de la fuente.
- **Interfaz limpia**: sin errores de navegación ni de carga.
- **Seguridad de datos personales**: garantizada mediante cifrado y buenas prácticas.

---

## 8. Precedencia y Prioridad
- **Prioridad Alta**: Recolección y visualización de datos esenciales (tecnologías, empleos, empresas).
- **Prioridad Media**: Funciones de personalización y comparación de perfil.
- **Prioridad Baja**: Exportación avanzada de reportes y recomendaciones automáticas.

**Desarrollo inicial** enfocado en estudiantes y profesionales, luego ampliado a instituciones.

---

## 9. Otros requerimientos del producto

### a) Estándares legales
- Cumplimiento con la Ley de Protección de Datos Personales vigente en Perú (Ley N° 29733).
- Uso responsable y legal de la información recolectada desde portales públicos.
- Políticas claras de privacidad y términos de uso accesibles al usuario final.

### b) Estándares de comunicación
- Comunicación segura mediante el protocolo HTTPS.
- Lenguaje sencillo, inclusivo y adaptado al público objetivo (estudiantes y profesionales de las áreas de tecnología).

### c) Estándares de cumplimiento de la plataforma
- Compatibilidad con navegadores modernos (Chrome, Firefox, Edge, Safari).
- Diseño responsivo que se adapte correctamente a móviles, tabletas y computadoras.

### d) Estándares de calidad y seguridad
- Pruebas de funcionalidad, rendimiento y usabilidad realizadas antes de la publicación.
- Protección contra ataques comunes como inyecciones SQL.
- Almacenamiento seguro de cualquier dato sensible.
- Actualizaciones periódicas para garantizar estabilidad y seguridad.

---

## CONCLUSIONES
El desarrollo de una aplicación para analizar la demanda laboral permite a los estudiantes y profesionales conocer las tendencias del mercado, facilitando la toma de decisiones sobre su formación y empleabilidad.

A través del análisis de datos actualizados, se identifican las tecnologías, habilidades y regiones con mayor demanda, lo que aporta valor tanto a los usuarios como a instituciones educativas.

La herramienta propuesta no solo fortalece la orientación profesional, sino que también puede convertirse en un apoyo estratégico para la planificación académica y laboral.

---

## RECOMENDACIONES
- Mantener la aplicación con actualizaciones constantes de datos para asegurar su vigencia y utilidad.
- Expandir la cobertura a otras áreas de tecnología para beneficiar a más estudiantes y egresados.
- Evaluar la integración con plataformas educativas para brindar información personalizada según los cursos o especializaciones del usuario.
- Promover el uso de la herramienta dentro de la universidad para apoyar la inserción laboral de sus estudiantes.

---

## WEBGRAFÍA

- [Ministerio de Trabajo y Promoción del Empleo](https://www.trabajo.gob.pe)
- [Computrabajo Perú](https://pe.computrabajo.com)
