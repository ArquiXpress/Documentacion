# BITÁCORA ARQUITECTÓNICA

Proyecto: ArquiXpress – Marketplace

---

## 1. Propósito del Documento

La presente bitácora tiene como objetivo registrar de manera sistemática y trazable:

- Reuniones y actas
- Inicio y cierre de iteraciones
- Decisiones de diseño arquitectónico
- Cambios en la arquitectura
- Tareas asignadas
- Pruebas de concepto (PoC)
- Análisis técnicos
- Riesgos identificados
- Observaciones relevantes

Este documento funciona como un historial técnico del proyecto, garantizando trazabilidad, justificación de decisiones y soporte académico del proceso arquitectónico.

---

## 2. Información General del Proyecto

### 2.1 Nombre del proyecto

ArquiXpress – Marketplace

### 2.2 Tipo de sistema

Marketplace digital modular con arquitectura monolítica modular y frontend desacoplado.

### 2.3 Características principales del sistema

- Identidad y acceso
- Perfil de usuario
- Portal de vendedor
- Catálogo de productos
- Inventario
- Búsqueda y descubrimiento
- Favoritos
- Carrito de compras
- Gestión de pedidos
- Envío y rastreo
- Promociones
- Publicidad

---

## 3. Decisiones Arquitectónicas Previas a la Bitácora

Antes de iniciar formalmente este registro, ya se habían definido:

### 3.1 Arquitectura general

Arquitectura basada en Monolito Modular

Separación entre:

- Frontend
- API Backend

### 3.2 Diagramas creados

- Diagrama de Contexto
- Diagrama de Contenedores
- Diagrama de Componentes (enfocado al API monolito modular)

### 3.3 Pendientes

- Diagrama de componentes del frontend
- Profundización en módulos internos del monolito

---

## 4. Estructura Estándar para Cada Entrada de Bitácora

Cada registro debe seguir el siguiente formato:

[Tipo de entrada]

(Ejemplo: Reunión / Decisión de diseño / Inicio de iteración / Prueba de concepto / Cambio arquitectónico)

Fecha:  
Hora:  
Personas involucradas:  
Iteración:  

### 1. Descripción

Resumen claro del evento o decisión.

### 2. Contexto (si aplica)

Motivación o problema que llevó al análisis.

### 3. Análisis realizado

- Alternativas consideradas
- Impacto técnico
- Impacto en requisitos

### 4. Decisión tomada (si aplica)

Explicación clara y justificada.

### 5. Tareas asignadas

Tarea  
Responsable  
Fecha objetivo  

### 6. Riesgos identificados (si aplica)

---

## 5. Formato Especial para Decisiones Arquitectónicas (Modelo ADD)

Cuando la entrada sea una Decisión de Diseño Arquitectónico, debe incluir:

### DECISIÓN ARQUITECTÓNICA

#### 1. Drivers arquitectónicamente significativos

- Requisitos funcionales relevantes
- Requisitos no funcionales (rendimiento, escalabilidad, seguridad, mantenibilidad)
- Restricciones técnicas o académicas

#### 2. Conceptos de diseño analizados

- Estilo arquitectónico (monolito, microservicios, etc.)
- Patrones (Layered, Clean Architecture, Modular Monolith, etc.)
- Tecnologías candidatas
- Estrategias de persistencia
- Estrategias de autenticación

#### 3. Diagramas preliminares

(Referencia a diagramas generados)

#### 4. Análisis comparativo

Ventajas y desventajas de cada alternativa.

#### 5. Decisión final

Justificación técnica.

#### 6. Impacto en el sistema

- Impacto estructural
- Impacto en desarrollo
- Impacto en despliegue

#### 7. Tareas derivadas

---

## 6. Definición de Categorías de Entrada

- Reunión
- Inicio de iteración
- Cierre de iteración
- Decisión arquitectónica
- Cambio arquitectónico
- Prueba de concepto
- Identificación de riesgo
- Asignación de tareas
- Revisión técnica
- Observación

---

## 7. Registro de Iteraciones

### 7.1 Iteración 1

Duración: 17 de febrero – 23 de febrero de 2026  
Modalidad: Remota  
Frecuencia de reuniones: Lunes 11:00 a.m.  
Duración de iteración: 1 semana  

### 7.2 Iteración 2

Duración: 24 de febrero – 01 de marzo de 2026  
Modalidad: Remota  
Frecuencia de reuniones: Lunes 11:00 a.m. (cambio posterior a lunes 9:00 p.m.; ver entrada 9.2)  
Duración de iteración: 1 semana  

---

## 8. Entradas de Bitácora – Iteración 1

### 8.1 Reunión de Planeación

Tipo de entrada: Reunión  
Fecha: 17 de febrero de 2026  
Hora: 11:00 a.m.  
Personas involucradas: Todo el equipo  
Iteración: 1  

#### 1. Descripción

Se definió la estructura organizacional del SAD (Software Architecture Document) y se creó un tablero en Trello para la asignación de responsabilidades.

El profesor Pavlich resolvió dudas relacionadas con los diagramas de componentes y contenedores.

#### 2. Contexto

Organización del trabajo del SAD y alineación técnica inicial sobre el alcance de diagramas.

#### 3. Análisis realizado

- Se revisó el enfoque de diagramas de contenedores y componentes.
- Se aclararon dudas sobre cómo representar módulos y componentes en el SAD.
- Se consolidaron entregables y responsables.

#### 4. Decisión tomada

Se adopta una estructura de SAD por secciones con responsables asignados y seguimiento mediante Trello.

#### 5. Tareas asignadas

| Entregable | Responsable |
|----------|------------|
| Introducción | Paula García |
| Requisitos funcionales | Andrés Sáenz |
| Modelo de dominio | Juan Vargas |
| Stakeholders | Jan Muñoz |
| Requisitos arquitectónicos | Juan Ardila |
| Restricciones | Andrés Rueda |
| Contexto | Paula García |
| Vista contenedores | Juan Vargas |
| Vista componentes | Juan Vargas |
| Vista proceso | Jan Muñoz |
| Vista física | Andrés Rueda |
| Modelo de datos | Juan Ardila |
| Decisiones arquitectónicas | Andrés Sáenz |
| Riesgos técnicos | Jan Muñoz |
| Glosario | Paula García |

#### 6. Riesgos

Riesgo de inconsistencias entre diagramas.

---

### 8.2 Reunión de Seguimiento / Cierre de Iteración 1

Tipo de entrada: Reunión  
Fecha: 23 de febrero de 2026  
Hora: No especificada  
Personas involucradas: Equipo completo (Andrés Rueda ausente)  
Iteración: 1  

#### 1. Descripción

Se resolvieron dudas sobre el SAD, despliegue y dominio.

#### 2. Análisis

- Evaluación de despliegue (VM vs servicios externos)
- Revisión de modelo de dominio

#### 3. Decisión

- Uso de máquinas virtuales
- Ajuste en cupones y stock

#### 4. Riesgos

- Retraso por ausencia
- Inconsistencia de dominio

---

## 9. Entradas de Bitácora – Iteración 2

### 9.1 Inicio de Iteración 2

Tipo: Inicio de iteración  
Fecha: 24 de febrero de 2026  

#### Descripción

Se consolidan pendientes y prioridades.

#### Decisión

Priorizar repositorio y SAD.

#### Riesgos

- Retraso prototipo
- Desalineación arquitectura

---

### 9.2 Reunión de Seguimiento

Fecha: 26 de febrero de 2026  

#### Descripción

Revisión de avances y cambio de horario.

#### Decisión

- Tareas obligatorias
- Cambio de horario

#### Riesgos

- Desalineación SAD
- Retraso prototipo

#### Cambio organizacional

Reunión → lunes 9:00 p.m.

---

### 9.3 Reunión de Seguimiento

Fecha: 1 de marzo de 2026  
Hora: 8:30  

#### Descripción

Revisión de avances y GitHub.

#### Avances

- Repositorio creado
- Diagramas actualizados
- Decisiones arquitectónicas completas

#### Riesgos

- Desalineación capa física
- Retraso prototipo

#### Cambio organizacional

Reunión → lunes 8:30 p.m.


# Bitácora individual de actividades arquitectónicas 

**Proyecto:** ArquiXpress – Marketplace 

## Entrada de bitácora 

**Fecha:** Jueves 5 de marzo de 2026  
**Persona involucrada:** Todo el equipo  
**Tipo de entrada:** Ajuste de diseño arquitectónico / Elaboración de diagrama de despliegue  

## Descripción de la actividad 

Durante esta jornada se realizaron correcciones a la vista de contenedores del proyecto ArquiXpress – Marketplace, con el propósito de mejorar la claridad en la representación de los principales componentes del sistema y su distribución por responsabilidades. Estos ajustes permitieron fortalecer la consistencia entre las distintas vistas arquitectónicas construidas hasta el momento.  

Adicionalmente, se llevó a cabo la elaboración del diagrama de despliegue, incorporando la representación de los nodos físicos principales del sistema, los artefactos desplegados en cada entorno y la relación entre frontend, balanceador de carga, backend, base de datos y servicios externos. Este trabajo permitió ampliar la documentación arquitectónica del proyecto con una vista más cercana a la infraestructura de ejecución.  

De manera paralela, el equipo inició el desarrollo del documento SRS, con el fin de formalizar los requisitos del sistema y mantener alineada la documentación funcional con la propuesta arquitectónica. También se reorganizaron tareas dentro de Trello para dar continuidad al trabajo de la siguiente fase del proyecto.  

## Justificación técnica 

La actualización de la vista de contenedores y la creación del diagrama de despliegue responden a la necesidad de refinar progresivamente la arquitectura del sistema a medida que se detallan mejor sus componentes y su infraestructura. Estas mejoras permiten representar con mayor precisión tanto la estructura lógica como la distribución física de la solución.  

Asimismo, el inicio del SRS contribuye a fortalecer la trazabilidad entre requisitos y arquitectura, lo cual resulta fundamental para justificar las decisiones de diseño tomadas por el equipo.  

## Resultados obtenidos 

Se corrigió la vista de contenedores del sistema.  

Se elaboró el diagrama de despliegue del proyecto.  

Se inició el desarrollo del documento SRS.  

Se reorganizaron tareas del equipo en Trello.  

Se fortaleció la coherencia entre arquitectura y documentación funcional.  

## Observaciones 

Durante esta jornada se indicó como pendiente para la siguiente iteración la elaboración de una bitácora individual por integrante, con el fin de mejorar la trazabilidad del trabajo realizado dentro del proyecto.  


=====================================================================================================================================================
=====================================================================================================================================================
=====================================================================================================================================================



## Entrada de bitácora 

**Fecha:** Martes 10 de marzo de 2026  
**Persona involucrada:** Todo el equipo 
**Tipo de entrada:** Revisión técnica / Análisis de decisiones tecnológicas  

## Descripción de la actividad 

Durante esta jornada se recibió retroalimentación orientada a fortalecer la justificación de las decisiones tecnológicas adoptadas en la arquitectura del proyecto ArquiXpress – Marketplace. En particular, se señaló la necesidad de sustentar de manera más clara el uso de Angular como tecnología de frontend, explicando qué necesidades del sistema atiende y cómo contribuye al cumplimiento de los requisitos planteados.  

Adicionalmente, surgió la discusión sobre la posibilidad de considerar una aplicación móvil como parte futura de la solución. Aunque esta alternativa aún no se encuentra definida, se identificó la importancia de dejar constancia de esta posible evolución tecnológica para futuras iteraciones.  

También se sugirió incorporar comparaciones entre arquitecturas, con el fin de justificar de forma más sólida la selección de la propuesta actual frente a otras alternativas posibles. Este análisis comparativo permitiría fortalecer el sustento técnico del diseño arquitectónico adoptado por el equipo.  

## Justificación técnica 

Las observaciones realizadas durante esta revisión resaltan la importancia de no limitar la documentación arquitectónica a la descripción de componentes, sino de incluir también la justificación explícita de las decisiones tecnológicas. Esto resulta clave para demostrar que las elecciones realizadas responden a necesidades concretas del sistema y no únicamente a preferencias del equipo.  

Asimismo, contemplar posibles evoluciones como una aplicación móvil y realizar comparaciones entre arquitecturas permite construir una visión más crítica, flexible y argumentada de la solución propuesta.  

## Resultados obtenidos 

Se identificó la necesidad de justificar el uso de Angular dentro de la arquitectura.  

Se dejó abierta la discusión sobre una posible aplicación móvil.  

Se reconoció la conveniencia de realizar comparaciones entre alternativas arquitectónicas.  

Se fortaleció el análisis técnico de las decisiones del proyecto.  

## Observaciones 

Esta revisión permitió evidenciar que algunas decisiones tecnológicas ya adoptadas requerían una justificación más explícita dentro de la documentación, especialmente en relación con su aporte al cumplimiento de requisitos funcionales y no funcionales.  


=====================================================================================================================================================
=====================================================================================================================================================
=====================================================================================================================================================



## Entrada de bitácora 

**Fecha:** Jueves 19 de marzo de 2026  
**Persona involucrada:** Todo el equipo  
**Tipo de entrada:** Revisión arquitectónica / Corrección de documentación y diagramas  

## Descripción de la actividad 

Durante esta jornada se recibió retroalimentación detallada por parte del profesor Pavlich respecto a múltiples aspectos de la arquitectura y su documentación. A partir de esta revisión, se identificó la necesidad de realizar correcciones en la nomenclatura utilizada en algunos artefactos, ajustar la representación UML de los diagramas y documentar con mayor precisión los protocolos de comunicación entre los distintos componentes del sistema.  

Dentro de las observaciones recibidas, se destacó la necesidad de justificar con mayor profundidad la arquitectura propuesta desde la perspectiva de rendimiento y escalabilidad. En particular, se sugirió analizar con mayor detalle la capacidad del sistema frente a carga esperada, la frecuencia de las peticiones más relevantes y la relación de estas consideraciones con los requisitos arquitectónicamente significativos.  

También se discutieron alternativas relacionadas con la base de datos, como el uso de AWS Aurora, la diferenciación entre nodos de lectura y escritura y la cantidad de réplicas que podrían considerarse para soportar crecimiento futuro. De igual manera, se planteó la importancia de realizar pruebas de concepto y pruebas de carga que permitan validar de forma empírica las decisiones tomadas.  

Finalmente, se propusieron mejoras en la organización de la documentación del proyecto, incluyendo la unificación de bitácoras en un solo sistema con hipervínculos, el uso de Markdown como formato estándar, la creación de una base de conocimiento y la apertura de repositorios específicos para documentación y pruebas de concepto.  

## Justificación técnica 

La retroalimentación recibida puso en evidencia la necesidad de fortalecer la arquitectura no solo a nivel de representación, sino también en términos de validación, justificación y trazabilidad. Corregir la notación UML y documentar los protocolos mejora la precisión de los diagramas, mientras que incorporar análisis de rendimiento y pruebas de concepto permite sustentar técnicamente que la solución propuesta puede responder a las necesidades del sistema.  

Asimismo, una mejor organización de la documentación favorece el trabajo colaborativo, el control de versiones y la evolución ordenada de la arquitectura a lo largo del proyecto.  

## Resultados obtenidos 

Se identificaron correcciones necesarias en la nomenclatura y notación UML.  

Se reconoció la necesidad de documentar protocolos de comunicación.  

Se planteó la evaluación de alternativas de base de datos con lecturas y escrituras diferenciadas.  

Se estableció la necesidad de realizar pruebas de concepto y de carga.  

Se definieron mejoras en la organización de la documentación del proyecto.  

## Observaciones 

Esta jornada representó un punto de maduración importante para la arquitectura del sistema, ya que permitió pasar de una documentación principalmente descriptiva a una visión más crítica, justificada y validable de la solución propuesta.  


=====================================================================================================================================================
=====================================================================================================================================================
=====================================================================================================================================================



## Entrada de bitácora 

**Fecha:** Sábado 4 de abril de 2026  
**Persona involucrada:** Todo el equipo  
**Tipo de entrada:** Corrección de SAD y diagramas  

## Descripción de la actividad 

Durante esta jornada se realizó una revisión detallada del documento SAD (Software Architecture Document) del proyecto ArquiXpress – Marketplace, con el fin de mejorar su claridad, consistencia y alineación con la arquitectura definida.  

Se efectuaron correcciones en la introducción, así como en la visión general de los requisitos funcionales, reorganizando la información para lograr una mejor comprensión de las funcionalidades del sistema.  

Adicionalmente, se revisó el modelo de dominio y la definición de sus entidades, realizando ajustes para asegurar coherencia con la lógica del negocio. Como complemento, se crearon tablas para describir de manera más detallada las entidades del modelo de dominio.  

Finalmente, se corrigió el diagrama de contenedores, mejorando la representación de la estructura del sistema y la interacción entre sus componentes principales.  

## Justificación técnica 

La revisión del SAD responde a la necesidad de contar con un documento arquitectónico claro, consistente y alineado con las decisiones de diseño del sistema. La mejora de sus secciones permite reducir ambigüedades y facilitar la comunicación dentro del equipo.  

Asimismo, los ajustes al modelo de dominio y al diagrama de contenedores fortalecen la comprensión tanto conceptual como estructural del sistema, lo que es clave para su implementación.  

## Resultados obtenidos 

Se corrigió la introducción del SAD.  

Se ajustó la visión general de los requisitos funcionales.  

Se revisó y corrigió el modelo de dominio.  

Se mejoró la definición de las entidades del modelo.  

Se crearon tablas para el modelo de dominio.  

Se corrigió el diagrama de contenedores.  

Se incrementó la coherencia del documento arquitectónico.  

## Observaciones 

Esta actividad fortaleció el SAD como artefacto central del proyecto, proporcionando una base más clara y consistente para futuras etapas de desarrollo y discusión técnica.



=====================================================================================================================================================
=====================================================================================================================================================
=====================================================================================================================================================


## Entrada de bitácora 

**Fecha:** jueves 16 de abril de 2026  
**Persona involucrada:** Todo el equipo  
**Tipo de entrada:** Seguimiento de proyecto / Alineación de equipo  

## Descripción de la actividad 

Durante esta jornada el equipo realizó una reunión de seguimiento con el propósito de alinear las correcciones y ajustes necesarios sobre la entrega del proyecto ArquiXpress – Marketplace. En este espacio se revisaron de manera general los comentarios y observaciones identificados sobre el trabajo desarrollado hasta el momento, con el fin de establecer cuáles aspectos debían fortalecerse tanto en la documentación como en la justificación técnica de la arquitectura propuesta.  

Asimismo, se discutió la mejor manera de organizar las actividades pendientes del equipo, distribuyendo cargas y responsabilidades de acuerdo con los componentes y apartados que cada integrante podía abordar con mayor claridad. Esta alineación permitió definir una ruta de trabajo más ordenada para continuar con las mejoras del proyecto, evitando duplicidad de esfuerzos y facilitando la continuidad del proceso.  

## Justificación técnica 

Las reuniones de alineación y distribución de cargas son importantes en proyectos colaborativos, ya que permiten responder de forma organizada a las observaciones realizadas sobre una entrega y facilitan que los ajustes posteriores se desarrollen con mayor coherencia. Además, este tipo de actividad fortalece la coordinación del equipo y contribuye a mantener consistencia entre las distintas partes del proyecto.  

## Resultados obtenidos 

Se revisaron de manera general las correcciones y ajustes pendientes sobre la entrega.  
Se identificaron aspectos que requerían fortalecimiento en la documentación y en la justificación arquitectónica.  
Se distribuyeron responsabilidades y cargas de trabajo entre los integrantes del equipo.  
Se definió una ruta de trabajo para abordar las mejoras del proyecto en las siguientes jornadas.  

## Observaciones 

La jornada permitió alinear al equipo frente a las correcciones necesarias y organizar de manera más clara la continuación del proyecto, dejando una base de trabajo más estructurada para las siguientes actividades.



=====================================================================================================================================================
=====================================================================================================================================================
=====================================================================================================================================================


=====================================================================================================================================================
=====================================================================================================================================================
=====================================================================================================================================================


## Entrada de bitácora 

**Fecha:** Martes 21 de abril de 2026  
**Persona involucrada:** Todo el equipo  
**Tipo de entrada:** Revisión técnica / Validación arquitectónica mediante pruebas automáticas  

## Descripción de la actividad 

Durante esta jornada se recibió retroalimentación del profesor orientada a fortalecer la etapa de validación de la arquitectura del proyecto ArquiXpress – Marketplace. En particular, se indicó la necesidad de diseñar e implementar pruebas automáticas de integración que permitieran evaluar tanto requisitos funcionales como requisitos no funcionales del sistema.  

A partir de esta orientación, el equipo identificó que las pruebas no debían limitarse únicamente a verificar el correcto funcionamiento de módulos aislados, sino que también debían servir como mecanismo de evidencia para demostrar que las decisiones arquitectónicas adoptadas han sido apropiadas frente a las necesidades del sistema. En este sentido, se enfatizó la importancia de aislar aquello que ya funciona correctamente, de modo que pueda validarse formalmente y utilizarse como soporte del diseño propuesto.  

Asimismo, se reconoció como pendiente prioritario la definición y ejecución de pruebas asociadas a requisitos no funcionales, especialmente aquellas relacionadas con atributos de calidad como rendimiento, mantenibilidad y comportamiento bajo integración entre componentes. Finalmente, se estableció la necesidad de actualizar las bitácoras individuales para reflejar estas nuevas actividades de validación y su aporte a la justificación de la arquitectura.  

## Justificación técnica 

La incorporación de pruebas automáticas de integración permite validar el comportamiento conjunto de los componentes principales del sistema, superando una verificación puramente teórica o documental de la arquitectura. Esto resulta fundamental para demostrar que las decisiones de diseño adoptadas no solo son conceptualmente correctas, sino también efectivas en la práctica frente a los requisitos funcionales y no funcionales del proyecto.  

Adicionalmente, orientar las pruebas hacia la validación de atributos de calidad fortalece la trazabilidad entre requisitos, decisiones arquitectónicas y evidencia empírica. De esta forma, la arquitectura deja de ser únicamente una propuesta de diseño y pasa a estar respaldada por resultados observables y repetibles.  

## Resultados obtenidos 

Se definió la necesidad de implementar pruebas automáticas de integración.  
Se estableció que las pruebas deben cubrir tanto requisitos funcionales como no funcionales.  
Se identificó que las pruebas deben servir como evidencia de la validez de las decisiones arquitectónicas tomadas.  
Se reconoció la importancia de aislar y documentar los componentes y flujos que ya funcionan correctamente.  
Se priorizó la actualización de las bitácoras individuales en función de estas actividades de validación.  

## Observaciones 

Esta jornada marcó una transición importante en el proyecto, al mover el foco desde la definición y documentación de la arquitectura hacia su validación práctica. La retroalimentación recibida refuerza la necesidad de sustentar las decisiones arquitectónicas mediante pruebas concretas, lo cual aporta mayor solidez técnica y académica al desarrollo del sistema.