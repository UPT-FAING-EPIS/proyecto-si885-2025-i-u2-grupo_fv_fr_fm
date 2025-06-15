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

---
</center>
<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

# Plataforma de Análisis del Mercado Laboral Tecnológico

## Informe Proyecto Final

**Versión 2.0**

## CONTROL DE VERSIONES

| Versión | Hecha por | Revisada por | Aprobada por | Fecha      | Motivo         |
|---------|-----------|--------------|--------------|------------|----------------|
| 2.0     | AFM       | AFM          | AFM          | 09/06/2025 | Versión Original |

---

## ÍNDICE GENERAL

1. [Antecedentes](#antecedentes)  
2. [Planteamiento del Problema](#planteamiento-del-problema)  
   - 2.1 [Problema](#problema)  
   - 2.2 [Justificación](#justificación)  
   - 2.3 [Alcance](#alcance)  
3. [Objetivos](#objetivos)  
   - 3.1 [Objetivo General](#objetivo-general)  
   - 3.2 [Objetivos Específicos](#objetivos-específicos)  
4. [Marco Teórico](#marco-teórico)  
5. [Desarrollo de la Solución](#desarrollo-de-la-solución)  
   - 5.1 [Análisis de Factibilidad](#análisis-de-factibilidad)  
   - 5.2 [Tecnología de Desarrollo](#tecnología-de-desarrollo)  
   - 5.3 [Metodología de Implementación](#metodología-de-implementación)  
6. [Cronograma](#cronograma)  
7. [Presupuesto](#presupuesto)  
8. [Conclusiones](#conclusiones)  
9. [Recomendaciones](#recomendaciones)  
10. [Anexos](#anexos)  
   - Anexo 01 [Informe de Factibilidad](#informe-de-factibilidad)  
   - Anexo 02 [Documento de Visión](#documento-de-visión)  
   - Anexo 03 [Documento SRS](#documento-srs)  
   - Anexo 04 [Documento SAD](#documento-sad)  
   - Anexo 05 [Manuales y otros documentos](#manuales-y-otros-documentos)

---

## 1. Antecedentes
En los últimos años, el sector tecnológico ha experimentado un crecimiento acelerado, generando una alta demanda de profesionales con habilidades específicas. Sin embargo, muchas personas no cuentan con una herramienta que les permita conocer las tendencias del mercado laboral en tiempo real, lo que dificulta su inserción profesional o actualización continua. Este proyecto nace como respuesta a esa necesidad, buscando cerrar la brecha entre formación académica y demanda laboral.

---

## 2. Planteamiento del Problema

A pesar del crecimiento del sector tecnológico en Perú, existe una desconexión entre las habilidades que los profesionales adquieren durante su formación académica y las competencias que las empresas requieren en el mercado laboral. Esta brecha se ve reflejada en la dificultad de los egresados para encontrar empleo en su área de especialización y en la escasez de talento calificado que enfrentan las organizaciones para cubrir posiciones clave en sus equipos de TI.

### 2.2 Justificación
La creación de un dashboard en Power BI que analice el mercado laboral tecnológico permitirá visualizar de manera clara y dinámica las tendencias de demanda de habilidades, niveles salariales, ubicaciones geográficas con mayor oferta de empleo y otros indicadores clave. Esta herramienta proporcionará a los usuarios información estratégica para la toma de decisiones, como la elección de especializaciones académicas, la identificación de áreas con mayor potencial de crecimiento y la optimización de procesos de contratación y retención de talento.

### 2.3 Alcance
El proyecto abarcará el desarrollo de un dashboard interactivo en Power BI que integrará datos provenientes de diversas fuentes, como portales de empleo, encuestas a empresas y estudios de mercado. Se incluirán visualizaciones que permitan analizar la evolución de la demanda de habilidades tecnológicas, comparar salarios por región y sector, identificar perfiles profesionales más solicitados y evaluar la efectividad de las políticas educativas en la formación de talento alineado con las necesidades del mercado.

---

## 3. Objetivos

### 3.1 Objetivo General
Desarrollar un dashboard interactivo en Power BI que proporcione un análisis integral y actualizado del mercado laboral tecnológico en Perú, facilitando la toma de decisiones informadas para estudiantes, profesionales, instituciones educativas y empresas.

### 3.2 Objetivos Específicos
1. Integrar datos de diversas fuentes confiables sobre el mercado laboral tecnológico en Perú.
2. Desarrollar visualizaciones interactivas que permitan analizar tendencias de demanda de habilidades, niveles salariales y ubicaciones geográficas con mayor oferta de empleo.
3. Implementar filtros y segmentaciones que permitan personalizar el análisis según el perfil del usuario.
4. Garantizar la actualización periódica de los datos para mantener la relevancia del dashboard.
5. Proporcionar recomendaciones basadas en los análisis realizados para apoyar la toma de decisiones estratégicas.

---

## 4. Marco Teórico

El **Business Intelligence (BI)** es un conjunto de tecnologías, aplicaciones y prácticas que permiten la recopilación, integración, análisis y presentación de información empresarial para apoyar la toma de decisiones. **Power BI** es una herramienta de BI desarrollada por Microsoft que permite crear informes y dashboards interactivos a partir de diversas fuentes de datos. En el contexto del análisis del mercado laboral, el BI permite transformar grandes volúmenes de datos en información visual y comprensible, facilitando la identificación de tendencias y patrones.

En Perú, el mercado laboral tecnológico ha mostrado un crecimiento sostenido en los últimos años. Según datos del Ministerio de Trabajo y Promoción del Empleo, en 2021 las áreas de tecnología y sistemas ocuparon el tercer lugar en generación de empleo formal en el país. Se estima que para el 2025 habrá una demanda de 80,000 profesionales de tecnología en el país. Sin embargo, las empresas enfrentan el desafío de encontrar a los profesionales adecuados para cubrir sus necesidades, ya que la tecnología se está desarrollando más rápido de lo que se puede formar a la gente para utilizarla.

---

## 5. Desarrollo de la Solución

### 5.1 Análisis de Factibilidad

- **Técnica**: Power BI es una herramienta robusta y ampliamente utilizada que permite la integración de múltiples fuentes de datos y la creación de visualizaciones interactivas.
- **Económica**: La inversión en licencias de Power BI es accesible, y existen versiones gratuitas que pueden ser suficientes para el desarrollo inicial del proyecto.
- **Operativa**: Se requiere personal con conocimientos en BI y análisis de datos para el desarrollo y mantenimiento del dashboard.
- **Social**: El proyecto contribuirá a mejorar la empleabilidad de los profesionales del sector tecnológico al proporcionarles información actualizada y relevante.
- **Legal**: Es necesario cumplir con las normativas de protección de datos personales y derechos de autor al utilizar fuentes de información.
- **Ambiental**: El uso de herramientas digitales reduce la necesidad de recursos físicos, contribuyendo a la sostenibilidad.

### 5.2 Tecnología de Desarrollo

- **Herramienta Principal**: Power BI Desktop y Power BI Service.
- **Fuentes de Datos**: APIs de portales de empleo, bases de datos públicas y privadas sobre el mercado laboral.
- **Lenguajes y Herramientas Complementarias**: DAX para cálculos, Power Query para transformación de datos, y Azure para almacenamiento en la nube.

### 5.3 Metodología de Implementación

Se adoptará una metodología ágil, permitiendo iteraciones rápidas y adaptaciones según los comentarios de los usuarios finales. Las fases principales serán:
1. Recopilación de requisitos y definición del alcance.
2. Diseño del modelo de datos y desarrollo de visualizaciones.
3. Integración de datos y pruebas de funcionalidad.
4. Despliegue y capacitación de usuarios.
5. Mantenimiento y actualizaciones periódicas.

---

## 6. Cronograma

| Fase                         | Duración Estimada |
|------------------------------|-------------------|
| **Recopilación de requisitos** | 2 semanas         |
| **Diseño y desarrollo**       | 4 semanas         |
| **Integración y pruebas**     | 2 semanas         |
| **Despliegue y capacitación** | 1 semana          |
| **Mantenimiento inicial**     | 2 semanas         |

---

## 7. Presupuesto

| Categoría              | Costos Total (S/) |
|------------------------|-------------------|
| **Costos Generales**    | 2,200             |
| **Costos Operativos**   | 2,100             |
| **Costos del Ambiente** | 400               |
| **Costos de Personal**  | 8,400             |
| **Total**               | 13,100            |

---

## 8. Conclusiones

El desarrollo de un dashboard en Power BI para analizar el mercado laboral tecnológico proporcionará a estudiantes y profesionales una herramienta poderosa para tomar decisiones informadas sobre su desarrollo profesional. La implementación de este proyecto contribuirá a mejorar la alineación entre la formación académica y las demandas del mercado, fortaleciendo así el sector tecnológico en Perú.

---

## 9. Recomendaciones

1. Mantener la actualización periódica de los datos para asegurar la relevancia del dashboard.
2. Expandir la cobertura a otras áreas tecnológicas según la demanda del mercado.
3. Integrar el dashboard con plataformas educativas para personalizar la información según el perfil académico del usuario.
4. Fomentar la colaboración con empresas del sector para enriquecer los datos y mejorar la precisión del análisis.

---

## 10. Anexos

### Anexo 01 Informe de Factibilidad
[Informe de Factibilidad](https://docs.google.com/document/d/1ybW1vLJAFhtLjfRVdl5kROqXont1yyq1QX_QPJNKETo/edit?usp=sharing)

### Anexo 02 Documento de Visión
[Documento de Visión](https://docs.google.com/document/d/18J_vN2vINOlYl2htSBwjASvgn2oxOZ1RjnhwXAkKCUo/edit?usp=sharing)

### Anexo 03 Documento SRS
[Documento SRS](https://docs.google.com/document/d/19n6WhanP7eJMTWCgEC-fsJYtsbwc4z6d/edit?usp=sharing&ouid=107416293927707292395&rtpof=true&sd=true)

### Anexo 04 Documento SAD
[Documento SAD](https://docs.google.com/document/d/1vSFDd7CMTY1jReSy2MQCDzy80d926kPV/edit?usp=sharing&ouid=107416293927707292395&rtpof=true&sd=true)

### Anexo 05 Manuales y otros documentos
[Manuales y otros documentos](https://docs.google.com/document/d/1pFoZeQUc9I7nVsCPM6uH_cH3DaFqaksH/edit?usp=sharing&ouid=107416293927707292395&rtpof=true&sd=true)

