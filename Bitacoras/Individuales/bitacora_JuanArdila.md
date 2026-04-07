# Bitácora individual de actividades arquitectónicas Juan L. Ardila

**Proyecto:** ArquiXpress – Marketplace  

*Entrada #1 de bitácora*
- **Fecha:** 9 de marzo de 2026
- **Persona involucrada:** Juan L. Ardila
- **Tipo de entrada:** Ajuste de diseño arquitectónico / Refinamiento de atributos de calidad

## Descripción de la actividad
Durante esta jornada se realizó una ampliación y refinamiento del conjunto de Requerimientos Arquitectónicamente Significativos (ASR) del proyecto ArquiXpress – Marketplace. En particular, se añadieron y documentaron los ASR desde el ASR-13 en adelante, con el fin de complementar la visión de calidad del sistema y cubrir escenarios que no habían quedado suficientemente explícitos en la versión anterior.

Los nuevos ASR incorporados se enfocaron en atributos relevantes para la operación del marketplace, especialmente en temas de escalabilidad, disponibilidad, confiabilidad y mantenibilidad. Entre ellos se incluyeron requerimientos relacionados con la capacidad del sistema para soportar picos de uso en momentos de alta demanda, garantizar la disponibilidad de las fotos y detalles del producto aun ante fallas parciales, mantener un historial de compras correcto y consistente, asegurar que la actualización de estados de envío siga una secuencia válida, y permitir que cambios futuros en reglas del negocio no afecten órdenes ya creadas.

Este ejercicio permitió fortalecer la especificación de escenarios de calidad del sistema, dando mayor claridad sobre el comportamiento esperado del marketplace frente a situaciones reales de uso, crecimiento y evolución.

## Justificación técnica
La incorporación de los ASR-13 al ASR-17 responde a la necesidad de completar la definición de requisitos no funcionales críticos para la arquitectura del sistema. Aunque ya se contaba con requerimientos orientados a rendimiento, seguridad y confiabilidad, todavía era necesario detallar escenarios asociados al crecimiento del sistema, la tolerancia a fallas parciales, la consistencia de la información visible para los actores del negocio y la facilidad de adaptación ante cambios futuros.

Desde el punto de vista arquitectónico, estos nuevos ASR ayudan a orientar decisiones de diseño relacionadas con escalabilidad, validación de estados, manejo de errores parciales, consistencia entre módulos y evolución controlada de reglas del negocio. Su inclusión mejora la trazabilidad entre necesidades de calidad y decisiones arquitectónicas posteriores.

## Resultados obtenidos
- Se ampliaron los requerimientos arquitectónicamente significativos del proyecto desde el ASR-13 hasta el ASR-17.
- Se incorporaron nuevos escenarios relacionados con picos de demanda, continuidad del servicio, exactitud del historial de compras, integridad de estados logísticos y facilidad de actualización de reglas.
- Se fortaleció la definición de atributos de calidad relevantes para el marketplace.
- Se mejoró la base de análisis para futuras decisiones de diseño e implementación de la arquitectura.

## Observaciones
La inclusión de estos nuevos ASR representa un avance importante en la madurez de la propuesta arquitectónica del sistema, ya que amplía la cobertura de escenarios de calidad y permite que el diseño del marketplace contemple no solo su funcionamiento actual, sino también condiciones de crecimiento, operación continua y evolución futura.



*Entrada #2 de bitácora*
- **Fecha:** 24 de marzo de 2026
- **Persona involucrada:** Juan Luis Ardila
- **Tipo de entrada:** Gestión documental

## Descripción de la actividad
Durante esta jornada se creó la entrada de Bitácoras Individuales, se convirtió una entrada de bitácora al formato Markdown (.md) y se cargó en el repositorio de documentación del proyecto.

## Justificación técnica
Esta actividad permitió organizar la documentación en un formato claro, ligero y compatible con el repositorio, facilitando su almacenamiento y consulta.

## Resultados obtenidos
- Se convirtió la bitácora a formato .md.
- Se cargó el archivo en el repositorio de documentación.

## Observaciones
La actividad ayudó a mantener actualizada y ordenada la documentación del proyecto.



*Entrada #3 de bitácora*
- **Fecha:** 4 de abril de 2026
- **Persona involucrada:** Juan Luis Ardila
- **Tipo de entrada:** Corrección de documentación arquitectónica / Refinamiento de requerimientos

## Descripción de la actividad
Durante esta jornada se realizaron ajustes al documento SAD del proyecto ArquiXpress – Marketplace. En particular, se corrigió la tabla de ASR, completando la columna correspondiente a los requerimientos funcionales asociados, la cual se encontraba pendiente. Además, se realizó una corrección de la sección de stakeholders del SAD, con el fin de mejorar su claridad y consistencia.

## Justificación técnica
La actualización de la tabla de ASR era necesaria para fortalecer la trazabilidad entre los requerimientos funcionales y los requerimientos arquitectónicamente significativos del sistema. Asimismo, la corrección de la sección de stakeholders permitió mejorar la identificación de los actores relevantes y su relación con las decisiones arquitectónicas del proyecto.

## Resultados obtenidos
- Se completó la columna de requerimientos funcionales asociados en la tabla de ASR.
- Se corrigió la sección de stakeholders del SAD.
- Se mejoró la consistencia y completitud del documento arquitectónico.

## Observaciones
Esta actividad permitió fortalecer la calidad del SAD y dejar más clara la relación entre los requerimientos funcionales, los atributos de calidad y los actores del sistema.



*Entrada #4 de bitácora*
- **Fecha:** 5 de abril de 2026
- **Persona involucrada:** Juan Luis Ardila
- **Tipo de entrada:** Actualización de modelo de datos / Reunión de coordinación

## Descripción de la actividad
Durante esta jornada se elaboró la versión 2 del modelo de datos, representada en el diagrama entidad-relación, tomando como base el nuevo diagrama de dominio definido en el SAD. Adicionalmente, se llevó a cabo una reunión de trabajo en la cual se asignó a Juan Luis Ardila y Paula García la responsabilidad de realizar el SAD.

## Justificación técnica
La construcción de una segunda versión del modelo de datos fue necesaria para mantener la coherencia entre el diagrama de dominio y la representación estructural de la información del sistema. La reunión también permitió definir responsables claros para continuar con el desarrollo del documento arquitectónico.

## Resultados obtenidos
- Se elaboró la versión 2 del modelo de datos (diagrama E/R).
- El modelo fue ajustado con base en el nuevo diagrama de dominio del SAD.
- Se definió junto con Paula García la asignación para desarrollar el SAD.

## Observaciones
La actualización del modelo de datos ayudó a mantener alineados los distintos artefactos del proyecto y la reunión permitió organizar mejor las responsabilidades del equipo.



*Entrada #5 de bitácora*
- **Fecha:** 6 de abril de 2026
- **Persona involucrada:** Juan Luis Ardila
- **Tipo de entrada:** Elaboración de documentación / Gestión documental / Apoyo a sustentación

## Descripción de la actividad
Durante esta jornada se avanzó en la elaboración del documento SRS del proyecto, específicamente en las secciones de tabla de contenido, visión del producto, casos de uso y caracterización de los usuarios. Además, se cargaron en el repositorio de documentación las versiones 1 y 2 del modelo de datos en diagrama entidad-relación. Finalmente, se agregó la sección de ASR en la diapositiva de la sustentación.

## Justificación técnica
El desarrollo de estas secciones del SRS permitió fortalecer la especificación funcional del sistema y dejar documentados elementos importantes para su comprensión. La carga de las versiones del modelo de datos al repositorio facilitó la trazabilidad documental, mientras que la inclusión de la sección de ASR en la sustentación permitió mejorar la presentación de los aspectos arquitectónicos del proyecto.

## Resultados obtenidos
- Se elaboraron las secciones de tabla de contenido, visión del producto, casos de uso y caracterización de usuarios en el SRS.
- Se cargaron al repositorio las versiones 1 y 2 del modelo de datos.
- Se agregó la sección de ASR en la diapositiva de la sustentación.

## Observaciones
Esta actividad permitió avanzar tanto en la documentación funcional del sistema como en la organización de los artefactos del proyecto y en la preparación de la sustentación.