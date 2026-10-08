# Sistema de Gestión para Restaurante (SGR)

## 1. Descripción del proyecto
El Sistema de Gestión para Restaurante (SGR) es un proyecto académico desarrollado durante la asignatura Ingeniería de Software I de la Universidad Abierta para Adultos (UAPA). Su propósito es organizar y facilitar los procesos administrativos y operativos de un restaurante mediante una solución informática.

## 2. Objetivo del sistema
Diseñar un sistema digital que permita gestionar productos, pedidos, mesas, usuarios y facturación, contribuyendo a mejorar la organización de la información, reducir errores manuales y agilizar las operaciones del restaurante.

## 3. Problema que resuelve
La administración manual de pedidos, productos y facturas puede generar errores, pérdida de información y retrasos en la atención al cliente. El SGR propone centralizar estas operaciones mediante una aplicación que facilite el registro, la consulta y el seguimiento de la información.

## 4. Funcionalidades principales
- Inicio de sesión y control de acceso de usuarios.
- Registro, consulta y actualización de productos.
- Registro y administración de pedidos.
- Gestión del estado de las mesas.
- Generación y registro de facturas.
- Consulta de reportes de ventas diarias.

Estas funcionalidades forman parte del alcance propuesto y no implican que todas se encuentren implementadas.

## 5. Arquitectura seleccionada
El proyecto contempla una arquitectura cliente-servidor con separación lógica por capas:

- Capa de presentación: formularios e interfaces de usuario.
- Capa de lógica de negocio: validaciones y reglas de funcionamiento.
- Capa de acceso a datos: operaciones de consulta y almacenamiento en la base de datos.

La solución está orientada a una aplicación de escritorio desarrollada con C# y Windows Forms, utilizando SQL Server para la persistencia de datos.

## 6. Organización del frontend y backend

### Frontend
El frontend corresponde a la interfaz gráfica desarrollada con Windows Forms. Su responsabilidad es permitir la interacción de los usuarios con el sistema mediante formularios, botones, tablas y controles.

Entre las pantallas previstas se encuentran el inicio de sesión, menú principal, gestión de productos, pedidos y facturación.

### Backend
El backend corresponde a la lógica de negocio y al acceso a datos implementados en C#. Su responsabilidad es procesar las operaciones, validar la información y comunicarse con SQL Server para almacenar y recuperar registros.

### Comunicación entre frontend y backend
Cuando un usuario realiza una operación desde un formulario, la capa de presentación invoca la lógica de negocio. Esta valida la solicitud y, cuando corresponde, utiliza la capa de acceso a datos para interactuar con SQL Server. Finalmente, el resultado se devuelve a la interfaz gráfica.

En esta arquitectura de escritorio, frontend y backend representan capas lógicas de la aplicación; no se requiere una API web independiente.

## 7. Herramientas y tecnologías
- Visual Studio: entorno de desarrollo.
- C#: lenguaje de programación.
- Windows Forms: diseño de interfaces gráficas.
- SQL Server y SQL Server Management Studio: gestión de base de datos.
- GitHub: repositorio y control de versiones.
- GitHub Projects: seguimiento de actividades mediante tablero Kanban.
- Visual Paradigm Online: elaboración de diagramas UML.

## 8. Metodología de trabajo
Se utilizaron principios de desarrollo ágil, tomando como referencia Scrum para la organización del trabajo y Kanban para visualizar las tareas mediante GitHub Projects.

El tablero contempla las etapas Backlog, Por hacer, En progreso, Revisión y Finalizado.

## 9. Documentación del proyecto
La documentación contempla:
- Requisitos funcionales y no funcionales.
- Historias de usuario.
- Diagramas UML de casos de uso, clases, secuencia y actividades.
- Descripción de la arquitectura.
- Registro de avances y cambios.
- Issues para seguimiento técnico.
- Nota técnica de versión.

Los documentos se incorporarán al repositorio conforme se complete su organización.

## 10. Estado actual del proyecto
El SGR se encuentra en una etapa académica de documentación, organización de evidencias y consolidación de una versión inicial controlada.

Se han trabajado los requisitos, el diseño del sistema, los modelos UML y la planificación de actividades. La implementación y validación de cada funcionalidad deberán comprobarse mediante el código y las evidencias técnicas disponibles.

## 11. Próximos pasos
- Incorporar los documentos técnicos al repositorio.
- Revisar y organizar los Issues pendientes.
- Actualizar el tablero GitHub Projects.
- Verificar las funcionalidades implementadas.
- Documentar y etiquetar la versión inicial del proyecto.

## 12. Información académica
**Proyecto:** Sistema de Gestión para Restaurante (SGR)  
**Asignatura:** Ingeniería de Software I  
**Universidad:** Universidad Abierta para Adultos (UAPA)  
**Modalidad:** Trabajo individual
