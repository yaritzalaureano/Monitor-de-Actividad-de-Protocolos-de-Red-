METODOLOGÍA SCRUM – Proyecto de Monitoreo de Equipos y Protocolos en Red
✔ 1. Descripción General del Proyecto

El proyecto consiste en desarrollar un sistema que registre información de equipos en red, monitoree puertos, valide direcciones MAC/IP duplicadas, genere reportes y grafica actividad, y presente todo en una interfaz web administrable.
El sistema incluye:

Cliente instalable

Servicio de Windows

Scripts de captura

Base de datos

Dashboard web

Reportes y gráficas

✔ 2. Roles Scrum
Rol	Responsable	Descripción
Product Owner (PO)	Docente / Cliente	Define los requisitos, prioriza el Product Backlog y valida cada entrega al final del sprint.
Scrum Master (SM)	Integrante del equipo	Asegura el cumplimiento de Scrum, facilita reuniones y elimina impedimentos del equipo.
Development Team (Dev Team)	Equipo de desarrollo	Encargado de implementar todas las funcionalidades técnicas: scripts, cliente, servicio, API y dashboard.
✔ 3. Entregables del Proyecto

Los entregables están organizados por módulos funcionales:

🟦 Sprint 1 – Infraestructura y análisis

Script de captura del sistema (OS, IP, MAC, hostname)

Registro de puertos con validación de 10 minutos

Modelo de base de datos en MySQL

Repositorio GitHub

Rama documentacion

Documento metodológico (este archivo)

🟩 Sprint 2 – Aplicación Cliente y Servicio

Cliente de captura (C# o VB.NET)

Servicio de Windows que corre al inicio

Comunicación con API / servidor

Validación IP/MAC duplicadas

Logs locales en el equipo

🟨 Sprint 3 – Dashboard Web

Interfaz web responsiva

API para recibir datos de equipos

Clasificación de protocolos por nivel de seguridad (verde, amarillo, naranja, rojo)

Vista general de actividad de los equipos

🟥 Sprint 4 – Reportes y Gráficas

Gráficas de pastel para protocolos seguros e inseguros

Reportes generales por equipo y por protocolo

Optimización del dashboard

Corrección de errores

Versión final funcional

✔ 4. Fases de Scrum Aplicadas al Proyecto

Scrum no tiene fases “tradicionales”, pero sí ciclos iterativos que se repiten cada sprint:

1️⃣ Sprint Planning (Planeación del Sprint)

Duración: 2 horas por cada semana de sprint
En esta fase se decide:

Qué requisitos entrarán al sprint

Qué prioridad tienen

Qué tareas realizará el equipo

2️⃣ Daily Scrum (Reuniones Diarias)

Duración: 15 minutos diarios
Cada integrante responde:

¿Qué hice ayer?

¿Qué haré hoy?

¿Tengo algún impedimento?

3️⃣ Sprint Work (Desarrollo del Sprint)

Duración: 2 semanas por sprint
Aquí se realizan todas las actividades técnicas:

Diseño

Desarrollo

Integración

Pruebas internas

4️⃣ Sprint Review (Revisión del Sprint)

Duración: 1 hora
Se presenta lo desarrollado al Product Owner y se decide si se aprueba.

5️⃣ Sprint Retrospective

Duración: 1 hora
El equipo evalúa:

Qué funcionó

Qué no funcionó

Qué mejorar en el siguiente sprint

✔ 5. Tiempos Estimados del Proyecto (8 semanas)
Sprint	Duración	Objetivo
Sprint 1	2 semanas	Scripts, BD, documentación
Sprint 2	2 semanas	Cliente + Servicio Windows
Sprint 3	2 semanas	Dashboard Web + API
Sprint 4	2 semanas	Reportes + gráficas + versión final

Duración total del proyecto:

⏱ 8 semanas
✔ 6. Justificación de Uso de Scrum

Se selecciona Scrum porque:

Permite dividir el proyecto en módulos claros

Facilita retroalimentación constante del profesor

Reduce riesgos gracias a entregas parciales

Se adapta al cambio (muy útil para proyectos escolares)

Permite ver avances reales cada 2 semanas
