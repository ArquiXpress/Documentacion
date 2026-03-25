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