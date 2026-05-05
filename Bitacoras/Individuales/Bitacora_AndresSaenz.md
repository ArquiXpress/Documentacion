# Bitácora Individual - Andrés Sáenz  

**Proyecto:** ArquiXpress – Marketplace  

---

## Entrada 1  

- **Fecha:** Domingo 22 de febrero de 2026  
- **Tipo de entrada:** Inicio de definición de requisitos funcionales (SRS y SAD)  

### Descripción de la actividad  
Durante esta jornada se inició la definición de los requisitos funcionales del sistema, en el marco del documento SRS y su relación con el SAD. Se realizó una primera estructuración de las funcionalidades principales del marketplace y su relación con los actores del sistema.  

### Justificación técnica  
La definición de requisitos funcionales permite establecer el comportamiento esperado del sistema y sirve como base para la toma de decisiones arquitectónicas, asegurando trazabilidad con el SAD.  

### Resultados obtenidos  
- Estructura inicial de requisitos funcionales.  
- Identificación de funcionalidades clave.  
- Base para integración con el SAD.  

### Observaciones  
Se evidenció la importancia de mantener consistencia entre requerimientos y arquitectura.  

---

## Entrada 2  

- **Fecha:** Lunes 23 de febrero de 2026  
- **Tipo de entrada:** Finalización de requisitos funcionales  

### Descripción de la actividad  
Se completó la definición de los requisitos funcionales del sistema, refinando su redacción para asegurar claridad, coherencia y alineación con los objetivos del proyecto.  

### Justificación técnica  
Requisitos bien definidos reducen ambigüedades y facilitan el diseño de una arquitectura consistente.  

### Resultados obtenidos  
- Requisitos funcionales completos y documentados.  
- Mayor claridad del alcance del sistema.  
- Insumo listo para diseño arquitectónico.  

### Observaciones  
Se recomienda validar continuamente los requerimientos con el equipo.  

---

## Entrada 3  

- **Fecha:** Domingo 1 de marzo de 2026  
- **Tipo de entrada:** Inicio del registro de decisiones arquitectónicas (ADR)  

### Descripción de la actividad  
Se inició la elaboración del registro de decisiones arquitectónicas dentro del SAD, identificando decisiones clave relacionadas con la estructura del sistema y atributos de calidad.  

### Justificación técnica  
El ADR permite documentar y justificar decisiones de diseño, facilitando la trazabilidad y comprensión de la arquitectura.  

### Resultados obtenidos  
- Identificación inicial de decisiones arquitectónicas.  
- Estructura base para la sección ADR.  
- Relación preliminar con atributos de calidad.  

### Observaciones  
Se identificó la necesidad de alinear las decisiones con las vistas del sistema.  

---

## Entrada 4  

- **Fecha:** Lunes 2 de marzo de 2026  
- **Tipo de entrada:** Finalización del registro de decisiones arquitectónicas (ADR)  

### Descripción de la actividad  
Se completó el registro de decisiones arquitectónicas, incluyendo decisiones como la adopción de una arquitectura monolito modular y la incorporación de mecanismos de resiliencia como redundancia básica y health checks.  

### Justificación técnica  
Formalizar las decisiones arquitectónicas permite evidenciar cómo se cumplen atributos de calidad como disponibilidad, escalabilidad y mantenibilidad.  

### Resultados obtenidos  
- Sección ADR completa en el SAD.  
- Integración con atributos de calidad.  
- Inclusión de mecanismos de resiliencia.  

### Observaciones  
Se recomienda mantener actualizado el ADR conforme evolucione el sistema.  

---

## Entrada 5  

- **Fecha:** Lunes 6 de abril de 2026  
- **Tipo de entrada:** Adecuación de formato de bitácora individual  

### Descripción de la actividad  
Se realizó la mejora y restructuración de la bitácora individual, pasando de una versión inicial simple a un formato más completo y organizado. Se incorporaron secciones detalladas como descripción de la actividad, justificación técnica, resultados obtenidos y observaciones, alineando el documento con los estándares solicitados para la entrega.  

### Resultados obtenidos  
- Bitácora reorganizada con estructura formal y consistente.  
- Mejor claridad en la presentación de avances individuales.  
- Documento listo para publicación en GitHub.  

### Observaciones  
Se recomienda mantener este formato en futuras actualizaciones para asegurar consistencia y calidad en la documentación. 

---

## Entrada 6

- **Fecha:** Martes 5 de mayo de 2026
- **Tipo de entrada:** Implementación del módulo de notificaciones por correo electrónico

### Descripción de la actividad
Se implementó el sistema de notificaciones por correo electrónico para el marketplace ArquiXpress, utilizando Resend como proveedor de envío. El desarrollo se realizó sobre la rama `andres-notificaciones` e integra el patrón Outbox ya existente en el proyecto para garantizar consistencia entre la base de datos y el envío de emails.

### Justificación técnica
Las notificaciones por correo son un componente clave en la experiencia del usuario dentro de un marketplace, ya que mantienen al comprador y vendedor informados sobre el estado de sus transacciones. Se eligió Resend por su facilidad de integración con Java, su API simple y su capa gratuita suficiente para el alcance del proyecto.

### Resultados obtenidos
- Nuevo servicio `EmailService.java` con plantillas HTML para cada tipo de notificación.
- Modificación de `NotificationPublisher.java` para enrutar eventos del outbox al servicio de email.
- Modificación de `AuthService.java` para registrar eventos de creación de cuenta y cambio de contraseña.
- Modificación de `CheckoutService.java` para registrar eventos de actualización y entrega de envío.
- Integración con `application.yml` y `docker-compose.yml` para configuración por variables de entorno.
- Siete tipos de notificación implementados:
  - Registro de cuenta
  - Orden pagada
  - Pago rechazado
  - Actualización del estado del envío
  - Envío entregado
  - Orden cancelada
  - Cambio de contraseña

### Observaciones
- La notificación de stock bajo (20% del stock tras cada restock) quedó identificada y documentada como pendiente, ya que requiere modificar la tabla de productos en coordinación con el resto del equipo.
- El dominio `arquixpress.com` requiere verificación en Resend para poder usar `noreply@arquixpress.com` como remitente oficial en producción. Por ahora se utiliza `onboarding@resend.dev` para pruebas.
