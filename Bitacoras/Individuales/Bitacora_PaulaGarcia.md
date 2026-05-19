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

---

## Entrada 6

- **Fecha:** Abril 2026  
- **Tipo de entrada:** Configuración del entorno de desarrollo local  

### Descripción de la actividad
Se realizó la descarga y configuración local del proyecto de prueba de concepto de ArquiXpress. Se instaló y ejecutó Docker Desktop para levantar los contenedores necesarios del sistema, incluyendo backend, base de datos PostgreSQL y servicios relacionados. También se revisó la estructura general del repositorio para identificar las carpetas principales del frontend, backend, documentación y configuración.

### Justificación técnica
La configuración del entorno local permite validar el funcionamiento real del sistema antes de realizar cambios sobre el código. Además, facilita la ejecución de pruebas sin afectar la rama principal del repositorio.

### Resultados obtenidos
- Proyecto ejecutado localmente mediante Docker.
- Validación del backend en el puerto 8080.
- Identificación de la estructura del repositorio.
- Reconocimiento de los módulos principales del sistema.

### Observaciones
Inicialmente se presentaron errores relacionados con permisos de archivos y contenedores existentes, los cuales fueron corregidos para permitir la ejecución del sistema.

---

## Entrada 7

- **Fecha:** Abril 2026  
- **Tipo de entrada:** Uso de ramas en GitHub  

### Descripción de la actividad
Se creó una rama individual llamada `paula` para trabajar de forma independiente sin afectar la rama principal del proyecto. Esta rama permitió realizar cambios locales, probarlos y posteriormente subirlos al repositorio para revisión del equipo.

### Justificación técnica
El uso de ramas permite mantener aislados los cambios individuales, evitando modificaciones directas sobre `main`. Esto reduce el riesgo de afectar el trabajo del equipo y permite revisar los cambios antes de integrarlos.

### Resultados obtenidos
- Creación de la rama `paula`.
- Subida de cambios iniciales al repositorio remoto.
- Separación del trabajo individual respecto a la rama principal.

### Observaciones
Se comprendió la diferencia entre trabajar localmente, hacer commit, hacer push y modificar la rama principal.

---

## Entrada 8

- **Fecha:** Mayo 2026  
- **Tipo de entrada:** Revisión del frontend Angular  

### Descripción de la actividad
Se identificó que el proyecto contaba con un frontend Angular independiente ubicado en la carpeta `frontend`. Se ejecutó el frontend localmente y se revisó la interfaz principal del marketplace, incluyendo la navegación, el catálogo, el carrito, favoritos y las vistas asociadas a los perfiles de usuario.

### Justificación técnica
La revisión del frontend permitió identificar que la interfaz principal del sistema no correspondía únicamente a los archivos estáticos del backend, sino a una aplicación Angular separada. Esto fue importante para trabajar sobre la interfaz correcta.

### Resultados obtenidos
- Identificación del frontend real del sistema.
- Ejecución del frontend en entorno local.
- Revisión de la navegación entre inicio, tienda y carrito.
- Validación visual de la estructura de la interfaz.

### Observaciones
Inicialmente se estaban revisando archivos estáticos del backend, pero posteriormente se identificó que el frontend principal estaba en Angular.

---

## Entrada 9

- **Fecha:** Mayo 2026  
- **Tipo de entrada:** Integración frontend-backend  

### Descripción de la actividad
Se revisó la comunicación entre el frontend Angular y el backend del sistema. Se identificaron problemas de conexión relacionados con la configuración del proxy y el acceso a los endpoints del backend, especialmente para la carga del catálogo de productos.

### Justificación técnica
La correcta integración entre frontend y backend es necesaria para que la interfaz pueda consumir los datos reales del sistema, como productos, carrito, favoritos e información del checkout.

### Resultados obtenidos
- Verificación del endpoint `/api/products`.
- Identificación de errores de conexión entre Angular y backend.
- Revisión de la configuración del proxy.
- Validación de que el backend respondía correctamente desde el puerto 8080.

### Observaciones
Se evidenció la importancia de configurar correctamente la comunicación entre componentes para que el frontend pueda consumir la API del backend.

---

## Entrada 10

- **Fecha:** Mayo 2026  
- **Tipo de entrada:** Implementación y mejora del flujo de checkout  

### Descripción de la actividad
Se trabajó en la mejora del flujo de checkout del marketplace, enfocándose en que el proceso de compra mostrara información relevante para el usuario y para el sistema. Se consideraron elementos como método de pago, identificador de orden, productos incluidos e identificador de transacción.

### Justificación técnica
El checkout es uno de los procesos principales del marketplace, ya que conecta catálogo, carrito, pedidos y pago simulado. Mejorar este flujo permite representar de manera más clara el proceso de compra y validar la consistencia de la operación.

### Resultados obtenidos
- Revisión del flujo de checkout existente.
- Definición de los datos necesarios para la confirmación de compra.
- Inclusión conceptual de método de pago, ID de orden, productos e ID de transacción.
- Mejora de la presentación del resultado del pago para evitar mostrar información técnica innecesaria al usuario.

### Observaciones
El pago se mantiene como una simulación, de acuerdo con el alcance del proyecto, evitando la integración con una pasarela de pagos real.

---

## Entrada 11

- **Fecha:** Mayo 2026  
- **Tipo de entrada:** Mejora de experiencia de usuario  

### Descripción de la actividad
Se revisó la interfaz del marketplace con el objetivo de mejorar su distribución visual y hacerla más cercana a una plataforma real de comercio electrónico. Se analizaron referencias como Mercado Libre y Amazon para organizar mejor la navegación, las categorías, los productos destacados, el carrito y la sección de compras.

### Justificación técnica
Una interfaz clara mejora la usabilidad del sistema, facilita la navegación del usuario y reduce errores durante procesos importantes como búsqueda, selección de productos y checkout.

### Resultados obtenidos
- Revisión de la distribución visual del marketplace.
- Identificación de problemas de usabilidad en la interfaz.
- Propuesta de organización por secciones: inicio, tienda, catálogo, carrito y checkout.
- Mejora conceptual del flujo visual de compra.

### Observaciones
Se concluyó que la interfaz no solo debía ser funcional, sino también clara, intuitiva y coherente con el comportamiento esperado de un marketplace real.


## Entrada 12

Fecha: Mayo 2026
Tipo de entrada: Implementación de pruebas unitarias y soporte funcional

## Descripción de la actividad

Se implementaron pruebas unitarias para nuevos requisitos funcionales del sistema, correspondientes a RF-31, RF-32, RF-33, RF-34, RF-36, RF-39, RF-40, RF-41 y RF-42.

Las pruebas se organizaron por requisito para facilitar su revisión. También se agregó la lógica necesaria para que estos casos pudieran ser evaluados correctamente, incluyendo campañas vencidas, métricas de campañas, suspensión de usuarios, moderación de productos, cancelación de pedidos, consulta de pagos, notificaciones, pedidos del vendedor y direcciones de entrega en checkout.

## Justificación técnica

Estas pruebas permiten validar que cada funcionalidad cumpla su comportamiento esperado de forma aislada. Esto ayuda a detectar errores antes de integrar los módulos y reduce el riesgo de afectar procesos importantes como pagos, pedidos, notificaciones y gestión de usuarios.

## Resultados obtenidos

- Pruebas creadas para RF-31, RF-32, RF-33, RF-34, RF-36, RF-39, RF-40, RF-41 y RF-42.
- Se implementó soporte funcional para campañas, usuarios, productos, pedidos, pagos, notificaciones y direcciones de entrega.
- La ejecución de pruebas fue exitosa.
- 
## Observaciones

Se concluyó que las pruebas unitarias son necesarias para comprobar el comportamiento interno del sistema y dejar una base más estable para futuras pruebas de integración.
