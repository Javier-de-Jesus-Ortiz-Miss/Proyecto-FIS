# ¿Qué es la Ingeniería/Fase de Requerimientos?
Según Boehm, se refiere a "la disciplina para desarrollar una
especificación completa, consistente y no ambigua, la cual servirá como
base para acuerdos comunes entre todas las partes involucradas y en
dónde se describen las funciones que realizará el sistema."

# ¿Qué habilidades técnicas están asociadas a la fase de Requerimientos?
1. **Gestión de proyectos:**

* **Importancia:** según Ben Aston, "Una excelente gestión de proyectos significa mucho más que mantener controlado el triángulo de hierro de la gestión de proyectos, cumpliendo con los plazos, el presupuesto y el alcance; une a los clientes y los equipos, crea una visión para el éxito y pone a todos en la misma página de lo que se necesita para mantenerse camino al éxito. Cuando los proyectos se gestionan correctamente, hay un impacto positivo que va más allá de la entrega de “las cosas”."

* **Argumentos:** un equipo con una buena gestión del proyecto, tendrá claras ventajas sobre un proyecto que no lleve una buena gestión de su proyecto, entre los aspectos que podemos destacar están: 
    
    1. **Enfoque y Objetivos Claros:** los gestores de proyecto se encargan de dividir las tareas en partes más pequeñas, de esta manera permite al equipo mantenerse centrado en objetivos claros.

    2. **Planificación Realista del Proyecto:** una buena gestión de proyectos garantiza establecer expectativas y tareas realistas, por medio del análisis de diversas variables en un proyecto, lo que en muchas ocasiones define el éxito o el fracaso de un proyecto de Software.
</br></br>

2. **Seguridad de la información:**

* **Importancia:** la información es el recurso más valioso de una empresa, en éste se encuentran reflejadas un sinfín de horas de trabajo y de recursos destinados para la elaboración de los proyectos que ha llevado a cabo, sin embargo, en la actualidad, la seguridad se aborda en etapas demasiado avanzadas del proceso de desarrollo de Software, dando lugar a problemas de seguridad más complejos que, en caso de detectarse, podrían alargar el plazo de entrega del proyecto o llevar a vulnerabilidades y por ende, poner en peligro la información confidencial del sistema. Es por ello que el equipo de desarrollo debe contar con valiosas habilidades técnicas en seguridad de la información.

* **Argumentos:** Según Red Hat, podemos abordar argumentos tales como:

1. **Mejorar la seguridad y disminuir los riesgos** gracias a la eliminación de más puntos vulnerables desde el inicio del ciclo de vida de la infraestructura y el desarrollo de las aplicaciones, lo cual reduce los problemas potenciales en la etapa de producción.

2. **Disminuir los riesgos y aportar claridad** mediante la implementación de controles de seguridad desde el comienzo del ciclo de vida de la infraestructura y el desarrollo de las aplicaciones, lo cual reduce la probabilidad de que se cometan errores humanos y mejora la seguridad, el cumplimiento normativo y la capacidad para anticipar los inconvenientes y repetir los procesos que permitan solucionarlos, y disminuye los problemas de auditoría.

Adicionalmente, podemos mencionar aspectos como la confianza del cliente y el usuario final, la protección de la reputación de la empresa y el cumplimiento normativo.

</br>

3. **Control de calidad:**

* **Importancia:** la calidad en el software es un aspecto crucial en el desarrollo de todo software exitóso porque asegura la satisfacción del cliente y evita errores que se pueden detectar a tiempo. Un correcto control de calidad por parte de los integrantes del equipo de desarrollo, asegura buenos resultados y la satisfacción de todas las partes involucradas.

* **Argumentos:** el control de calidad asegura que el producto final cumpla con los requisitos y expectativas del cliente (que al final del día es la razón del proyecto), además, reduce los errores en etapas tempranas del desarrollo, lo que a su vez ahorra tiempo y dinero para el cliente y el equipo de desarrollo. Adicionalmente facilita el mantenimiento a largo plazo.

Actualmente, nuestro equipo de desarrollo está más organizado que en semanas anteriores, debido a que al inicio aún desconocíamos de muchas herramientas y conocimientos que actualmente tenemos y basados en la experiencia podemos mencionar la gestión del proyecto, que ahora está más dividida en tareas más pequeñas que antes, además de objetivos más claros con fechas definidas de entrega; esto lo hemos ido aprendiendo sobre la marcha y ahora podemos decir que hemos aprendido a gestionar mejor nuestro proyecto. 


# Casos de Uso vs Historias de Usuario

Según Felipe Gonzalez, "mientras que en las historias de usuarios estamos enfocados en encontrar la necesidad de la funcionalidad por parte del usuario (el para qué), en los casos de usos describimos detalladamente las interacciones de nuestro software con actores externos para satisfacer esa necesidad. Dado eso, adicionalmente se los utiliza como una herramienta para documentar requerimientos. 

Además, los casos de usos al ser más complejos son más difíciles de leer y pueden contener algún lenguaje técnico, mientras que en una historia de usuario son fáciles de leer y cualquier persona fuera del proyecto logra comprender sobre la misma."

Por tanto, podemos decir que los casos de uso, al tener un lenguaje más especializado, son más aptos para el equipo de desarrollo y colaboradores que están en constante comunicación con el equipo, mientras que las historias de usuario son más fáciles de leer para cualquier usuario que los casos de uso.

Por tanto podemos recomendar los casos de uso para: 
* Proyectos grandes y complejos donde se necesita una comprensión detallada de las interacciones entre actores y el sistema.

* Cuando se busca documentar un conjunto completo de requisitos funcionales y no funcionales de manera estructurada.

Recomendamos las historias de usuario para:

* Proyectos ágiles y desarrollo iterativo, donde se prioriza la entrega de valor de manera incremental.

* Cuando se busca una comunicación más sencilla y comprensible de los requisitos entre los desarrolladores y clientes.

* Para equipos que practican metodologías ágiles como Scrum, donde las Historias de Usuario son una unidad clave de trabajo.

Basado en la experiencia, podemos confirmar que las historias de usuario son más comprensibles al no tener tantos detalles y un entedimiento minucioso del funcionamiento del sistema, por lo que, para proyectos más grandes, los casos de uso serían adecuados debido a la complejidad del mismo.

# Métodos relacionados al diseño de la interfaz de usuario 

Las interfaces son una de las partes más importantes del software ya que tienen un gran peso en definir que tanto se usara el software, si una interfaz es confusa, lenta y antiestética lo mas probable es que el usuario deje de utilizar el software. Es por esto por lo que el diseño de interfaces, lejos de ser trivial es fundamental para un exitoso desarrollo de software.
En (Pressman,2002, p. 279) se menciona que, aunque se han desarrollado e impuesto varios modelos de para el diseño de las interfaces, suelen ser una combinación de las siguientes etapas: 
<ol>
  <li>Definir objetos y acciones de la interfaz (operaciones) con el uso de la información desarrollada en el análisis de la interfaz.</li>
  <li>Definir eventos (acciones del usuario) que harán que cambie el estado de la interfaz de usuario. Hay que modelar este comportamiento.</li>
  <li>Ilustrar cada estado de la interfaz como lo vería en la realidad el usuario final.</li>
  <li>Indicar cómo interpreta el usuario el estado del sistema a partir de la información provista a través de la interfaz.</li>
</ol>

Nos centraremos en la primera etapa, en nuestra opinión la más importante, ya que sirve como base para todo lo demás.  Se menciona que antes de diseñar hay que:

**Entender al usuario**, para esto existen métodos como realizarles entrevistas, realizar análisis de mercado, hacernos preguntas sobre las características de los usuarios (nivel educacional, edad, genero, idioma etc.) y estar en constante contacto con ellos. 

**Comprender las tareas**, a través de casos de uso, dividirlas en tareas y subtareas (jerarquizarlas) y la realización de diagramas.

**Analizar la información en pantalla**, buscando que sea estética y que el usuario pueda rápidamente identificar que representa cada cosa.

**Análisis del ambiente de trabajo**, todos los elementos que se tendrán en el entorno en el cual se utilizara el software se tienen que tomar en cuenta (iluminación, acceso al teclado, ruido, urgencia etc.)

En el caso de nuestro proyecto sin saberlo realizamos este método para diseño de interfaces, ya que desde el principio tuvimos en cuenta nuestro público objetivo y desarrollamos la app pensando en que estarían acostumbrados a usar ciertas redes sociales y apps. También realizamos el listado de tareas a través de los casos de uso y requerimientos, mismos que nos sirvieron para validar las interfaces.

De la misma forma tuvimos en cuenta que toda la información en pantalla fuera estética y sobre todo entendible para los usuarios objetivo, sin embargo, sabemos que esto no es suficiente por lo que en esta próxima entrega buscaremos realizar las mayores pruebas posibles para asegurar la usabilidad de nuestras interfaces.

# Pruebas en el desarrollo de software

Las pruebas son fundamentales en el desarrollo y existen distintos tipos dependiendo de que en etapa se estén realizando y cual sea su función, algunos ejemplos son: 

**Pruebas continuas:** estas pruebas se realizan después de cada compilación a medida que se acabe. se basa en automatizar pruebas; permitiendo así que el software se valide en entornos de prueba realistas en una etapa temprana del proceso, mejorando el diseño y reduciendo riesgos.

**Virtualización de servicios:** cuando los servicios no están completos este lo que hace es simular los servicios faltantes para reducir las dependencias y así realizar pruebas antes.

Es importante tener un buen seguimiento de defectos o errores ya que permite saber los defectos, medir su alcance e impacto y descubrir problemas relacionados.

A su vez las métricas e informes permiten a los miembros del equipo compartir el estado, los objetivos y los resultados de las pruebas y así supervisar las relaciones entre las pruebas, el desarrollo y otros elementos del proyecto
Los dos ejemplos de prueba dados nos hablan de realizar las pruebas lo antes posible, esto no es coincidencia ya que realizar cambios suele ser más costoso mientras as avanzado este el proceso.

De aquí surge parte del valor de los métodos agiles que buscan dividir el desarrollo en módulos, que una vez terminados pueden ser probados individualmente y así en base a los resultados realizar correcciones y tomar en cuenta los cambios para los siguientes módulos. Esto hace posible las pruebas continuas, permitiendo la iteración y modificaciones de forma iterativa y continua, pero mitigando la cantidad de trabajo que se tiene que rehacer o desechar igualmente.

En nuestro equipo a pesar de no haber realizado pruebas formales hemos estado cuestionando los requerimientos y enfoque de nuestro proyecto desde el principio, esto ha resultado en una reducción de los requerimientos y funciones. Reflexionando nos dimos cuenta de que de haber realizado pruebas con wireframes muy básicos nos hubiéramos dado cuenta que estábamos siendo muy ambiciosos desde el principio, ya que estamos seguros el usuario se hubiera perdido y abrumado con todas las funciones que queríamos incluir. Sin embargo, es una realidad que hubiera sido una inversión de tiempo bastante grande, por lo que llegamos a la conclusión de que si estuvo bien reservar las pruebas para esta etapa de refinamiento de interfaces en la cual estamos actualmente. 

# Habilidades de un Ingeniero de software en la creacion de un software seguro

**Por que es necesaria la seguridad en una aplicacion de software?** Una seguridad de aplicaciones deficiente puede implicar enormes consecuencias negativas para una organización. Los intrusos cibernéticos atacan a diversas organizaciones cada día para extraer dinero, información corporativa y propiedad intelectual con fines de enriquecimiento. Los atacantes utilizan los datos secuestrados para realizar compras no autorizadas y robar las identidades de los consumidores. 

* **Modelado de amenazas:** Pensar en cómo los atacantes pueden vulnerar un sistema y qué protecciones se necesitan contra esto

* **Ciclo de vida de desarrollo de software seguro (SSDLC):** Ayudar a los desarrolladores a escribir códigos seguros mediante la implementación de estándares de codificación seguros, técnicas y prácticas recomendadas con el fin de minimizar las vulnerabilidades

* **Revisiones de códigos de seguridad:** Identificar las vulnerabilidades de seguridad en el código fuente antes de que se implemente una aplicación en producción

* **Análisis y pruebas de vulnerabilidades:** Descubrir las debilidades una vez implementada la aplicación y asesorar a los equipos de desarrollo sobre una corrección

### References
(Habilidades Técnicas: ¿Qué Y Cuáles Son?, 2019) [https://habilidades.top/habilidades-tecnicas/#Ejemplos_de_habilidades_tecnicas](https://habilidades.top/habilidades-tecnicas/#Ejemplos_de_habilidades_tecnicas)


Galindo, S. (2023, March 15). Gestión de la calidad en el desarrollo de software: planificación, gestión y control. 3digits; 3digits. [https://www.3digits.es/blog/gestion-de-la-calidad-en-el-desarrollo-de-software.html#:~:text=La%20gesti%C3%B3n%20de%20la%20calidad%20del%20software%20permite%20identificar%20y,necesidad%20de%20duplicar%20el%20trabajo.](https://www.3digits.es/blog/gestion-de-la-calidad-en-el-desarrollo-de-software.html#:~:text=La%20gesti%C3%B3n%20de%20la%20calidad%20del%20software%20permite%20identificar%20y,necesidad%20de%20duplicar%20el%20trabajo.)

Seguridad en el ciclo de vida de desarrollo del software. (2022). Redhat.com.[https://www.redhat.com/es/topics/security/software-development-lifecycle-security](https://www.redhat.com/es/topics/security/software-development-lifecycle-security)

Sánchez, A. A. L. L. (2016, February 28). Requisitos vs Casos de uso vs Historias de Usuario. Angel Lozano.[http://www.angellozano.com/requisitos-del-sistema-vs-casos-uso-vs-historias-usuario/](http://www.angellozano.com/requisitos-del-sistema-vs-casos-uso-vs-historias-usuario/)

Pressman, r. s. (2002). Ingeniería del software: un enfoque practico (5a. ed.). Madrid: Mcgraw-hill interamericana.

Latam, D. (2021, 15 abril). 15 métodos de prueba que todos los desarrolladores deben conocer - DevOps Latam. DevOps Latam. https://devopslatam.com/15-metodos-de-prueba-que-todos-los-desarrolladores-deben-conocer/

¿Qué es la prueba de software y cómo funciona? | IBM. (s. f.). https://www.ibm.com/mx-es/topics/software-testing#:~:text=Hay%20muchos%20tipos%20diferentes%20de%20pruebas%20de%20software%2C,funci%C3%B3n%20de%20los%20requisitos%20funcionales.%20. . .%20More%20items

Fundamentos de la seguridad de aplicaciones. (s. f.). [https://trailhead.salesforce.com/es-MX/content/learn/modules/application-security-basics/learn-application-security-engineer-skills]


