#  Sistema de Gestión de Becas – ITM

## Descripción

Este proyecto corresponde a un **prototipo funcional** de un sistema de gestión de becas universitarias del ITM.

El sistema fue diseñado inicialmente en **Figma** como prototipo visual y posteriormente implementado en un único archivo utilizando **HTML, CSS y JavaScript**, funcionando de manera local en el navegador.

Su objetivo es simular el flujo completo del proceso de becas, incluyendo:

* Registro de usuarios
* Inicio de sesión
* Postulación a convocatorias
* Evaluación de solicitudes
* Selección de beneficiarios
* Desembolso de becas

---

##  Objetivo del proyecto

Desarrollar un prototipo funcional que permita:

* Simular el proceso completo de gestión de becas
* Validar reglas de negocio definidas en las historias de usuario
* Representar el flujo principal del sistema
* Servir como base para una futura integración con backend y base de datos

---

##  Tecnologías utilizadas

* HTML5
* CSS3
* JavaScript (Vanilla JS)

---

## Ejecución del proyecto

###  Opción 1: Abrir directamente

1. Descargar el proyecto
2. Abrir el archivo `sistema-becas.html` con doble clic

---

### Opción 2: Usar Live Server (recomendado)

1. Abrir el proyecto en Visual Studio Code
2. Instalar la extensión **Live Server**
3. Click derecho sobre `sistema-becas.html`
4. Seleccionar **"Open with Live Server"**

---

## Funcionamiento

Este sistema funciona en modo **local**, lo que significa:

* No requiere servidor backend
* No usa base de datos real
* La información se maneja en memoria con JavaScript

Al recargar la página, los datos se reinician.

---

## Roles del sistema

El sistema simula diferentes tipos de usuario:

* Estudiante
* Administrador
* Evaluador
* Tesorero

Cada rol tiene funcionalidades específicas dentro del sistema.

---

## Funcionalidades principales

* Registro de usuarios con validaciones
* Inicio de sesión
* Gestión de convocatorias
* Postulación con documentos
* Evaluación de solicitudes
* Ranking de beneficiarios
* Registro de desembolsos

---

## Diseño

El diseño del sistema fue realizado previamente en **Figma**, definiendo:

* Estructura de interfaces
* Flujo de usuario
* Experiencia de uso (UX)

---

## Limitaciones

* No hay conexión con backend (Node.js)
* No hay base de datos (PostgreSQL)
* No hay persistencia de datos
* No se implementan servicios externos (correo, autenticación real)

---

## Mejoras futuras

* Integración con backend en Node.js
* Conexión a base de datos PostgreSQL
* Autenticación segura con JWT
* Persistencia de datos
* Validaciones más robustas
* Implementación de notificaciones reales
