Modelo Híbrido: Cascada + Scrum

Proyecto: Sistema de Monitoreo de Equipos y Protocolos en Red

1. Introducción

En este documento se presenta el modelo de desarrollo híbrido que combinará dos metodologías vistas en clase: Cascada y Scrum.
El objetivo es aprovechar las ventajas de ambas metodologías para desarrollar de manera óptima el sistema de monitoreo, el cual incluye:

Scripts de captura

Cliente instalable

Servicio de Windows

Base de datos

API

Dashboard web

Reportes y gráficas

2. Justificación de la selección del modelo híbrido

El proyecto combina componentes rígidos, que requieren planificación detallada antes de programar, y componentes cambiantes, como visualizaciones y reportes.
Por ello, se eligieron Cascada y Scrum porque:

✔ ¿Por qué Cascada?

Es ideal para definir al inicio la arquitectura del sistema, los requisitos y la base técnica.

Evita errores en módulos complejos: servicio Windows, scripts de red, validación de puertos, base de datos.

Permite documentar desde el principio el diseño general del proyecto.

✔ ¿Por qué Scrum?

Permite avanzar por iteraciones cortas (sprints).

Facilita la adaptación del proyecto según retroalimentación del docente.

Reduce riesgos gracias a entregas parciales.

Permite mejorar cada módulo de manera incremental.

3. ¿Qué aporta cada metodología al proyecto?
🟦 Aportes de Cascada

Requisitos claros y documentados

Diseño técnico completo desde el inicio

Arquitectura estable para todos los módulos

Secuencia de trabajo ordenada

Reducción de fallos en la etapa de programación

Base sólida para que Scrum pueda desarrollarse sin confusión

En este proyecto, Cascada será fundamental para:

Definir cómo se recopilarán datos de MAC/IP

Diseñar la base de datos MySQL

Estructurar la API y el cliente

Diseñar el servicio de Windows

Definir formatos de reportes y métricas

🟩 Aportes de Scrum

Iteraciones de 2 semanas con avances visibles

Reuniones constantes para medir progreso

Entregas funcionales al final de cada sprint

Priorización del backl og

Adaptación rápida a mejoras solicitadas

Permite construir el dashboard y reportes de manera incremental

En este proyecto, Scrum ayudará especialmente a:

Mejorar scripts

Construir dashboard por módulos

Probar reportes y gráficas

Corregir y refinar errores en cada sprint

4. Implementación del Modelo Híbrido

El modelo híbrido Cascada + Scrum se aplicará en dos fases principales:

🟥 Fase 1 – Cascada (Planificación, Requisitos y Diseño Técnico)

Se compone de tres etapas del modelo Cascada:

1. Recolección de requisitos

Captura de MAC/IP

Monitoreo de puertos

Dashboard web

API para comunicación

Servicio Windows

Validación de duplicados

Reportes automáticos

Resultado: Documento de requisitos del sistema.

2. Diseño del sistema

Modelo de base de datos

Flujo del cliente → API → BD

Arquitectura del Servicio Windows

Esquema de reportes

Mockups del dashboard

Resultado: Arquitectura bien definida antes de iniciar programación.

3. Implementación base

Prototipo del script de captura

Prototipo de API (endpoints vacíos)

BD inicial

Cliente en blanco

Dashboard con plantilla base

Resultado: Estructura inicial lista para entrar a fase Scrum.

🟦 Fase 2 – Scrum (Desarrollo Iterativo por Sprints)

A partir de la arquitectura creada en Cascada, el desarrollo se realizará con Scrum durante 4 sprints de 2 semanas.

✔ Sprint 1 – Scripts y Base de Datos

Script de captura (MAC, IP, puertos)

Validación de puertos cada 10 minutos

Diseño final de la BD

Documentación metodológica

✔ Sprint 2 – Cliente y Servicio Windows

Cliente instalable

Servicio Windows que inicia automáticamente

Comunicación con API

Logs locales

✔ Sprint 3 – API + Dashboard Web

API funcional

Dashboard responsivo

Clasificación de protocolos (verde, amarillo, naranja, rojo)

Visualización de equipos

✔ Sprint 4 – Reportes y Gráficas

Gráficas de pastel y barras

Reporte por equipo y por protocolo

Corrección de errores

Versión final

5. Roles Scrum (Aplicados en la fase iterativa)
Rol	Responsable	Función
Product Owner	Docente	Define y valida requisitos
Scrum Master	Integrante del equipo	Facilita reuniones y elimina impedimentos
Development Team	Equipo de desarrollo	Implementa todas las funciones
6. Beneficios del modelo híbrido
✔ Beneficios de Cascada

Evita improvisación técnica

Mejora la calidad de la arquitectura

Reduce fallos tempranos

Documentación completa desde el inicio

✔ Beneficios de Scrum

Flexibilidad ante cambios

Avances constantes y revisables

Corrección continua del código

Producto final de mayor calidad

🤝 Beneficio Combinado

Cascada garantiza estabilidad técnica
Scrum garantiza adaptación y mejora continua

7. Conclusión

El modelo híbrido Cascada + Scrum es ideal para este proyecto porque combina una planificación inicial fuerte con un desarrollo adaptable y rápido. Gracias a esto, se obtiene un sistema sólido, bien diseñado y con mejoras continuas en cada sprint.
