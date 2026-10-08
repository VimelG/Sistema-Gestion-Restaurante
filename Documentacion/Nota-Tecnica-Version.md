# Nota técnica de versión – Sistema de Gestión para Restaurante (SGR)

**Versión:** v0.1.0  
**Fecha:** 8 de octubre de 2026  
**Estado:** Versión inicial de documentación y diseño  
**Asignatura:** Ingeniería de Software I

## 1. Descripción general de la versión

La versión v0.1.0 del Sistema de Gestión para Restaurante (SGR) representa una línea base inicial de documentación, análisis y diseño del proyecto. Su propósito es organizar los requisitos, los modelos UML, la arquitectura propuesta y el seguimiento de las actividades mediante GitHub y GitHub Projects.

Esta versión no representa un sistema completamente implementado ni validado mediante pruebas funcionales. Se han identificado interfaces diseñadas en Windows Forms y componentes cuyo desarrollo continúa pendiente.

## 2. Contenido de la versión

- Documento de seis requisitos funcionales y cinco requisitos no funcionales.
- Cuatro diagramas UML: casos de uso, clases, secuencia y actividades.
- Descripción de la arquitectura propuesta en tres capas: presentación, lógica de negocio y acceso a datos.
- README principal con descripción, funcionalidades, herramientas y estado del proyecto.
- Registro de cinco avances documentales y de organización.
- Seguimiento técnico de cuatro Issues seleccionados.
- Tablero GitHub Projects con 16 elementos organizados según su estado.
- Evidencia de diseño visual de las interfaces de inicio de sesión, menú principal y facturación.

## 3. Cambios controlados

Durante la preparación de esta versión se realizaron las siguientes actualizaciones:

1. Organización de los archivos del repositorio en carpetas de requisitos, diagramas UML, arquitectura y documentación.
2. Incorporación y actualización de los requisitos funcionales y no funcionales, incluyendo RF-06 para la gestión de usuarios y roles.
3. Incorporación de los cuatro diagramas UML y descripción de la arquitectura propuesta.
4. Corrección de los identificadores de requisitos asociados a las historias de usuario en los Issues.
5. Actualización del registro de cambios y revisión del tablero GitHub Projects para reflejar los avances verificados.

Los cambios documentales se registran mediante commits en el repositorio, permitiendo consultar su historial.

## 4. Estado actual del proyecto

Al cierre de esta revisión, el tablero GitHub Projects contiene 16 elementos distribuidos de la siguiente manera:

| Estado | Cantidad |
|---|---:|
| Backlog | 11 |
| Por hacer | 0 |
| En progreso | 2 |
| En revisión | 0 |
| Finalizado | 3 |

Las tareas finalizadas corresponden a la documentación de funcionalidades, el diseño de la interfaz de inicio de sesión y el diseño del módulo de facturación.

Continúan en progreso el diseño de la interfaz del menú y productos y el diseño del módulo de gestión de pedidos.

## 5. Trabajo pendiente

- Completar el diseño de la interfaz de productos y su navegación desde el menú principal.
- Incorporar los controles necesarios al formulario de gestión de pedidos.
- Diseñar la interfaz de gestión de usuarios y roles.
- Verificar la configuración y conexión de la base de datos SQL Server.
- Implementar o completar la gestión de mesas y el reporte de ventas.
- Realizar pruebas funcionales de autenticación, pedidos y facturación.
- Validar la integración entre presentación, lógica de negocio y acceso a datos.

## 6. Riesgos y limitaciones

La existencia de formularios y código fuente no garantiza por sí sola el funcionamiento completo del sistema. Algunas opciones del menú todavía no ejecutan acciones y el formulario de pedidos requiere completar su diseño. Asimismo, no se dispone aún de evidencia suficiente para considerar finalizadas las pruebas funcionales y de integración.

## 7. Próximo paso técnico

El siguiente paso será completar la interfaz de gestión de pedidos y la navegación hacia el módulo de productos. Posteriormente se deberán verificar las conexiones con SQL Server y ejecutar pruebas funcionales que permitan validar los principales procesos del restaurante.

## 8. Conclusión técnica

La versión v0.1.0 establece una base organizada para continuar el desarrollo del Sistema de Gestión para Restaurante. La documentación, los modelos UML, la arquitectura propuesta y el seguimiento mediante GitHub permiten identificar los avances realizados y las actividades pendientes, favoreciendo el control y la trazabilidad del proyecto.

Esta nota describe el estado revisado del proyecto; no constituye por sí misma evidencia de una publicación formal o de una versión ejecutable liberada.
