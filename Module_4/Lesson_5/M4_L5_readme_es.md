# Lección 5: De la teoría a la práctica

## Contenidos

- [Planes de Ciencia Abierta y Gestión de Datos](#planes-de-ciencia-abierta-y-gesti%C3%B3n-de-datos)
- [¿Cómo planificar abrir nuestro código?](#c%C3%B3mo-planificar-abrir-nuestro-c%C3%B3digo)
- [Generar interés y construir comunidades](#generar-inter%C3%A9s-y-construir-comunidades)
- [Contribuir a proyectos de software de Código Abierto](#contribuir-a-proyectos-de-software-de-c%C3%B3digo-abierto)
- [Recursos adicionales](#recursos-adicionales)
- [Lección 5: Resumen](#lecci%C3%B3n-5-resumen)
- [Lección 5: Evaluación](#lecci%C3%B3n-5-evaluaci%C3%B3n)
- [Resumen del Módulo 4: Código Abierto](#resumen-del-m%C3%B3dulo-4-c%C3%B3digo-abierto)

## Descripción general

Esta lección final articula el desarrollo de software de acceso abierto con la puesta en práctica de un plan de gestión de software (SMP). Se introduce la dimensión comunitaria del software abierto, comenzando con una discusión sobre la redacción de planes de gestión de software y continuando con cómo vincularse con comunidades de software abierto. Este recorrido se contextualiza a partir de los beneficios de las comunidades de software y de los distintos roles que se desempeñan en ellas. Luego de presentar una lista de comunidades, se propone explorar e interactuar con algunas de ellas. Finalmente, la lección cierra con recursos adicionales y sugerencias útiles para contribuir al software abierto.

## Objetivos de aprendizaje

Luego de completar esta lección, deberías poder:

- Recordar la definición de un plan de gestión de software, potencialmente como parte de un Plan de Ciencia Abierta y Gestión de Datos (OSDMP), y dónde encontrar recursos útiles.
- Enumerar formas de involucrarse y contribuir a comunidades de software abierto.

## Planes de Ciencia Abierta y Gestión de Datos

Muchas convocatorias de NASA requieren la presentación de un Plan de Ciencia Abierta y Gestión de Datos como parte del paquete de propuesta. La Guía de Ciencia Abierta y Código Abierto de la Dirección de Misiones Científicas de NASA (SMD) establece:

<img style="width: 100%; height: auto;" src="../images/media/codebg_es.jpg">

> “Un Plan de Ciencia Abierta y Gestión de Datos de NASA (OSDMP) describe cómo se gestionará y se pondrá a disposición de forma abierta la información científica producida a partir de actividades científicas financiadas por NASA. El OSDMP debe incluir secciones sobre gestión de datos, gestión de software y compartición de publicaciones.”
> — NASA Science Mission Directorate, 2025

Crédito de la imagen: “Codes on Tilt Shift Lens” de Markus Spiske vía [Pexels](https://www.pexels.com/photo/codes-on-tilt-shift-lens-2004161/) (enlace externo)

---

Ejemplos de secciones a incluir en un OSDMP:

- Plan de Gestión de Datos (DMP)
- Plan de Gestión de Software (SMP)
- Compartición de publicaciones
- Otras actividades de ciencia abierta
- Roles y responsabilidades

### Repaso de los pasos de un SMP vistos en lecciones anteriores

- **Qué:** descripción de la gestión, preservación y liberación del código.
- **Cuándo:** cronograma para el archivado y la compartición del software o código.
- **Dónde:** lugar donde el software o código será compartido y archivado a largo plazo.
- **Cómo:** habilitar la reutilización del software o código mediante la asignación de un DOI, una licencia, lineamientos de contribución, etc.
- **Quién:** roles y responsabilidades de las personas integrantes del equipo.

<img style="width: 350px; height: auto;" src="../images/media/recallsteps_es.jpg">

## ¿Cómo planificamos hacer abierto nuestro código?

### ¿Es necesario escribir un plan de gestión de software o de datos?

Si estás planificando un proyecto que puede requerir un plan de gestión de software o de datos, redactar ese plan es un excelente primer paso antes de comenzar el proyecto. En este contexto, “software” refiere a programas informáticos científicamente o técnicamente relevantes, tanto en forma de código fuente como de software ejecutable. A continuación se presenta una lista de razones por las cuales deberías, o no, redactar un SMP:

|  |  |
|---|---|
| **El SMP es requerido** | Necesitas un SMP para: <ul><li>Presentarte a convocatorias de financiamiento (por ejemplo, NASA, NSF y, probablemente, cada vez más agencias)</li><li>Colaborar en un equipo que planea liberar software o código al público</li><li>Gestionar con éxito misiones o proyectos de gran escala</li></ul> |
| **El SMP no es requerido** | Probablemente no necesites un SMP si estás trabajando en: <ul><li>Un artículo en solitario (o con un grupo muy pequeño)</li><li>Exploraciones iniciales de ideas o experimentación con código de análisis</li><li>Actividades con fines educativos</li></ul> |

Es posible que tu proyecto no encaje exactamente en estas categorías. Por ejemplo, si tu objetivo es que otras personas puedan reproducir tus resultados, la decisión de redactar un SMP quedará a tu criterio.

El material que sigue asume que ya alcanzaste ese umbral y que estás redactando un plan de gestión de datos o de software.

### Manos a la obra: comenzar a escribir un plan

Si estás solicitando financiamiento, es muy probable que la convocatoria incluya requisitos específicos de gestión de datos. Por ejemplo, la entidad financiadora puede exigir el uso de una licencia determinada o de un repositorio específico. Asegúrate de contrastar tu plan con esos requisitos.

**Ejemplos de planes de gestión de software**

- <https://www.software.ac.uk/resources/guides/software-management-plans> (enlace externo)
- <https://www.esciencecenter.nl/national-guidelines-for-software-management-plans/> (enlace externo)
- <https://zenodo.org/record/7589725> (enlace externo)

**Requisitos**

¿Cuáles son los requisitos para un SMP (qué indican la agencia financiadora o la institución)?

- ¿Qué formatos de datos deben utilizarse?
- ¿Cuáles son los requisitos de archivado y preservación del software o código?
- ¿Qué roles y responsabilidades son necesarios para cumplir todos los requisitos?

### Agencias financiadoras

Las agencias de financiamiento científico suelen recurrir a evaluaciones por pares para respaldar decisiones de financiamiento. Estas evaluaciones, de manera explícita o implícita, consideran el software o código abierto asociado. La participación comunitaria es necesaria para alcanzar consensos sobre estándares comunitarios de financiamiento.

Por ejemplo, la política SPD-41a de la Dirección de Misiones Científicas de NASA se aplica a todas las actividades científicas financiadas por SMD y establece explícitamente que “el software financiado debe seguir las buenas prácticas de las comunidades relevantes de código abierto e investigación” (NASA Science Mission Directorate, 2022).

### Políticas establecidas de código abierto en sociedades profesionales

Sociedades profesionales como AAAS, AGU, AAS y otras influyen en las políticas de las agencias financiadoras y afectan directamente las políticas sobre software y código utilizados para generar publicaciones. Involucrarse con la comunidad a través de documentos de consenso y sociedades profesionales es clave para orientar decisiones de política sobre software de código abierto en ciencia.

Science (AAAS) establece explícitamente: “En general, todo el código informático central para los hallazgos que se reportan debería estar disponible para las personas lectoras a fin de garantizar la reproducibilidad”.

### Instituciones

Las instituciones con las que trabajamos imponen restricciones muy variables al software de código abierto debido a consideraciones de seguridad, privacidad, propiedad intelectual, aspectos comerciales u otros factores que no siempre se alinean con el espíritu de la ciencia abierta. Es importante interactuar con la comunidad institucional para facilitar el avance hacia políticas que promuevan el software de código abierto como base de la ciencia abierta.

### Actividad 5.1: redacción de un SMP

En esta actividad, revisa el SMP que se presenta a continuación y reflexiona sobre las siguientes preguntas:

- ¿Qué tipos de software o código describe el SMP?
- ¿Cuándo se compartirá el trabajo?
- ¿Dónde se compartirá el trabajo?
- ¿Cómo se compartirá el trabajo para que sea un objeto citable?
- ¿Quién será responsable de los distintos aspectos del software o código?
- ¿Cuáles son algunas de las limitaciones del software o código?
- ¿Cómo impactaría la falta de un plan en el desarrollo del código a largo plazo?
- ¿Los resultados son reproducibles sin el código original en Interactive Data Language (IDL)?
- ¿Hay elementos en el plan de ejemplo que agregarías o especificarías con mayor detalle?

#### Ejemplo de Plan de Gestión de Software

**1. Tipos de software esperados**

Se utilizarán modelos de simulación establecidos para realizar simulaciones iniciales. Estos modelos están escritos en Fortran y fueron desarrollados a lo largo de la última década. Aunque no están disponibles públicamente, sí están disponibles para su uso en el proyecto (por ejemplo, mediante comunicación privada). Los modelos de simulación generarán archivos de salida según lo descrito en el Plan de Gestión de Datos (DMP). Se desarrollará software de análisis en Python para analizar los archivos de salida de los modelos, lo que permitirá generar productos de datos derivados, mapas y figuras. El desarrollo del software de análisis en Python se compartirá en un repositorio de GitHub.

**2. Desarrollo del software de análisis**

Todo el desarrollo nuevo de código en Python se realizará de manera abierta en GitHub por integrantes de este proyecto. Se publicará y seguirá un Código de Conducta para el desarrollo de software del proyecto de investigación, que incluye lineamientos para contribuciones de otras personas de la comunidad científica.

**3. Repositorios y cronograma para compartir el software**

Este trabajo respaldará el desarrollo de dos artículos revisados por pares. Todo el código fuente desarrollado en Python para respaldar cada artículo será archivado en Zenodo a más tardar en la fecha de publicación del artículo. El software se pondrá a disposición bajo una licencia permisiva Apache License 2.0. Zenodo asignará un DOI al software archivado.

**4. Excepciones para compartir software**

Este trabajo no respalda el desarrollo adicional de los modelos de simulación existentes en Fortran, que se mantienen de forma independiente. No se cuenta con permiso para compartir públicamente el código fuente en Fortran de esos modelos.

**5. Roles y responsabilidades**

El modelado inicial de simulaciones y el desarrollo del software de análisis en Python serán realizados por estudiantes de doctorado y personas en instancias de posdoctorado. La persona Investigadora Principal (PI) del proyecto tiene la responsabilidad general de la ejecución de este plan.

## Involucrarse y construir comunidades

Las comunidades de software abierto son espacios sociales de aprendizaje donde las personas se reúnen para aprender nuevas habilidades, intercambiar conocimientos y experiencias, y luego aplicar lo aprendido en su trabajo cotidiano.

### Las comunidades ofrecen:

- Un punto de entrada accesible para aprender y mejorar el uso de software en investigación.
- Una oportunidad para compartir experiencias individuales, identificar obstáculos comunes y mejorar el conocimiento de forma iterativa.
- Una forma de construir colaboración en torno al software de código abierto en ciencia y mantenerse actualizado sobre herramientas y prácticas.
- Comunidades de práctica no jerárquicas, donde todas las personas contribuyen.

### Conectar con comunidades

Algunas comunidades que pueden ayudarte a comenzar son:

- PyData  
- SPEC  
- rOpenSci  
- pyOpenSci  
- PyHC  
- Research Software Engineering  
- NumFOCUS  
- R-Ladies  
- PyLadies  
- WoCCode  
- Pangeo  
- ObsPy  
- The Turing Way  

Suscribirse y participar en foros, talleres presenciales, conferencias y hackatones relacionadas con tu disciplina o el software al que contribuyes es una excelente forma de involucrarte. Conectar a través de redes sociales y conversar con colegas también puede abrir puertas a comunidades más amplias.

### Actividad 5.2: explorar comunidades de práctica

<img style="width:350px;height:auto;" src="../images/media/lightbulb_es.png">

- Explora los sitios web de al menos dos comunidades listadas en la sección anterior.
- Identifica al menos dos puntos de entrada para involucrarte, como eventos próximos, foros u otros espacios.

#### Ideas clave

- Existen muchas oportunidades para involucrarse en comunidades que trabajan en software abierto.
- La participación en estas comunidades puede enriquecer y mejorar tu software.

## Contribuir al software de código abierto

Contribuir al software abierto ofrece múltiples beneficios y abre oportunidades valiosas. Existen diversas formas de contribuir, y no todas implican escribir código:

|  |  |
|---|---|
| **Agregar nuevas funcionalidades** | Mejorar la usabilidad incorporando nuevas características. |
| **Corregir errores** | Resolver problemas reportados en el código. |
| **Reportar problemas y sugerir mejoras** | Informar errores o limitaciones también es una contribución valiosa. |
| **Mejorar la documentación** | Es una excelente forma de comenzar y facilita el uso por parte de otras personas. |
| **Crear tutoriales o casos de uso** | Compartir experiencias de uso del software. |
| **Refactorizar código** | Mejorar estructura, automatización y estabilidad del código existente. |
| **Organizar o participar en encuentros comunitarios** | Fortalecer la comunidad y el intercambio de conocimiento. |
| **Revisar código** | Evaluar contribuciones de otras personas, de forma similar a la revisión por pares. |

## Recursos adicionales

### Aviso

Algunos artículos mencionados pueden estar detrás de muros de pago. Si necesitas acceso, contacta a las personas autoras o busca versiones en repositorios de preprints como bioRxiv.

### Referencias y guías

- OpenSciency  
- NASA SMD Open Source Science Guidance  
- Practical Guide to Software Management  
- FAIR Principles for Research Software (FAIR4RS)  
- Open Source Software Policy Options for NASA Earth and Space Sciences  
- The Turing Way  
- Ten simple rules for documenting scientific software  
- Journal of Open Source Software  

### Formación adicional

- Software Carpentries  
- How to contribute to Open Source projects (guía para principiantes)

## Lección 5: Resumen

En esta lección aprendiste:

- Cuándo es necesario redactar un SMP y que las organizaciones financiadoras o instituciones pueden tener reglas específicas sobre el desarrollo y la compartición de código.
- Que integrarse a comunidades de software es una excelente forma de intercambiar conocimientos y aprender nuevas habilidades.
- Que existen múltiples formas de contribuir al código abierto, y no todas requieren escribir código.

## Lección 5: Autoevaluación

**01/02**  
La participación en comunidades de software abierto es no jerárquica; todas las personas integrantes deben contribuir.  
- Verdadero  
- Falso  

**02/02**  
Selecciona las formas beneficiosas de contribuir al software de código abierto:  
- Agregar nuevas funcionalidades  
- Corregir errores  
- Documentar el trabajo  
- Refactorizar  
- Todas las anteriores  

## Resumen de Código Abierto

¡Felicitaciones! Ahora deberías poder:

- Explicar qué significa el software de código abierto, su ciclo de desarrollo, beneficios y limitaciones.
- Descubrir software de código abierto, evaluarlo para su reutilización y citarlo cuando corresponda.
- Crear un plan de gestión de software de código abierto.
- Evaluar si tu software puede compartirse y cómo hacerlo para aumentar su visibilidad.
- Enumerar las responsabilidades asociadas a compartir software de código abierto.

### Referencias citadas

- NASA Science Mission Directorate. (2025). Open-Source Science Guidance.  
- NASA Science Mission Directorate. (2022). SMD Policy Document SPD-41a.
