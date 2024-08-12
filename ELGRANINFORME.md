# INFORME

Nombre: Alexandra Costa P.
Cargo: Estudiante
Contacto: fucapalexa@gmail.com
Fecha: 12/08/2024

---

# **Resumen Ejecutivo**

_Un proyecto de seguridad cibernética del Fondo Conjunto de Cooperación Chile-México ha sufrido un ciberataque en una de sus infraestructuras críticas, generando como consecuencia la caída de su servidor principal durante 2 días. Se evualará el alcance de esta explotación y se propondrán medidas de mitigación._

---

## **Introducción**

A través del presente informe, se dará visibilidad a un caso de explotación de vulnerabilidades en el contexto de la implementación de un proyecto del Fondo Conjunto de Cooperación entre Chile y México.
Se ahondará en el análisis de este caso, el cual considerará herramientas, metodología y técnicas para lograr dicho propósito. Asimismo, se informará acerca de los hallazgos, la evidencia y sus métodos de adquisición.
Finalmente, se establecerán recomendaciones para mitigar el impacto de esta vulnerabilidad, así como métodos para la protección y prevención frente a futuras amenazas de seguridad.

#### Antecedentes del caso:

#### Objetivos del análisis:

Este análisis tiene como objetivo determinar qué sucedió en este ataque cibernético, cómo ocurrió y quién lo efectuó, también conocer bajo qué propósito se llevó a cabo.
Además, considerando estas interrogantes ya mencionadas, evaluar si esta explotación afectó nuestro proyecto de Servitech.

---

## Metodología:

Para determinar si este ataque cibernético ha impactado sobre nuestro proyecto "Servitech", hemos definido como método de análisis el uso de diversas herramientas que nos permitan obtener indicios o hallazgos de algún tipo de anomalía o posible vulneración para su posterior análisis y documentación.

#### Herramientas utilizadas:

Como parte de las herramientas utilizadas para este propósito, implementamos el uso de Wireshark, Nmap y Autopsy.

#### Procedimientos de Adquisición:

Para adquirir los datos de tráfico de red, primeramente nos aseguramos de utilizar un entorno seguro, en este caso Kali Linux virtualizado desde un computador de escritorio con sistema operativo Windows 10. Utilizando el entorno virtualizado de Kali Linux, procedimos a ejecutar la herramienta NMap para así obtener datos sobre las conexiones de red del equipo en el cual se encuentran alojados los archivos propios del proyecto Servitech.

En paralelo, ejecutamos el software Wireshark. Mediante este programa y haciendo uso de filtros en la captura de datos, pudimos analizar el tráfico de la red mediante procolos TCP y UDP y con esto, conocer las comunicaciones existentes entre el equipo y otros dispositivos. Estos dispositivos pueden identificarse para establecer un mapeo a través de NMap.

#### Técnicas de Análisis

Nuestra técnica de análisis fue el uso de estas herramientas ya mencionadas en el módulo anterior (Wireshark y NMap) con el objetivo de recabar datos y, posteriormente, establecer una correlación de datos según se requiera. Además, utilizamos el software Autopsy para crear una copia en imagen del repositorio local en donde se contienen los archivos del proyecto Servitech.

---

## **Hallazgos**

Tras el uso de las herramientas señaladas para llevar a cabo este análisis, nos encontramos con que no existen comunicaciones de red sospechosas ni poseedoras de comportamientos anómalos, así como tampoco se evidenció la presencia de accesos remotos ni servicios iniciados en desconocimiento del usuario del equipo. Toda comunicación, tráfico de datos y actividad registrada, obedecían a un patrón de comportamiento esperable.

#### Evidencia digital

Imágenes adjuntas:

#### Análisis de la red

Se llevó a cabo el análisis de red capturando los paquetes de tráfico y haciendo un mapeo de estas comunicaciones, mediante el softare Nmap.

#### Análisis de sistemas

Se estableció el análisis de sistemas, descartando primeramente comunicaciones con dispositivos desconocidos por el usuario. Se hizo revisión de los puertos que mantenían actividad en tiempo real al momento del análisis.

---

## **Análisis**

#### Interpretación de los Hallazgos

Mediante la evidencia adquirida podemos establecer la siguiente interpretación de hallazgos:

1. No se evidenció actividad anómala.
2. Las comunicaciones detectadas fueron las esperadas según la propia actividad en el equipo.

#### Línea de tiempo de los eventos

#### Posibles vectores de ataque

Posibles vectores de ataque

---

## Conclusiones

Tras el análisis detallado de toda la evidencia adquirida mediante las herramientas señaladas, es posible concluir que el equipo en el cuál se contienen los archivos del repositorio local con el proyecto Servitech no se ha detectado actividad sospechosa ni comunicaciones anómalas o de riesgo.

---

#### Resumen de los hallazgos clave

---

#### Respuestas a las preguntas iniciales

---

## Recomendaciones:

Se recomienda al equipo del proyecto Servitech mantener actualizado el sistema operativo desde el cuál efectúen modificaciones a su repositorio así como los programas que utilicen. También señalar que todo software a utilizar siempre sea descargado desde fuentes oficiales.

---

#### Acciones a corto plazo

Se indica el uso de software antivirus de manera periódica, así como la concientización de los integrantes del proyecto y de sus ejecutores.

---

#### Acciones a largo plazo

Mantener el plan de concientización y extenderlo a nuevos integrantes a medida que se adhieran partipantes.
Resguardar la información del proyecto y asegurarse de cifrar los datos sensibles antes de compartirlos en caso de que así se requiera.

---

#### Mejoras en los procesos de seguridad

---

## Anexos

---

#### Logs completos

---

#### Capturas de pantalla

---

#### Reportes de herramientas

---

#### Evidencia digital adicional

---
