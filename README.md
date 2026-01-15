# MediTrack - Strategic Domain-Driven Design Analysis

Este repositorio contiene la solución propuesta para el trabajo práctico de **Diseño Estratégico DDD** enfocado en el caso de estudio de **MediTrack**, una plataforma de gestión para clínicas médicas pequeñas y medianas.

## Contenido

El archivo principal de este repositorio es [STRATEGIC_DDD_ASSIGNMENT.md](./STRATEGIC_DDD_ASSIGNMENT.md), el cual incluye el desarrollo completo de la actividad dividido en tres partes:

### 1. Decisión Arquitectónica
Análisis y justificación para la elección de una **Arquitectura Monolítica Modular** basada en:
- Tamaño del equipo (5 desarrolladores).
- Poca complejidad de infraestructura requerida.
- Tiempos acotados para el MVP (6 meses).

### 2. Contextos Delimitados (Bounded Contexts)
Identificación de los 4 dominios principales del negocio:
- **Atención Médica** (Core)
- **Turnos**
- **Facturación y Pagos**
- **Farmacia**

### 3. Lenguaje Ubicuo y Mapa de Contextos
- Definición de términos clave por contexto (glosario).
- **Mapa de Contextos** (Context Map) detallado con diagramas en Mermaid, mostrando las relaciones:
  - **Customer/Supplier**: Para flujos de dependencia directa.
  - **Shared Kernel**: Para la entidad Compartida "Paciente".

## Visualización

El documento utiliza diagramas **Mermaid** para visualizar los contextos y sus relaciones. Asegúrese de visualizar el archivo en un entorno compatible con Mermaid (GitHub, GitLab, o VS Code con extensión).
