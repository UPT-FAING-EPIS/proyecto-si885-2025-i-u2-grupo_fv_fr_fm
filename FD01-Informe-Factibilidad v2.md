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

## Informe de Factibilidad

**Versión 2.0**

**Control de Versiones**  
| Versión | Hecha por | Revisada por | Aprobada por | Fecha      | Motivo         |
|---------|-----------|--------------|--------------|------------|----------------|
| 2.0     | AFM       | AFM          | MFR          | 09/06/2025 | Versión Original |

---

## Índice General

1. [Descripción del Proyecto](#descripción-del-proyecto)
2. [Riesgos](#riesgos)
3. [Análisis de la Situación Actual](#análisis-de-la-situación-actual)
4. [Estudio de Factibilidad](#estudio-de-factibilidad)
   - 4.1 [Factibilidad Técnica](#factibilidad-técnica)
   - 4.2 [Factibilidad Económica](#factibilidad-económica)
   - 4.3 [Factibilidad Operativa](#factibilidad-operativa)
   - 4.4 [Factibilidad Legal](#factibilidad-legal)
   - 4.5 [Factibilidad Social](#factibilidad-social)
   - 4.6 [Factibilidad Ambiental](#factibilidad-ambiental)
5. [Análisis Financiero](#análisis-financiero)
6. [Conclusiones](#conclusiones)

---

## Descripción del Proyecto

### Nombre del Proyecto
**Plataforma de Análisis del Mercado Laboral Tecnológico**

### Duración del Proyecto
3 meses (desde la fase de análisis hasta la implementación y prueba del sistema)

### Descripción
Este proyecto tiene como objetivo crear un dashboard que permita analizar el mercado laboral tecnológico. La plataforma ayudará a estudiantes, egresados y profesionales a conocer qué empleos están disponibles, qué tecnologías están siendo más utilizadas y qué habilidades buscan las empresas actualmente. Además, permitirá a las universidades adaptar sus cursos a las necesidades reales del mercado laboral. Las empresas podrán entender mejor el mercado y mejorar cómo contratan nuevos talentos.

### Objetivos

#### Objetivo General
Desarrollar un dashboard moderno e intuitivo que permita a estudiantes, egresados y profesionales en tecnología visualizar y analizar de manera clara y accesible la demanda laboral actual, ayudándoles a identificar oportunidades de empleo y prepararse mejor para el mercado.

#### Objetivos Específicos
1. Recopilar información actualizada sobre las ofertas laborales disponibles para profesionales.
2. Analizar y mostrar los datos de manera interactiva, utilizando estadísticas y comparaciones que faciliten la comprensión de las tendencias laborales, las habilidades más solicitadas y los cambios en la demanda del mercado.
3. Mantener la aplicación siempre actualizada, integrando de forma constante nuevas tendencias, tecnologías emergentes y las necesidades cambiantes del mercado laboral, asegurando que la información sea útil y actual.

---

## Riesgos

1. **Dependencia de fuentes de datos externas**: La calidad de la información depende de portales de empleo y su disponibilidad.
2. **Precisión de datos**: Posibles inconsistencias si las fuentes no son actualizadas.
3. **Sobrecarga del servidor**: Riesgo de baja capacidad ante muchos usuarios concurrentes.
4. **Cumplimiento legal**: Necesidad de respetar la Ley de Protección de Datos Personales.

---

## Análisis de la Situación Actual

### Planteamiento del Problema
Existe una brecha entre la formación académica de los estudiantes y las demandas reales del mercado laboral. Muchos profesionales carecen de información sobre las habilidades requeridas, salarios, ubicaciones con alta demanda, lo que genera desempleo o subempleo. Actualmente no hay una herramienta específica que analice el mercado de forma integral para este campo.

### Consideraciones de Hardware y Software

#### Hardware
Para el desarrollo y prueba de la plataforma web de monitoreo y análisis del mercado laboral, se utilizarán 3 computadoras con las siguientes características:

- **Procesador**: Intel Core i5 de octava generación o superior, adecuado para tareas de programación, análisis de datos y pruebas del sistema, asegurando fluidez y rapidez en el desarrollo.
- **Sistema Operativo**: Windows 10 o versiones más recientes. Para el alojamiento en servidores, se recomienda utilizar Linux (si el proveedor de hosting lo permite), ya que ofrece mayor estabilidad, seguridad y un menor costo operativo.
- **Memoria RAM**: 16 GB DDR4, lo que permite ejecutar sin problemas herramientas de desarrollo, servidores locales, entornos de prueba y múltiples aplicaciones al mismo tiempo.
- **Accesorios**: Monitor, teclado y mouse estándar serán suficientes para llevar a cabo las tareas de desarrollo, diseño y pruebas funcionales de la plataforma.

#### Software

- **Lenguaje de programación**: Se empleará Python como lenguaje principal para desarrollar el backend de la aplicación. Para la parte visual, se utilizarán Power BI, lo que permitirá crear una interfaz moderna e interactiva.
- **Base de datos**: La información sobre ofertas de empleo, habilidades demandadas y usuarios se almacenará en una base de datos PostgreSQL, estructurada para garantizar eficiencia en la consulta y manejo de los datos.
- **Entorno de desarrollo**: Se trabajará con Visual Studio Code, un entorno ligero y flexible que ofrece todas las herramientas necesarias para programar en Python, gestionar la base de datos y realizar pruebas de manera eficiente.

---

## Estudio de Factibilidad

### Factibilidad Técnica

1. **Hardware**: Se utilizarán computadoras de gama media con procesadores Intel Core i5 o superior y al menos 8 GB de RAM, suficientes para programar, hacer pruebas y administrar la plataforma de manera fluida.
2. **Servidor en la nube**: Se necesitará un servidor con almacenamiento en la nube para guardar y acceder de forma segura a los datos recolectados, permitiendo acceso remoto para los desarrolladores y usuarios autorizados.
3. **Software**: El sistema será desarrollado en Python, utilizando este lenguaje para la lógica del backend y el procesamiento de datos. Para la visualización y análisis de la información, se empleará Power BI, lo que permitirá crear una interfaz interactiva, intuitiva y de fácil acceso para los usuarios.
4. **Visualización y exportación de datos**: Se usarán herramientas compatibles con PDF, Excel y JSON para que los usuarios puedan ver y descargar reportes de manera sencilla.
5. **Base de datos**: No se utilizará un sistema gestor de base de datos tradicional. En su lugar, la información sobre ofertas laborales, habilidades demandadas, estadísticas y otros datos relevantes se almacenará en un archivo CSV. Este enfoque permite manejar los datos de forma sencilla y flexible para su posterior análisis en Python y visualización en Power BI.

### Factibilidad Económica

#### Costos Generales

| Concepto                      | Cantidad | Costo Unitario (S/) | Subtotal (S/) |
|--------------------------------|----------|---------------------|---------------|
| Computadoras para desarrollo   | 2        | 1,000               | 2,000         |
| Material de oficina            | -        | 200                 | 200           |
| **Total**                      | -        | -                   | **2,200**     |

#### Costos Operativos Durante el Desarrollo

| Concepto                     | Cantidad | Costo Mensual (S/) | Total (S/) (6 meses) |
|-------------------------------|----------|--------------------|----------------------|
| Servicios básicos (agua, luz)  | 1        | 200                | 1,200                |
| Servidor en la nube            | 1        | 150                | 900                  |
| **Total**                      | -        | -                  | **2,100**            |

#### Costos del Ambiente

| Concepto                   | Costos (S/) |
|-----------------------------|-------------|
| Hosting                     | 150         |
| Dominio web (.com o .org)   | 50          |
| Infraestructura de red      | 200         |
| **Total**                   | **400**     |

#### Costos de Personal

| Rol                        | Cantidad | Salario Mensual (S/) | Duración (Mensual) | Subtotal (S/) |
|----------------------------|----------|----------------------|------------------|---------------|
| Desarrollador Backend       | 1        | 900                  | 3                | 2,700         |
| Desarrollador Frontend      | 1        | 1,000                | 3                | 2,100         |
| Analista de Requerimientos | 1        | 900                  | 3                | 400           |
| **Total**                   | -        | -                    | -                | **8,400**     |

#### Costos Totales

| Categoría                  | Costos Total (S/) |
|----------------------------|-------------------|
| Costos Generales            | 2,200             |
| Costos Operativos           | 2,100             |
| Costos del Ambiente         | 400               |
| Costos de Personal          | 8,400             |
| **Total**                   | **13,100**        |

---

### Factibilidad Operativa

El sistema está pensado para ser fácil de usar, con una interfaz intuitiva y amigable. Cualquier persona podrá entrar desde su navegador y acceder a la información sin necesidad de descargar nada. Además, tendrá filtros, comparaciones y gráficos para facilitar la experiencia. Se actualizará frecuentemente para mantener todo al día, lo que garantiza que pueda operar bien por mucho tiempo.

---

### Factibilidad Legal

El proyecto será desarrollado respetando las leyes vigentes, en especial la Ley de Protección de Datos Personales (Ley N° 29733 - Perú). Solo se usará información que sea pública o que los usuarios entreguen de forma voluntaria. Además, la plataforma contará con políticas de privacidad claras para proteger los datos personales y garantizar un uso legal de toda la información.

---

### Factibilidad Social

El impacto social es muy positivo. Ayudará a que más estudiantes y egresados puedan encontrar trabajo en su área, conociendo mejor qué habilidades deben aprender y en qué lugares hay más oportunidades. También ayudará a que las universidades mejoren sus planes de estudio y que las empresas contraten personal más capacitado. En general, busca mejorar la empleabilidad y apoyar el crecimiento profesional.

---

### Factibilidad Ambiental

1. **Uso eficiente de energía**: La plataforma digitaliza procesos de análisis y consulta de información laboral, lo que evita actividades presenciales y reduce el uso excesivo de recursos físicos, optimizando así el consumo energético.
2. **Optimización del almacenamiento digital**: La información se gestionará en la nube de forma organizada y sin duplicados, permitiendo un mejor uso del espacio en servidores y evitando el consumo innecesario de recursos tecnológicos.
3. **Fomento de la conciencia ambiental**: Al utilizar esta plataforma digital, los usuarios fortalecen su conciencia ecológica, promoviendo el uso responsable de herramientas tecnológicas y la reducción del impacto ambiental en sus actividades educativas y profesionales.

---

## Análisis Financiero

### Justificación de la Inversión

#### Beneficios del Proyecto

**Beneficios Tangibles:**

1. Acceso rápido a información laboral actualizada.
2. Ahorro de tiempo en la búsqueda de empleo.
3. Mejora en la planificación académica.
4. Análisis de tendencias y habilidades demandadas.

**Beneficios Intangibles:**

1. Mayor orientación profesional.
2. Confianza en los datos.
3. Impulso a la mejora continua.

#### Criterios de Inversión

##### Relación Beneficio/Costo (B/C)

| Inversión | S/. 13,100 |
|-----------|------------|
| **B/C**   | S/. 1.75   |
  
##### Valor Actual Neto (VAN)

| VAN        | S/. 7,789.92 |
|------------|--------------|

##### Tasa Interna de Retorno (TIR)

| TIR        | 48%          |
|------------|--------------|

---

## Conclusiones

Este proyecto busca desarrollar una plataforma que ayude a entender mejor el mercado laboral en el campo de tecnología. Gracias a esta herramienta, se podrá conocer qué puestos son más buscados, qué habilidades se necesitan y cómo se mueve el mercado en tiempo real. Esto será útil tanto para los estudiantes que quieren prepararse mejor, como para las universidades que desean adaptar su enseñanza a lo que realmente se necesita afuera. Desde el punto de vista económico, el proyecto es rentable. Los cálculos muestran que se recupera la inversión, se obtiene una buena ganancia y tiene un buen potencial de crecimiento. También trae beneficios sociales al mejorar la empleabilidad.
