# Introducción
Cypress, CodeceptJS, Serenity o Robot, son herramientas comunes en el desarrollo de un proyecto de testing de UI y cada año salen nuevas librerias/herramientas con la promesa de ser la solución definitiva a todos nuestros problemas de testing. Pero independientemente de la herramienta, todo proyecto de UI debe tener unos mínimos patrones de diseño que hagan su código mantenible, sino a la larga acabará siendo un caos cuando el SUT empiece a cambiar los requerimientos. 

En este curso aprenderemos a organizar nuestro código de testing de forma que sea más mantenible, escalable y fácil de utilizar por nuestros testers.

A partir de un ejemplo real profundizaremos en el testing de UI. Empezaremos identificando lo que es necesario y lo que NO es necesario testear desde la UI con un e2e test, a continuación crearemos diferentes soluciones de testing en Java, JavaScript y Python para el mismo problema, e identificaremos qué debería tener todo framework de testing. Finalmente, crearemos un CI completo con Jenkins + Docker.

# Objetivos
Después de participar en este curso, serás capaz de:
- Razonar y adaptar una estrategia de testing teniendo en cuenta diferentes arquitecturas de desarrollo.
- Reconocer y dar solución a los diferentes problemas que se encuentran al implementar tests de UI.
- Implementar una solución de UI testing mantenible en los frameworks más usados en Java, Javascript y Python
- Entender la forma correcta de implementar diferentes patrones de diseño de desarrollo en nuestra solución de testing.
- Crear un CI utilizando Jenkins y Dockers.

# Contenidos
- Definición de estrategia de testing dependiendo de la arquitectura de desarrollo.
    - Arquitecturas de microservicios y posibles estrategias de testing
    - Arquitectura de monolitos y posibles estrategias de testing
    - Diferentes tecnologias de UI implica diferentes estrategias de testing.

- Problemas más habituales en el UI testing
    - Creación de datos
    - Identificación de componentes
    - Flaky tests

- Implementando UI testing:
    - Comparar diferentes frameworks de testing en Java, Javascript y Python.
    - Implementar la misma solución de testing en Java, Javascript y Python. Teniendo en cuenta el mantenimiento, el performance y las buenas prácticas.

- Continuous testing: aplicaremos CI a nuestro proyecto de testing. Para eso crearemos el entorno de testing en un Docker, publicaremos el artefacto a un Nexus y ejecutaremos el CI en nuestro Jenkins.
    - Docker: conceptos básicos, creación de imagenes
    - Sonatype Nexus: instalación y configuración.
    - Gradle: empaquetado y gestión de dependencias. Publicación de artefactos.
    - Jenkins: configuración, creación de jobs por código.
