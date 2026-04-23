# Platzi Wallet - Unidad 1

> Propuesta técnica integral para una billetera digital: diseño del sistema, comparativa cloud, implementación en AWS y plan de seguridad.

---

## Tabla de contenido

- [Visión general](#visión-general)
- [Propósito de la Unidad 1](#propósito-de-la-unidad-1)
- [Estructura de la unidad](#estructura-de-la-unidad)
  - [1. Diseño del sistema](#1-diseño-del-sistema)
  - [2. Comparativa cloud](#2-comparativa-cloud)
  - [3. Implementación y migración a AWS](#3-implementación-y-migración-a-aws)
  - [4. Plan integral de seguridad](#4-plan-integral-de-seguridad)
- [Continuidad entre tareas](#continuidad-entre-tareas)
- [Entregable final recomendado](#entregable-final-recomendado)
- [Idea central del proyecto](#idea-central-del-proyecto)

---

## Visión general

**Platzi Wallet** es una propuesta de billetera digital diseñada con un enfoque **profesional, viable, progresivo y explicativo**.  

Durante la **Unidad 1**, el proyecto se desarrolla como una línea técnica continua que parte del diseño conceptual del sistema, avanza hacia la selección de la nube más adecuada, aterriza en una estrategia real de implementación en AWS y culmina con un plan integral de seguridad.

Más que presentar cuatro tareas aisladas, esta unidad construye una **propuesta tecnológica coherente de extremo a extremo**:

1. se define el sistema,  
2. se evalúa la nube más conveniente,  
3. se establece cómo implementarlo,  
4. y se determina cómo protegerlo y operarlo correctamente.

---

## Propósito de la Unidad 1

El objetivo de esta unidad es **consolidar una base técnica completa para Platzi Wallet**, integrando arquitectura, decisión cloud, estrategia de implementación y controles de seguridad dentro de un mismo marco de trabajo.

Esto permite entender el proyecto no solo como una idea funcional, sino como una solución que puede ser:

- **explicada con claridad**,
- **justificada técnicamente**,
- **implementada de forma realista**,
- y **evolucionada por etapas**.

---

## Estructura de la unidad

### 1. Diseño del sistema

#### ¿Qué se desarrolla?
En esta primera etapa se construye el **documento base de arquitectura** de Platzi Wallet.

#### ¿Qué aporta?
- Define el alcance funcional de la billetera digital.
- Justifica la adopción de una arquitectura **monolito modular cloud-ready**.
- Explica el sistema desde tres vistas complementarias:
  - **contexto del sistema**
  - **arquitectura interna**
  - **secuencia de flujo extremo a extremo**

#### Resultado principal
Se obtiene una base técnica **entendible, defendible y suficiente para avanzar**, evitando la sobreingeniería temprana y permitiendo continuar el proyecto con una dirección clara.

#### Gráficos clave
- Diagrama a nivel del sistema
- Diagrama de arquitectura del sistema
- Diagrama de secuencia de flujo P2P

---

### 2. Comparativa cloud

#### ¿Qué se desarrolla?
Se realiza un análisis comparativo del despliegue equivalente de Platzi Wallet en **AWS, Azure y Google Cloud Platform (GCP)**.

#### ¿Qué aporta?
- Mantiene la misma arquitectura definida en la etapa anterior para comparar en igualdad de condiciones.
- Relaciona servicios equivalentes entre proveedores cloud.
- Evalúa costos estimados de despliegue y operación.
- Utiliza una **matriz de decisión** para seleccionar la opción más coherente.

#### Resultado principal
Se recomienda **AWS** como plataforma de continuidad por su equilibrio entre:

- **continuidad arquitectónica**,
- **madurez de servicios**,
- **factibilidad real de implementación futura**.

#### Gráficos clave
- Diagrama comparativo de despliegue equivalente
- Comparación de costos anuales
- Matriz de decisión

---

### 3. Implementación y migración a AWS

#### ¿Qué se desarrolla?
En esta etapa se define el plan técnico para llevar Platzi Wallet desde su diseño lógico hacia una **implementación real en AWS**.

#### ¿Qué aporta?
- Define la **arquitectura objetivo en AWS**.
- Establece una estrategia de migración **Replatform**, buscando equilibrio entre modernización y viabilidad.
- Organiza el avance en cuatro fases:
  - **Assess**
  - **Mobilize**
  - **Migrate**
  - **Operate**
- Aterriza decisiones sobre:
  - red
  - datos
  - CI/CD
  - contenedorización
  - rollback

#### Resultado principal
Se construye una propuesta implementable basada en:

- **Laravel**
- **Amazon ECS Fargate**
- **Amazon RDS MySQL**
- **Redis**
- **Amazon S3**
- **Amazon SQS**
- **Amazon CloudWatch**
- **AWS IAM**
- **Amazon Route 53 + AWS Certificate Manager**

#### Gráficos clave
- Arquitectura objetivo en AWS
- Roadmap de migración
- Diseño de red VPC Multi-AZ
- Pipeline CI/CD propuesto

---

### 4. Plan integral de seguridad

#### ¿Qué se desarrolla?
Se diseña un plan de hardening y seguridad para la arquitectura AWS previamente definida.

#### ¿Qué aporta?
- Aplica controles de seguridad viables sobre la misma base de implementación.
- Usa **STRIDE** como metodología de modelado de amenazas.
- Organiza los controles por capas:
  - **IAM**
  - **cifrado**
  - **red y perímetro**
  - **gestión de secretos**
  - **observabilidad**
  - **cumplimiento**
  - **respuesta a incidentes**
- Relaciona la solución con marcos y referencias como:
  - **PCI-DSS**
  - **Ley 29733**
  - **buenas prácticas de seguridad en AWS**

#### Resultado principal
La arquitectura deja de ser solo implementable y pasa a ser también **operable, auditable y endurecida**, con un nivel mayor de madurez técnica y organizativa.

#### Gráficos clave
- Arquitectura segura en AWS
- Matriz STRIDE por componente
- Cobertura objetivo del plan de seguridad
- Flujo de respuesta a incidentes

---

## Continuidad entre tareas

Uno de los principales valores de la Unidad 1 es que cada tarea no se entiende de forma aislada, sino como parte de una secuencia lógica de construcción del proyecto.

- **Tarea 1:** define qué es el sistema y cómo se organiza.
- **Tarea 2:** define en qué nube conviene continuar.
- **Tarea 3:** define cómo implementarlo y migrarlo.
- **Tarea 4:** define cómo protegerlo y operarlo con mayor madurez.

En conjunto, estas cuatro etapas permiten presentar Platzi Wallet como una solución que evoluciona con criterio:  
**diseñar, decidir, implementar y asegurar**.

---

## Entregable final recomendado

El entregable principal de cierre de la unidad es:

## **Informe técnico integrado de la Unidad 1**

Este informe resume las cuatro tareas en un solo documento, reutilizando los diagramas, gráficos y decisiones técnicas más importantes para explicar el avance total del proyecto.

Su valor principal está en que permite comunicar el trabajo realizado como una **propuesta técnica integral**, en lugar de mostrar tareas separadas sin relación entre sí.

---

## Idea central del proyecto

Platzi Wallet no se plantea como una arquitectura inflada o imposible de implementar desde el inicio.  
Se plantea como una solución:

- **profesional**
- **viable**
- **progresiva**
- **coherente**
- **preparada para crecer por etapas**

La continuidad entre arquitectura, cloud, implementación y seguridad constituye el principal valor técnico de la **Unidad 1**.
