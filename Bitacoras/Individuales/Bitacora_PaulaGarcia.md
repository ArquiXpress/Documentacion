# Bitácora Individual - Paula García

**Proyecto:** EduSystem – Sistema de gestión académica  

---

## Entrada 1

- **Fecha:** Marzo 2026  
- **Tipo de entrada:** Elaboración de diagrama de contexto  

### Descripción de la actividad
Durante esta sesión se realizó la identificación de los actores principales del sistema, incluyendo estudiantes, profesores y administradores. Además, se definieron los sistemas externos como la pasarela de pagos y el servicio de notificaciones. Con esta información se construyó el diagrama de contexto del sistema EduSystem.

### Justificación técnica
El diagrama de contexto permite entender cómo el sistema interactúa con su entorno, identificando claramente los límites del sistema y los actores externos.

### Resultados obtenidos
- Identificación de actores del sistema.
- Definición de sistemas externos.
- Creación del diagrama de contexto.

### Observaciones
Inicialmente existió confusión sobre qué elementos eran internos o externos.

---

## Entrada 2

- **Fecha:** Marzo 2026  
- **Tipo de entrada:** Diagrama de contenedores  

### Descripción de la actividad
Se desarrolló el diagrama de contenedores del sistema, incluyendo frontend (Angular), backend (Spring Boot) y base de datos, además de load balancer y replicación.

### Justificación técnica
Permite dividir el sistema en partes independientes, entender la comunicación entre componentes y mejorar la escalabilidad.

### Resultados obtenidos
- Definición de arquitectura en capas.
- Inclusión de balanceador.
- Uso de base de datos con réplica.

### Observaciones
Se comprendió mejor el flujo general del sistema: usuario → frontend → backend → base de datos y servicios externos.

---

## Entrada 3

- **Fecha:** Marzo 2026  
- **Tipo de entrada:** Atributos de calidad  

### Descripción de la actividad
Se analizaron atributos como performance, disponibilidad y deployability, relacionándolos con decisiones arquitectónicas como balanceo de carga y replicación.

### Justificación técnica
Permiten tomar decisiones de arquitectura correctas para garantizar que el sistema funcione de manera eficiente bajo diferentes condiciones.

### Resultados obtenidos
- Uso de múltiples instancias de backend.
- Balanceo de carga.
- Replicación de base de datos.

### Observaciones
Al inicio hubo confusión, pero luego se entendió la relación entre arquitectura y calidad.

---

## Entrada 4

- **Fecha:** Marzo 2026  
- **Tipo de entrada:** Uso de GitHub  

### Descripción de la actividad
Se subió la bitácora en formato Markdown al repositorio del proyecto.

### Justificación técnica
Permite control de versiones y trabajo colaborativo entre los integrantes del equipo.

### Resultados obtenidos
- Archivo creado correctamente.
- Bitácora organizada en carpeta individual.

### Observaciones
Se aprendió el uso básico de GitHub.

---

## Entrada 5

- **Fecha:** Abril 2026  
- **Tipo de entrada:** Modelado de casos de uso y diagramas de flujo  

### Descripción de la actividad
Se desarrollaron los diagramas de flujo correspondientes a los casos de uso del sistema, representando los procesos principales para los diferentes actores: comprador, vendedor y administrador. Se modelaron flujos como el proceso de checkout, la gestión de productos, la publicación de productos, la gestión de campañas, la moderación de publicaciones y la consulta de pedidos y notificaciones.

### Justificación técnica
Los diagramas de flujo permiten representar el comportamiento del sistema de manera clara, mostrando paso a paso la lógica de los procesos, incluyendo decisiones, validaciones y posibles escenarios alternativos.

### Resultados obtenidos
- Modelado de múltiples casos de uso del sistema.
- Representación de flujos con decisiones (pagos exitosos, pendientes o rechazados).
- Integración de diferentes actores dentro de los procesos.
- Mejor comprensión de la lógica del sistema.

### Observaciones
Inicialmente hubo dificultad para estructurar los flujos y sus decisiones, pero posteriormente se logró entender cómo representar la lógica del sistema de forma clara y completa.
