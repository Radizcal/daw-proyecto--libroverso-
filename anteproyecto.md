# Anteproyecto — Libroverso

## 1. Descripción del proyecto

Libroverso es una aplicación web que busca fomentar el hábito de la lectura mediante la gamificación. Los usuarios podrán registrar sus páginas leídas y libros completados, obtener experiencia y subir de nivel. Además, dispondrán de un personaje virtual que podrán mejorar y personalizar mediante monedas y elementos estéticos.

El objetivo es convertir el seguimiento de la lectura en una experiencia más motivadora, combinando el progreso personal con mecánicas habituales de los videojuegos.

## 2. Público objetivo

La aplicación está dirigida a personas que desean mejorar su hábito lector y encuentran motivación en los objetivos, las recompensas y la personalización.

Contará con tres perfiles: público no registrado, usuarios registrados y administrador.

## 3. Funcionalidades principales

- Registro, autenticación y cierre de sesión.
- Gestión de libros y registro de sesiones de lectura.
- Seguimiento del progreso y consulta de estadísticas personales.
- Sistema de experiencia, niveles y monedas virtuales.
- Personaje personalizable y catálogo de elementos estéticos.
- Panel de administración para gestionar usuarios y elementos estéticos.

Las funcionalidades se desarrollarán de forma progresiva, priorizando la operatividad de la aplicación y los requisitos técnicos obligatorios.

## 4. Modelo de datos

El modelo de datos se diseñará mediante una base de datos relacional normalizada en tercera forma normal (3FN).

Las entidades de negocio previstas son Libro, Libro del usuario, Sesión de lectura, Personaje, Elemento estético y Elemento del inventario. Estas entidades permitirán relacionar la actividad lectora con el progreso del usuario y el sistema de recompensas.

Los usuarios y sus roles también formarán parte de la base de datos, pero no se contabilizarán como entidades de negocio para cumplir el mínimo exigido.

## 5. Tecnologías previstas

- **Frontend:** HTML, CSS, JavaScript y Vue.js.
- **Backend:** PHP con Laravel.
- **Base de datos:** MySQL.
- **ORM y migraciones:** Eloquent y las migraciones de Laravel.
- **Control de versiones:** Git y GitHub.
- **Despliegue:** plataforma compatible con una aplicación pública accesible mediante HTTPS.

La selección tecnológica definitiva estará condicionada por la viabilidad del despliegue y el cumplimiento de los requisitos del proyecto.

## 6. Add-ons previstos

Como ampliaciones técnicas, se valorará implementar:

- Pruebas automatizadas de integración para más del 40 % de los endpoints de la API.
- Documentación de la API mediante OpenAPI/Swagger.

Estos complementos se abordarán una vez consolidado el núcleo funcional.

## 7. Objetivo final

El objetivo es desarrollar una aplicación web funcional, segura y accesible que permita gestionar la lectura y motivar la constancia mediante un sistema de progresión y recompensas, cumpliendo los requisitos técnicos establecidos para el proyecto DAW.
