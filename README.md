# Metodologias de software 🚀
Ejemplos de las metodologías tradicionales y ágiles - Práctica 
- Tradicionales
- Ágiles
## Proyecto: Aplicación "ToDo"
**🚨 Metodología en cascada 🚨**

### 1. Recolección y Análisis de Requisitos
**Objetivo:** Definir las funcionalidades básicas de la aplicación.

**Tareas:**
- Identificar las funciones principales: crear, editar, eliminar tareas, y marcarlas como completadas.
- Establecer requisitos básicos como la usabilidad en dispositivos móviles.

**Entregable:**
- Lista simple de requisitos.

### 2. Diseño del Sistema
**Objetivo:** Crear un diseño básico de la aplicación.

**Tareas:**
- Crear un diagrama sencillo de la base de datos (tablas para tareas).
- Bosquejar las pantallas principales: lista de tareas, formulario de nueva tarea.

**Entregable:**
- Bosquejo de la interfaz y diagrama de base de datos.

### 3. Implementación (Codificación)
**Objetivo:** Desarrollar la aplicación según el diseño.

**Tareas:**
- Crear la base de datos y la lógica para manejar tareas.
- Implementar la interfaz de usuario y conectar con la base de datos.

**Entregable:**
- Código fuente funcional de la aplicación.

### 4. Pruebas (Testing)
**Objetivo:** Asegurarse de que la aplicación funcione como se espera.

**Tareas:**
- Probar las funciones básicas: agregar, editar, eliminar, y marcar tareas.
- Corregir cualquier error identificado.

**Entregable:**
- Lista de pruebas realizadas y correcciones aplicadas.

### 5. Implementación (Despliegue)
**Objetivo:** Poner la aplicación en producción.

**Tareas:**
- Configurar un servidor básico para alojar la aplicación.
- Desplegar la aplicación en un entorno accesible para los usuarios.

**Entregable:**
- Aplicación disponible para su uso.

### 6. Mantenimiento
**Objetivo:** Realizar ajustes y mejoras posteriores.

**Tareas:**
- Corregir errores reportados.
- Añadir pequeñas mejoras basadas en feedback de usuarios.

**Entregable:**
- Versiones actualizadas con mejoras.

## Proyecto: MiniTienda
**🚨 Metodología RUP 🚨**

### Fase 1: Inicio
**Objetivo:** Definir el alcance y la visión del proyecto.

**Tareas:**
- Identificar los casos de uso principales: navegación de productos, gestión de carrito, procesamiento de pagos.
- Definir los requisitos iniciales, tanto funcionales como no funcionales.
- Elaborar el caso de negocio y obtener la aprobación del proyecto.

**Entregables:**
- Documento de Visión del Proyecto.
- Lista de Requisitos iniciales.
- Documento de Casos de Uso de alto nivel.
- Plan de Proyecto inicial.

### Fase 2: Elaboración
**Objetivo:** Refinar los requisitos, diseñar la arquitectura y planificar el desarrollo detallado.

**Tareas:**
- Desarrollar diagramas de casos de uso detallados.
- Diseñar la arquitectura del sistema: base de datos, lógica de negocio, y capa de presentación.
- Crear un prototipo inicial para validar la arquitectura.
- Identificar riesgos técnicos y planificar su mitigación.
- Planificar las iteraciones del desarrollo.

**Entregables:**
- Modelo de Casos de Uso completo.
- Documento de Arquitectura del Sistema.
- Prototipo inicial.
- Lista de Riesgos y Plan de Mitigación.
- Plan de Iteración.

### Fase 3: Construcción
**Objetivo:** Desarrollar el sistema de acuerdo con la arquitectura y los requisitos definidos.

**Tareas:**
- Desarrollar la funcionalidad básica en iteraciones (e.g., gestión de productos, carrito de compras, integración de pagos).
- Realizar pruebas unitarias y de integración en cada iteración.
- Refinar y ajustar la interfaz de usuario y la experiencia de compra.
- Documentar el código y las pruebas realizadas.
- Preparar el entorno para el despliegue.

**Entregables:**
- Código fuente completo de la MiniTienda.
- Documentación de Pruebas Unitarias y de Integración.
- Versiones iterativas del sistema funcional.
- Documentación técnica y de usuario.

### Fase 4: Transición
**Objetivo:** Desplegar el sistema en un entorno de producción y realizar la transición a los usuarios.

**Tareas:**
- Implementar la MiniTienda en el entorno de producción.
- Realizar pruebas beta con usuarios reales.
- Recopilar y analizar feedback de los usuarios.
- Corregir errores y realizar ajustes finales.
- Capacitar a los usuarios finales y al personal de soporte.

**Entregables:**
- MiniTienda desplegada en producción.
- Informe de Pruebas Beta y Feedback de Usuarios.
- Manual de Usuario y Guías de Capacitación.
- Documentación de Soporte Técnico.

### Mantenimiento y Evolución
**Objetivo:** Mantener y mejorar la MiniTienda post-despliegue.

**Tareas:**
- Monitorear el rendimiento y la estabilidad del sistema.
- Resolver incidentes y problemas reportados por los usuarios.
- Planificar y desarrollar nuevas funcionalidades o mejoras.
- Realizar actualizaciones y mantenimiento del sistema.

**Entregables:**
- Informe de Mantenimiento y Soporte.
- Versiones mejoradas del sistema.
- Documentación actualizada.
## Proyecto: Aplicación de Gestión de Eventos
**🚨 Metodología Scrum 🚨**

### Visión del Producto
**Objetivo:** Desarrollar una aplicación para gestionar eventos, permitiendo a los usuarios crear, editar y visualizar eventos, así como registrarse para asistir a ellos.

**Características principales:**
- Crear y gestionar eventos.
- Ver lista de eventos próximos.
- Registro de usuarios para asistir a eventos.
- Notificaciones para cambios en los eventos.

### Roles en el Proyecto
- **Product Owner:** Define la visión del producto y prioriza el backlog.
- **Scrum Master:** Facilita el proceso Scrum y elimina impedimentos.
- **Equipo de Desarrollo:** Desarrolla, prueba, y entrega incrementos del producto.

### Backlog del Producto
1. **Crear evento:**
   - Como usuario, quiero crear eventos con título, descripción, fecha, y lugar para poder gestionar mi calendario.
2. **Ver eventos próximos:**
   - Como usuario, quiero ver una lista de eventos próximos para decidir a cuál asistir.
3. **Registro en eventos:**
   - Como usuario, quiero registrarme en un evento para confirmar mi asistencia.
4. **Notificaciones:**
   - Como usuario, quiero recibir notificaciones sobre cambios en los eventos para estar al tanto.

### Sprint 1: Configuración Inicial y Primeras Funcionalidades
**Objetivo del Sprint:** Implementar la funcionalidad básica para la creación y visualización de eventos.

**Historias de Usuario:**
- Crear eventos (prioridad alta).
- Ver eventos próximos (prioridad alta).

**Tareas:**
- Configurar el entorno de desarrollo.
- Implementar el modelo de datos para eventos.
- Desarrollar la interfaz para crear eventos.
- Implementar la funcionalidad para listar eventos próximos.
- Realizar pruebas unitarias y de integración.

**Entregables:**
- Funcionalidad básica de creación y visualización de eventos.
- Entorno de desarrollo configurado.

### Sprint 2: Registro en Eventos y Notificaciones
**Objetivo del Sprint:** Implementar el registro de usuarios en eventos y la funcionalidad de notificaciones.

**Historias de Usuario:**
- Registro en eventos (prioridad alta).
- Notificaciones sobre eventos (prioridad media).

**Tareas:**
- Desarrollar la funcionalidad para que los usuarios se registren en eventos.
- Implementar notificaciones para los usuarios registrados.
- Mejorar la interfaz de usuario basada en feedback del Sprint 1.
- Continuar con pruebas y correcciones de errores.

**Entregables:**
- Funcionalidad de registro en eventos.
- Sistema de notificaciones implementado.

### Sprint 3: Refinamiento y Preparación para Despliegue
**Objetivo del Sprint:** Refinar las funcionalidades existentes, mejorar la experiencia del usuario y preparar la aplicación para su lanzamiento.

**Historias de Usuario:**
- Mejorar la experiencia del usuario (prioridad media).
- Preparar la aplicación para el despliegue (prioridad alta).

**Tareas:**
- Refinar la interfaz y usabilidad basada en feedback.
- Optimizar el rendimiento del sistema.
- Realizar pruebas finales.
- Documentar la aplicación y crear un manual de usuario.
- Configurar el entorno de producción.

**Entregables:**
- Aplicación refinada y lista para el despliegue.
- Documentación completa.

### Revisión del Sprint y Retrospectiva
Al final de cada sprint:
- **Revisión del Sprint:** Demostración de las funcionalidades completadas al Product Owner y stakeholders.
- **Retrospectiva del Sprint:** Reflexión sobre lo que funcionó bien y qué se puede mejorar en futuros sprints.

### Despliegue y Soporte
**Objetivo:** Desplegar la aplicación en producción y brindar soporte inicial.

**Tareas:**
- Desplegar la aplicación en el entorno de producción.
- Realizar un monitoreo post-despliegue.
- Recopilar feedback de los usuarios y planificar mejoras futuras.

**Entregables:**
- Aplicación en producción.
- Plan de soporte y mantenimiento.
## Proyecto: Aplicación de Seguimiento de Hábitos
**🚨 Metodología Kanban 🚨**

### Visión del Producto
**Objetivo:** Desarrollar una aplicación que permita a los usuarios registrar y seguir sus hábitos diarios, con gráficos de progreso y recordatorios.

**Características principales:**
- Registro diario de hábitos.
- Visualización del progreso a través de gráficos.
- Configuración de recordatorios.
- Personalización de hábitos.

### Flujo de Trabajo en Kanban

#### 1. **Backlog de Tareas (To Do)**
   - Definir las características clave del producto.
   - Crear el modelo de datos para almacenar hábitos y registros diarios.
   - Diseñar la interfaz de usuario para el registro de hábitos.
   - Implementar la funcionalidad para visualizar el progreso mediante gráficos.
   - Desarrollar la funcionalidad de recordatorios.
   - Realizar pruebas unitarias y de integración.
   - Desplegar la aplicación en un entorno de producción.

#### 2. **En Progreso (In Progress)**
   - Las tareas que el equipo ha comenzado a trabajar se moverán a esta columna.
   - Ejemplos:
     - **Implementación del modelo de datos.**
     - **Diseño de la interfaz de usuario.**
     - **Desarrollo de la funcionalidad de gráficos.**

#### 3. **En Revisión (In Review)**
   - Tareas que están siendo revisadas por otros miembros del equipo antes de considerarlas completas.
   - Ejemplos:
     - **Revisión del código para la funcionalidad de gráficos.**
     - **Validación de la implementación del modelo de datos.**
     - **Pruebas de usabilidad en la interfaz de usuario.**

#### 4. **Completado (Done)**
   - Tareas que han sido revisadas y aprobadas.
   - Ejemplos:
     - **Modelo de datos implementado y probado.**
     - **Interfaz de usuario diseñada y validada.**
     - **Funcionalidad de gráficos completada y aprobada.**

### Implementación de Kanban

#### Establecimiento de Límites de WIP (Work In Progress)
   - **Desarrollo:** Máximo 3 tareas en progreso al mismo tiempo.
   - **Revisión:** Máximo 2 tareas en revisión simultáneamente.
   - **Pruebas:** Máximo 2 tareas en pruebas al mismo tiempo.

#### Reuniones de Revisión de Kanban
   - **Diarias:** Revisar el tablero Kanban y ajustar prioridades según sea necesario.
   - **Semanal:** Analizar el flujo de trabajo, identificar bloqueos y ajustar los límites de WIP si es necesario.

#### Métricas de Desempeño
   - **Lead Time:** Tiempo total desde que una tarea entra en "To Do" hasta que se mueve a "Done".
   - **Cycle Time:** Tiempo que una tarea tarda desde que se comienza en "In Progress" hasta que se completa.
   - **Throughput:** Número de tareas completadas en un período de tiempo.

### Lanzamiento y Mantenimiento Continuo
**Objetivo:** Desplegar la aplicación y continuar mejorándola basándose en el feedback de los usuarios.

#### Lanzamiento Inicial
   - Desplegar la aplicación en el entorno de producción.
   - Realizar un monitoreo post-lanzamiento para identificar posibles problemas.

#### Mejora Continua
   - Recopilar feedback de los usuarios y agregar nuevas tareas al backlog.
   - Priorizar tareas en el backlog y ajustarlas en el tablero Kanban.
   - Implementar nuevas funcionalidades y corregir errores de manera iterativa.

**Entregables:**
- Aplicación desplegada y operativa.
- Tablero Kanban actualizado con nuevas tareas basadas en el feedback.
