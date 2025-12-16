# Lección 4: Compartir Datos Abiertos

## Contenidos

- [Cuándo compartir los datos y consideraciones sobre si se debe hacerlo](#cu%C3%A1ndo-compartir-los-datos-y-consideraciones-sobre-si-se-debe-hacerlo)
- [Dónde compartir datos](#d%C3%B3nde-compartir-datos)
- [Cómo habilitar el reúso de datos](#c%C3%B3mo-habilitar-el-re%C3%BAso-de-datos)
- [Quién es responsable de compartir datos](#qui%C3%A9n-es-responsable-de-compartir-datos)
- [Lección 4: Resumen](#lecci%C3%B3n-4-resumen)
- [Lección 4: Evaluación](#lecci%C3%B3n-4-evaluaci%C3%B3n)


## Descripción general

En esta lección aprenderás las buenas prácticas para compartir tus datos con una audiencia más amplia. ¿Cuándo deberías compartir datos y deberías hacerlo? Retomarás el proceso de compartición y cómo evaluar si tus datos son compartibles. Luego aprenderás cómo asegurar que tus datos estén disponibles públicamente mediante una lección sobre repositorios y el ciclo de vida de la accesibilidad de los datos. Desde la selección de un repositorio hasta el archivado de tus datos, estas prácticas aseguran que tus datos puedan mantenerse y ser buscables. Finalmente, recorrerás los pasos para hacer que tus datos sean lo más reutilizables posible, concluyendo con una sección sobre a quién considerar para ayudar en el proceso de compartición de datos.

## Objetivos de aprendizaje

Luego de completar esta lección, deberías poder:

- Reconocer que variables institucionales, cuestiones de seguridad y el momento oportuno pueden afectar la decisión de compartir datos.
- Recordar las características, responsabilidades inherentes, consideraciones de financiamiento y requisitos de patrocinadores que deben considerarse al seleccionar un repositorio para compartir datos.
- Describir las herramientas y algunas buenas prácticas que optimizan la posibilidad de compartir datos.

## Descripción general del proceso de compartición de datos

Compartir datos es una parte crítica para aumentar la reproducibilidad de los resultados. Ya sea que se trate de nuevos datos recolectados directamente o de datos que se procesan para realizar análisis, siempre se termina compartiendo algún tipo de datos. Es necesario reflexionar sobre qué datos se compartirán y cómo asegurar que sean abiertos y utilizables por otras personas.

La compartición de datos debería realizarse, por lo general, a través de un centro de datos o repositorio de largo plazo que sea responsable de ingerir, curar y distribuir(publicar) los datos abiertos. La responsabilidad de proporcionar información(metadatos) para que los datos sean fácilmente descubribles, accesibles y citables recae en quien produce los datos. También deben considerarse los costos de archivado y publicación de los datos.

### Entonces, quieres compartir tus datos

Una vez que se decide compartir los datos, existen varias preguntas que deben responderse para planificar este proceso y que deberían incluirse en el plan de gestión de datos (DMP), tratado también en la Lección 3:

|  |  |
|---|---|
| ¿Qué? | Formatos de datos y (cuando corresponda) estándares |
| ¿Cuándo? | Cuándo y si compartir datos |
| ¿Dónde? | Repositorios previstos para datos archivados |
| ¿Cómo? | Cómo el plan habilita la reutilización de los datos |
| ¿Quién? | Roles y responsabilidades de los miembros del equipo para implementar el DMP |

En esta lección se cubren algunos pasos vinculados a la producción de datos. En particular, se pone el foco en las secciones del DMP relacionadas con el "cuándo", el "dónde", el "cómo" y el "quién".

### Proceso de compartición de datos abiertos

En general, compartir datos abiertos requiere los siguientes pasos:

1. Asegurarse de que los datos puedan compartirse.
2. Seleccionar o identificar un repositorio que aloje los datos.
3. Trabajar con el repositorio para seguir su proceso y cumplir con sus requisitos.
4. Asegurarse de que los datos sean encontrables y accesibles a través del repositorio, y que puedan mantenerse y archivarse.
5. Solicitar un DOI para el conjunto de datos para que sea fácilmente citable.
6. Elegir una licencia de datos.

En algunos casos, es posible trabajar con un repositorio bien dotado de personal que se encargue de muchos de estos pasos (por ejemplo, al trabajar con datos de misiones de la NASA). En otros casos, la responsabilidad de seguir los pasos anteriores para compartir los datos de forma abierta recae en quien produce los datos.

## Cuándo y si compartir datos

### ¿Cuándo compartir datos?

La decisión sobre cuándo compartir datos debería discutirse con todas las personas del equipo y documentarse en el plan de gestión de datos. Las agencias financiadoras y organizaciones pueden tener requisitos específicos sobre cuándo deben compartirse los datos, pero aquí se propone reflexionar incluso antes de lo exigido por el financiador acerca de si es factible o posible compartir los datos. Existen distintos momentos en los que los datos pueden compartirse:

- **Compartición anticipada:** Compartir en el momento de la recolección o poco después. Algunas agencias financiadoras lo requieren o permiten un breve periodo de embargo, aunque suele ser necesario justificarlo (controles de calidad, calibraciones, etc.). Esto maximiza la reutilización y el impacto de los datos, lo que puede derivar en mayores colaboraciones.
- **Compartición intermedia:** En el momento de la publicación. Muchas publicaciones (y algunas agencias financiadoras) requieren que los datos necesarios para reproducir los resultados se compartan al momento de publicar.
- **Compartición mínima:** Al finalizar el financiamiento. Todos los datos científicamente útiles deberían compartirse al finalizar la subvención.
- **No compartir:** Existen múltiples razones por las cuales los datos deben restringirse o no compartirse en absoluto.

Como se discutió previamente en este currículo, existen muchos beneficios en compartir los datos lo antes posible. La compartición temprana puede conducir a descubrimientos nuevos e inesperados y ampliar las redes de colaboración. Recuerda que, incluso cuando compartes datos, sigues siendo quien más conoce esos datos. En muchos casos, cuando otras personas desean trabajar con los datos, se pondrán en contacto para colaborar.

### ¿Deberían compartirse los datos?

Antes de compartir conjuntos de datos, es importante considerar cualquier restricción a la capacidad de compartirlos y asegurar que quienes contribuyeron, incluidas personas donantes de muestras y datos, aprueben su liberación.

Los datos deberían ser tan abiertos como sea posible y tan cerrados como sea necesario. Abrir los datos es una forma poderosa de habilitar el descubrimiento, la transparencia y el progreso científico. Sin embargo, es importante considerar algunos puntos antes de compartirlos:

- Algunos datos están sujetos a leyes y regulaciones que limitan su liberación.
- La agencia financiadora o la institución pueden tener políticas y recursos adicionales. Es importante investigarlos de forma temprana y periódica.

Consideraciones específicas que pueden impedir la compartición de datos incluyen:

- Secretos militares de un país o violaciones de intereses nacionales.
- Información médica privada o datos personales de individuos.
- Consideraciones culturales o de conservación.
- Propiedad intelectual y patentes.
- Otras consideraciones: reflexiona críticamente sobre qué se comparte y las implicancias de hacerlo (por ejemplo, si se cuenta con el permiso de todas las personas involucradas).

En el primer módulo de este currículo se enumeraron varias razones por las cuales ciertos productos de investigación no deberían compartirse. Aquí se revisan algunas de esas razones, con mayor detalle en aquellas particularmente relevantes para los datos.

### Consideraciones de exportación y seguridad

Las leyes y regulaciones relevantes que pueden impedir la liberación de datos incluyen, entre otras:

- [International Traffic in Arms Regulation](https://www.pmddtc.state.gov/?id=ddtc_public_portal_itar_landing) (ITAR) (enlace externo), que regula la fabricación, venta, distribución y exportación de artículos y servicios relacionados con defensa.
- [Export Administration Regulations](https://www.bis.gov/regulations) (EAR) (enlace externo), que regula la fabricación, venta, distribución y exportación de artículos comerciales y de uso dual, tecnología e información no cubiertos por ITAR.

**Ejemplo: Estándar de Protección de Sistemas Espaciales de la NASA**

NASA STD 1006.1 [Space System Protection Standard](https://standards.nasa.gov/standard/NASA/NASA-STD-1006) establece requisitos de protección para asegurar que las misiones de la NASA sean resilientes frente a amenazas intencionales.

### Consideraciones sobre información controlada

Algunas regulaciones que pueden impedir la compartición de datos incluyen, entre otras:

- [Health Insurance Portability and Accountability Act](https://www.hhs.gov/hipaa/for-professionals/index.html) (HIPAA) (enlace externo), que establece estándares para proteger información sensible de salud de pacientes.
- [Controlled Unclassified Information](https://www.archives.gov/cui) (enlace externo), que define estándares para el manejo de información no clasificada que requiere salvaguardas o controles de difusión.
- Leyes y regulaciones federales que gobiernan información clasificada o requisitos de seguridad.

### Consideraciones de propiedad intelectual

Los datos pueden estar sujetos a consideraciones de propiedad intelectual, derechos de autor y licenciamiento. Entre las regulaciones relevantes se encuentran leyes de patentes o propiedad intelectual, como la [Bayh-Dole Act](https://www.govinfo.gov/content/pkg/USCODE-2011-title35/html/USCODE-2011-title35-partII-chap18.htm) (enlace externo), que permite a universidades, instituciones de investigación sin fines de lucro y pequeñas empresas poseer, patentar y comercializar invenciones desarrolladas con financiamiento federal.

**Ejemplo: Suplemento FAR de la NASA 1852.227**

El [NASA FAR Supplement 1852.227](https://prod.nais.nasa.gov/far/far0595-nfs012617/5227.htm) describe derechos de patentes y datos para contratos gubernamentales.

---

Muchas instituciones de investigación cuentan con personas expertas en propiedad intelectual, derechos de autor y patentes. Son un recurso valioso ante dudas o inquietudes.

## Dónde compartir datos

Los datos pueden compartirse en una variedad de lugares. Aunque compartir datos por correo electrónico o sitios web es común, no se recomienda porque no cumple con los requisitos de encontrabilidad ni con el soporte de archivado a largo plazo. Compartir datos como material suplementario de una publicación revisada por pares, especialmente para conjuntos de datos pequeños, es aceptable en algunos campos. Un repositorio de largo plazo que provea un identificador permanente es la mejor opción para compartir datos.

### Seleccionar un repositorio de datos

Si aún no tienes un repositorio en mente, considera lo siguiente para reducir opciones:

- ¿El patrocinador del financiamiento exige un repositorio específico?
- ¿La organización(institución) recomienda un repositorio determinado?
- ¿Existe un repositorio específico por dominio ampliamente usado en tu campo?
- ¿El repositorio ofrece acceso abierto a los datos?
- ¿Las herramientas del repositorio para descubrimiento y distribución son FAIR y adecuadas para tus datos?
- ¿El repositorio requiere financiamiento del proyecto? ¿Se ajusta al presupuesto o requiere soporte más allá del ciclo de vida del proyecto?

Compara servicios, beneficios y limitaciones de los repositorios considerados. Cada repositorio tiene procesos y requisitos propios según su financiamiento, propósito y base de usuarios.

Los datos con preocupaciones de privacidad pueden requerir procesos adicionales de anonimización, aprobación o restricciones de acceso.

Un buen resumen de características deseables presentado por la Casa Blanca puede encontrarse [aquí](https://doi.org/10.5479/10088/113528) (enlace externo).

### Asegurar la accesibilidad

Los repositorios adecuados comparten(o ofrecen) datos abiertos mediante protocolos estándar como HTTPS o SFTP. Las formas comunes incluyen:

- Permitir que las personas vean una lista de archivos y los descarguen mediante una interfaz intuitiva.
- Crear una API documentada para generar listas de archivos según criterios de búsqueda y descargarlos de forma automatizada (acceso máquina a máquina).

Los repositorios también pueden requerir autorización y autenticación (por ejemplo, inicio de sesión con usuario y contraseña). Esto está permitido bajo los Principios FAIR, pero puede entrar en conflicto con principios de ciencia abierta si no todas las personas pueden obtener acceso.

### Trabajar con un repositorio

<table>
  <thead>
    <tr>
        <th>INICIAR EL TRABAJO CON UN REPOSITORIO &#9745;</th>
        <th>MANTENER DATOS EN UN REPOSITORIO</th>
        <th>ARCHIVAR DATOS EN UN REPOSITORIO</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="3">
            <p>Los requisitos de los repositorios varían ampliamente. Revisa siempre los requisitos para saber qué acciones tomar al comenzar a trabajar con ellos. Algunos repositorios cuentan con personal que puede ayudar en el proceso de compartición de datos, mientras que otros dependen de que la persona usuaria sepa cómo compartir sus datos.</p>
            <p>Si el repositorio ofrece acompañamiento, puede solicitar revisar y comentar el plan de gestión de datos.</p>
            <p>El repositorio puede pedir datos de muestra para evaluar:</p>
            <ul>
                <li>Que el formato de datos esté soportado.</li>
                <li>Que las variables estén nombradas como se espera.</li>
                <li>Que el vocabulario de metadatos sea correcto.</li>
                <li>Que se cumplan los requisitos específicos del repositorio.</li>
            </ul>
            <p>Este control de conformidad puede identificar malentendidos de forma temprana y facilitar una entrega final fluida.</p>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>INICIAR EL TRABAJO CON UN REPOSITORIO</th>
        <th>MANTENER DATOS EN UN REPOSITORIO &#9745;</th>
        <th>ARCHIVAR DATOS EN UN REPOSITORIO</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="3">
            <p>A medida que el proyecto avanza, utiliza los procesos de actualización, revisión y reenvío del repositorio para mantener los datos archivados actualizados. Cada nueva versión debe atravesar una evaluación similar a la inicial.</p>
            <p>Esto implica que cada versión pase por revisión del DMP, control de cumplimiento y procedimiento de carga.</p>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>INICIAR EL TRABAJO CON UN REPOSITORIO</th>
        <th>MANTENER DATOS EN UN REPOSITORIO</th>
        <th>ARCHIVAR DATOS EN UN REPOSITORIO &#9745;</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="3">
            <p>Al finalizar el proyecto, asegúrate de haber actualizado y cargado toda la documentación complementaria con la versión final de los datos.</p>
            <p>Asegura que el repositorio mantenga los datos(o al menos los metadatos) disponibles por un período razonable.</p>
            <p>Verifica que el repositorio acepte revisiones posteriores si se detectan problemas luego del cierre del proyecto.</p>
        </td>
    </tr>
  </tbody>
</table>

## Cómo habilitar la reutilización de los datos

### Obtener un DOI

Las personas no suelen solicitar un DOI directamente, sino a través de una organización autorizada, como:

- El repositorio de datos
- La organización de pertenencia
- La editorial (si los datos forman parte de una publicación)

Quienes producen datos deben proporcionar información de resumen para las páginas de aterrizaje del DOI si es requerido. Es recomendable reservar un DOI antes de crear los datos, cuando sea posible.

### Asegurar la encontrabilidad

Los repositorios gestionan la compartición, distribución y curaduría de los datos. Servicios adicionales incluyen:

- Asignación de identificadores persistentes (como DOI).
- Indexación y(o) registro de datos y metadatos en servicios de búsqueda.
- Retroalimentación para optimizar metadatos.
- Coordinación para asegurar que los metadatos refieran al DOI.
- Asociación del DOI con una página de aterrizaje descriptiva.

### Facilitar la citación de los datos

El objetivo es facilitar la citación. Buenas prácticas incluyen:

- Incluir una declaración de citación con el DOI.
- Incorporar un archivo .CFF si el repositorio lo recomienda.
- Identificar claramente a quienes crean los datos y(o) su institución.
  - Incluir ORCiD cuando sea posible.

Una vez que los datos están en un repositorio y cuentan con DOI y declaración de citación, difúndelos y recuerda a quienes los usen que los citen.

## Quién es responsable de compartir los datos

Compartir datos abiertos es un esfuerzo colectivo. Planificar y acordar roles y responsabilidades es una parte clave del proceso.

### ¿Quién moverá los datos al repositorio?

Determina quién se encargará de:

- Proporcionar información sobre volumen, cantidad de archivos y naturaleza.
- Verificar nombres de archivos.
- Definir el método de transferencia.
- Verificar la integridad de datos, metadatos y documentación.

### ¿Quién desarrollará la documentación y los metadatos?

Determina quién:

- Organizará el contenido.
- Desarrollará metadatos.
- Elaborará documentación (por ejemplo, README).
- Extraerá metadatos de archivos y documentación.

### ¿Quién ayudará con la reutilización de los datos?

Identifica quién:

- Verificará accesibilidad y encontrabilidad.
- Colaborará con el repositorio para optimizar herramientas.
- Evaluará implicancias de los protocolos de acceso.

### ¿Quién desarrollará pautas sobre privacidad y sensibilidad cultural?

Decide quién:

- Identificará preocupaciones de privacidad.
- Definirá procesos de aprobación.
- Desarrollará pautas de interpretación.
- Evaluará restricciones necesarias para una compartición respetuosa.

## Lección 4: Resumen

Los principales aprendizajes de esta lección son:

- Cuándo y si compartir datos: definir el momento adecuado y reconocer que no todos los datos pueden compartirse.
- Dónde compartir datos: se recomienda el uso de repositorios públicos de datos.
- Cómo habilitar la reutilización: usar metadatos adecuados, asignar un DOI y facilitar la citación.
- Quién ayuda a compartir datos: definir roles claros para cada etapa del proceso.

## Lección 4: Autoevaluación

*Pregunta*

**01/04**

Los datos no pueden compartirse si están:

- Controlados por ITAR
- Clasificados como información no clasificada controlada
- Sujetos a propiedad intelectual, derechos de autor o licenciamiento
- Todas las anteriores

*Pregunta*

**02/04**

Es una buena práctica comenzar a trabajar con un repositorio:

- Lo antes posible
- Cuando se cuenta con datos de prueba
- Después de obtener un DOI
- Cuando se está listo para liberar los datos

*Pregunta*

**03/04**

¿Quién puede ayudar a obtener un DOI para los datos?

- El repositorio
- La organización de pertenencia
- Una revista científica
- Todas las anteriores

*Pregunta*

**04/04**

¿Qué roles deben considerarse al compartir datos? Selecciona todos los que correspondan.

- Desarrollar pautas sobre privacidad y sensibilidad cultural
- Desarrollar documentación y metadatos
- Asignar un DOI a los datos
- Verificar la integridad de la transferencia de datos, metadatos y documentación
