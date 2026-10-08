# Arquitectura del Sistema de Gestión para Restaurante (SGR)

## 1. Introducción

El Sistema de Gestión para Restaurante (SGR) contempla una arquitectura de tres capas, diseñada para separar la interfaz de usuario, la lógica de negocio y el acceso a los datos. Esta organización facilita el mantenimiento, la seguridad y la evolución del sistema.

## 2. Arquitectura seleccionada

Se propone una arquitectura de aplicación de escritorio con separación lógica en tres capas:

- Capa de presentación (Frontend).
- Capa de lógica de negocio (Backend).
- Capa de acceso a datos (Backend).

La aplicación utiliza C# y Windows Forms, con SQL Server como sistema gestor de base de datos.

## 3. Frontend: capa de presentación

El frontend corresponde a los formularios de Windows Forms que permiten a los usuarios interactuar con el sistema.

Sus principales responsabilidades son:

- Mostrar las interfaces gráficas.
- Recibir los datos introducidos por los usuarios.
- Presentar productos, pedidos y facturas.
- Mostrar mensajes de confirmación y error.
- Enviar solicitudes a la lógica de negocio.

Entre las interfaces previstas se encuentran el inicio de sesión, menú principal, gestión de productos, pedidos y facturación.

## 4. Backend: lógica de negocio

El backend se encarga de procesar las operaciones solicitadas desde la interfaz de usuario.

Sus responsabilidades incluyen:

- Validar los datos recibidos.
- Aplicar las reglas de negocio del restaurante.
- Procesar pedidos y calcular importes.
- Gestionar las operaciones de facturación.
- Controlar las operaciones autorizadas según el usuario.
- Coordinar el acceso a la información almacenada.

## 5. Capa de acceso a datos

Esta capa permite la comunicación entre la lógica de negocio y SQL Server.

Sus responsabilidades son:

- Registrar información de productos, usuarios, pedidos y facturas.
- Consultar los registros almacenados.
- Actualizar información existente.
- Eliminar registros cuando corresponda y esté autorizado.
- Gestionar las conexiones y operaciones con la base de datos.

## 6. Comunicación entre frontend y backend

La comunicación se realizará mediante llamadas internas entre las capas de la aplicación desarrollada en C#.

El flujo previsto será:

1. El usuario realiza una acción desde un formulario de Windows Forms.
2. La capa de presentación envía la solicitud a la lógica de negocio.
3. La lógica de negocio valida la información y procesa la operación.
4. Cuando es necesario, se utiliza la capa de acceso a datos para consultar o modificar información en SQL Server.
5. El resultado de la operación regresa a la lógica de negocio.
6. La interfaz presenta al usuario el resultado correspondiente.

Al tratarse de una aplicación de escritorio, no se requiere una API REST independiente para la comunicación entre frontend y backend.

## 7. Herramientas y tecnologías

| Herramienta | Función |
|---|---|
| Visual Studio | Entorno de desarrollo |
| C# | Lenguaje de programación |
| Windows Forms | Interfaces gráficas |
| SQL Server | Almacenamiento de información |
| SQL Server Management Studio | Administración de la base de datos |
| GitHub | Control de versiones |
| GitHub Projects | Seguimiento de actividades |
| Visual Paradigm Online | Modelado UML |

## 8. Ventajas de la arquitectura

- Separación de responsabilidades.
- Mayor facilidad para mantener y modificar el sistema.
- Organización modular de las funcionalidades.
- Posibilidad de reutilizar componentes.
- Mejor control de las operaciones de acceso a datos.

## 9. Estado actual

La arquitectura descrita corresponde al diseño técnico propuesto para el SGR. Su implementación completa deberá verificarse mediante el código fuente, las pruebas y las evidencias disponibles.

## 10. Próximos pasos

- Revisar la implementación de las capas propuestas.
- Verificar la comunicación con SQL Server.
- Completar las funcionalidades pendientes.
- Ejecutar pruebas funcionales.
- Registrar los resultados y cambios en GitHub.
