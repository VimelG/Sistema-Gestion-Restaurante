# Requisitos del Sistema de Gestión para Restaurante (SGR)

## 1. Introducción

Este documento presenta los requisitos funcionales y no funcionales del Sistema de Gestión para Restaurante (SGR), desarrollado como proyecto académico de la asignatura Ingeniería de Software I de la Universidad Abierta para Adultos (UAPA).

Los requisitos permiten definir las funciones que deberá realizar el sistema y las características de calidad necesarias para su funcionamiento.

## 2. Objetivo de los requisitos

Establecer las necesidades principales del sistema para orientar su diseño, desarrollo, implementación y evaluación, garantizando una solución organizada para la gestión de las operaciones de un restaurante.

## 3. Requisitos funcionales

Los requisitos funcionales describen las operaciones que deberá permitir el sistema.

| Código | Requisito | Descripción |
|---|---|---|
| RF-01 | Gestión de productos | Permitir al administrador registrar, consultar, modificar y eliminar productos del menú. |
| RF-02 | Gestión de pedidos | Permitir al cajero registrar pedidos, seleccionar productos y calcular sus importes. |
| RF-03 | Generación de facturas | Generar facturas a partir de los pedidos, mostrando productos, cantidades y total correspondiente. |
| RF-04 | Reporte de ventas | Permitir al administrador consultar un reporte de las ventas realizadas durante el día. |
| RF-05 | Gestión de mesas | Permitir registrar y actualizar el estado de las mesas del restaurante. |

## 4. Requisitos no funcionales

Los requisitos no funcionales establecen las características de calidad, seguridad y funcionamiento esperadas.

| Código | Requisito | Descripción |
|---|---|---|
| RNF-01 | Usabilidad | El sistema deberá contar con una interfaz clara, intuitiva y fácil de utilizar. |
| RNF-02 | Rendimiento | Las operaciones habituales deberán responder en un tiempo objetivo de tres segundos bajo condiciones normales de uso. |
| RNF-03 | Seguridad | El acceso a las funciones deberá estar controlado mediante autenticación de usuarios y permisos según su rol. |
| RNF-04 | Disponibilidad | El sistema deberá estar disponible durante el horario de operación del restaurante, sujeto al funcionamiento del equipo y la base de datos. |
| RNF-05 | Mantenibilidad | El sistema deberá organizarse en componentes que faciliten la corrección de errores y futuras modificaciones. |

## 5. Actores del sistema

### Administrador
Responsable de gestionar productos, supervisar las operaciones, consultar reportes y administrar las funciones autorizadas del sistema.

### Cajero
Responsable de registrar pedidos, consultar productos disponibles y realizar operaciones de facturación.

## 6. Relación entre requisitos y módulos

| Módulo | Requisitos relacionados |
|---|---|
| Productos | RF-01 |
| Pedidos | RF-02 |
| Facturación | RF-03 |
| Reportes | RF-04 |
| Mesas | RF-05 |
| Inicio de sesión y control de acceso | RNF-03 |

## 7. Estado de los requisitos

Los requisitos documentados constituyen la base de planificación y diseño del SGR. Su implementación y cumplimiento deberán verificarse mediante pruebas y evidencias del sistema.

Este documento no representa una certificación de que todas las funcionalidades se encuentran implementadas.

## 8. Control de documentación

- **Proyecto:** Sistema de Gestión para Restaurante (SGR).
- **Asignatura:** Ingeniería de Software I.
- **Universidad:** Universidad Abierta para Adultos (UAPA).
- **Modalidad:** Trabajo individual.
- **Estado:** Documentación de requisitos para cierre técnico académico.
