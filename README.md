# Prácticas en empresa — REWE digital, Colonia

Repositorio de entrega de la estancia en prácticas en **[REWE digital](https://www.rewe-digital.com/)** (Colonia, Alemania), correspondiente al módulo de Formación en Empresa del **CFGS de Desarrollo de Aplicaciones Web** (2DAW, curso 2025/26).

Repositorio **compartido** por los dos participantes que realizaron las prácticas en esta empresa. Cada uno trabajó en un **departamento distinto**, por lo que la actividad individual se documenta por separado más abajo.

| Alumno/a | Departamento | Periodo |
|---|---|---|
| Carmen Castillo Gaitán | Observability | Febrero–Mayo 2026 |
| Cristian Gabriel Cocargeanu | *Placeholder* | Febrero–Mayo 2026 |

---

## Índice

- [La empresa: REWE digital](#la-empresa-rewe-digital) *(común)*
- [Presentación de empresa](#presentación-de-empresa) *(común)*
- [Carmen Castillo Gaitán](#carmen-castillo-gaitán) *(individual)*
- [Cristian Gabriel Cocargeanu](#cristian-gabriel-cocargeanu) *(individual)*
- [Vídeos de la exposición](#vídeos-de-la-exposición)
- [Materiales del repositorio](#materiales-del-repositorio)

---

## La empresa: REWE digital

REWE digital es la unidad tecnológica del **Grupo REWE**, uno de los mayores grupos de distribución y alimentación de Europa. Desde su sede en Colonia desarrolla la tecnología de prácticamente todo el negocio del grupo: comercio online (e-food), apps para clientes y plantilla, sistemas TPV, logística y fulfillment, fidelización, pagos y cloud. Cuenta con más de 2.700 especialistas repartidos en varias sedes europeas (incluida Málaga) y define su cultura como *"Home of IT"*.

> Contexto detallado en la presentación de empresa (ver abajo).

---

## Presentación de empresa

Presentación general sobre REWE digital, elaborada **conjuntamente por Carmen y Cristian** como parte común de la estancia.

**Contenido:** qué es REWE digital y su contexto en el Grupo REWE · a qué se dedica · sedes y cultura *"Home of IT"* · innovación en el retail · modelo de negocio sostenible y objetivos climáticos.

Diapositivas: [`REWE_digital.pptx`](./REWE_digital.pptx)
Vídeo (parte común): *(ver [Vídeos](#vídeos-de-la-exposición))*

---

## Carmen Castillo Gaitán

### Contexto

- **Departamento:** Observability
- **Periodo:** Febrero–Mayo 2026

El equipo de Observability monitoriza y analiza la salud y el rendimiento de los sistemas digitales (logs, métricas y trazas) para detectar y resolver incidencias rápidamente, garantizando alta disponibilidad y fiabilidad. Una de las herramientas centrales del equipo es **Netcool**, que recoge eventos de otras aplicaciones de monitorización (Grafana, Checkmk…), los clasifica y envía notificaciones ordenadas a los equipos correspondientes.

### Tareas y responsabilidades por módulo

#### Desarrollo en Entorno Cliente
Diseño y maquetación de las notificaciones (**correo electrónico y Microsoft Teams**) que envía Netcool, avisando a los equipos con la información ya clasificada y ordenada.

> Aunque no usé frameworks como React o Angular, consolidé mis bases de JavaScript: fue el lenguaje en el 99% de las prácticas.

**Herramientas:** HTML · CSS · JavaScript

#### Desarrollo en Entorno Servidor
Varias soluciones de servidor para el sistema de monitorización:
- **Integración ServiceNow ↔ Netcool/Impact (REST API):**
  - *CMDB Sync* — recuperación, transformación y deduplicación de datos de ServiceNow en tablas y *lookup files* de Netcool.
  - *Incident Automation* — creación y gestión en tiempo real de tickets en ServiceNow disparados por eventos de Netcool.
- **Policy "email repeat"** — política para Netcool/Impact que reenvía las notificaciones de un evento a intervalos configurables (a petición de un equipo).
- **Script en Python** para gestionar la adición y eliminación de usuarios en grupos de LDAP.

**Herramientas:** JavaScript · Python · API REST · SQL · PostgreSQL · LDAP · Netcool/Impact

#### Diseño de Interfaces
Rediseño visual de las plantillas de notificación, diseñando directamente en código: mejora de la apariencia, la legibilidad y la organización de la información, con criterios de **accesibilidad** (paleta apta para personas daltónicas) e incorporación de nuevos campos útiles (*Original Severity* y *Product*).

**Herramientas:** HTML · CSS · Accesibilidad

#### Despliegue de Aplicaciones
Contribución de código a repositorios con un flujo de **CI/CD** ya establecido: control de versiones (commits, push, pull requests) e integración a través de los pipelines automáticos del equipo.

**Herramientas:** Git · GitLab · CI/CD

#### Inglés
Lengua vehicular durante toda la estancia: comunicación diaria con el equipo, participación en las *dailies* y exposiciones, en un entorno de trabajo internacional.

### Stack utilizado
`JavaScript` · `Python` · `HTML` · `CSS` · `SQL` · `PostgreSQL` · `LDAP` · `Netcool/Impact` · `ServiceNow (REST API)` · `Git` · `GitLab (CI/CD)`

### Valoración personal
Más allá de lo técnico, lo que más me llevo de las prácticas es haber visto desde dentro cómo funciona una gran empresa y el mundo laboral real. Lo que más valoré fueron las **metodologías de trabajo y la organización** de los equipos. La experiencia también ha aumentado mi interés por el ámbito **DevOps**.

### Material
- Diapositivas: [`PRACTICAS_CARMEN_CASTILLO.pdf`](./PRACTICAS_CARMEN_CASTILLO.pdf)
- Vídeo individual: *( ver [Vídeos](#vídeos-de-la-exposición))*

---

## Cristian Gabriel Cocargeanu

<!-- Cristian: completa tu sección siguiendo la misma estructura que la de Carmen. -->

### Contexto

- **Departamento:** <!-- tu departamento (distinto al de Carmen) -->
- **Periodo:** Febrero–Mayo 2026

<!-- Describe brevemente tu departamento y a qué se dedicaba. -->

### Tareas y responsabilidades por módulo

#### Desarrollo en Entorno Cliente
<!-- Qué hiciste -->

**Herramientas:** <!-- ... -->

#### Desarrollo en Entorno Servidor
<!-- Qué hiciste -->

**Herramientas:** <!-- ... -->

#### Diseño de Interfaces
<!-- Qué hiciste -->

**Herramientas:** <!-- ... -->

#### Despliegue de Aplicaciones
<!-- Qué hiciste -->

**Herramientas:** <!-- ... -->

#### Inglés
<!-- Qué hiciste -->

### Stack utilizado
<!-- `Tecnología 1` · `Tecnología 2` · ... -->

### Valoración personal
<!-- Tu valoración personal de las prácticas. -->

### Material
- Diapositivas: <!-- [`nombre_de_tu_presentacion.pptx`](./nombre_de_tu_presentacion.pptx) -->
- Vídeo individual: *(pendiente — ver [Vídeos](#vídeos-de-la-exposición))*

---

## Vídeos de la exposición

| Vídeo | Responsable | Enlace |
|---|---|---|
| Parte común (empresa) | Carmen y Cristian | *(pendiente de enlace)* |
| Parte individual — Carmen Castillo Gaitán | Carmen | https://youtu.be/A1GBMs84Oy0 |
| Parte individual — Cristian Gabriel Cocargeanu | Cristian | *(pendiente de enlace)* |

---

## Materiales del repositorio

| Archivo | Descripción |
|---|---|
| [`README.md`](./README.md) | Este documento |
| [`REWE_digital.pptx`](./REWE_digital.pptx) | Presentación de empresa (común) |
| [`PRACTICAS_CARMEN_CASTILLO.pdf`](./PRACTICAS_CARMEN_CASTILLO.pdf) | Memoria de prácticas de Carmen |
| *(pendiente)* | Memoria de prácticas de Cristian |

---

## Autores

- **Carmen Castillo Gaitán** — CFGS Desarrollo de Aplicaciones Web (2DAW)
- **Cristian Gabriel Cocargeanu** — CFGS Desarrollo de Aplicaciones Web (2DAW)
