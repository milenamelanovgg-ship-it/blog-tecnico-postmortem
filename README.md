# Entregable Final: Blog Técnico con Post-Mortem Constructivo

**Estudiante:** Milena Melano  
**Curso:** Mentalidad de Crecimiento y Comunicación en Entornos Digitales  
**Año:** 2026  

---

## Paso 1 — Selección de plataforma

Elegí **Notion** para estructurar y publicar la cara pública de mi blog técnico debido a su flexibilidad para el diseño de componentes de información y la velocidad que ofrece para disponibilizar contenido en la web. Me permite mantener una documentación limpia, legible y sumamente profesional sin necesidad de configurar servicios complejos de hosting, facilitando que perfiles tanto técnicos como de negocio consuman el análisis de forma directa.

En paralelo, integré **GitHub** como repositorio central de este conocimiento. Siguiendo una mentalidad nativa de ingeniería de producto (*"Ship It"*), esta dualidad me otorga ventajas complementarias: Notion opera como la interfaz ágil de lectura para cualquier stack de stakeholders, mientras que GitHub actúa como el motor de control de versiones, asegurando la trazabilidad absoluta, el versionado del contenido en Markdown y la transparencia histórica de cada cambio editorial realizado en el proyecto.

* **URL pública del blog en Notion:** [[https://milenamelano.notion.site/auditoria-integral-experiencia-nutrigo-2026](https://app.notion.com/p/Entregable-Final-Blog-T-cnico-con-Post-Mortem-Constructivo-d55e3fad2eb1472ab2860196116ef628?source=copy_link)]([https://milenamelano.notion.site/auditoria-integral-experiencia-nutrigo-2026](https://app.notion.com/p/Entregable-Final-Blog-T-cnico-con-Post-Mortem-Constructivo-d55e3fad2eb1472ab2860196116ef628?source=copy_link))
* **Repositorio en GitHub:** [https://github.com/milenamelanovgg-ship-it/blog-tecnico-postmortem](https://github.com/milenamelanovgg-ship-it/blog-tecnico-postmortem)

---

## Paso 2 — Creación de la página en Notion

Abrí mi espacio de trabajo en Notion y creé una página dedicada con una arquitectura optimizada para la lectura. Para su distribución pública, utilicé el menú superior derecho configurando los permisos de acceso abierto a la web.

> <img width="1358" height="636" alt="screenshot-1782494368801" src="https://github.com/user-attachments/assets/56d5fe18-976a-4f71-ac39-1d064e8db4ac" />


---

## Paso 3 — Preparación de la entrada de blog

# Post-Mortem Constructivo: Auditoría Integral de Experiencia NutriGO

**Autor:** Milena Melano | **Fecha:** 2026 | **Categoría:** UX/CX Strategy, Digital Product Analysis

### Nota para el lector
Este espacio de documentación técnica y análisis de producto está estructurado para ser útil tanto a desarrolladores como a líderes de negocio. Cada vez que utilicemos métricas específicas de la industria (como UX, CX, KPIs o SLAs), incluiremos su desglose contextual para garantizar una lectura clara, ágil y aplicable a cualquier entorno de producto.

---

### 1. Contexto y Propósito Analítico
El proyecto consistió en realizar un análisis estratégico integral de **NutriGO**, una plataforma digital de salud y bienestar orientada a la comercialización de productos nutricionales altamente personalizados y sustentables. El objetivo central del ejercicio fue aplicar de forma práctica marcos de referencia de experiencia de usuario, diagnóstico preciso de fallas operativas y estructuración de soluciones escalables bajo metodologías ágiles de desarrollo.

#### Propósito Real del Ejercicio:
* Validar la comprensión de metodologías de análisis de experiencia del cliente (CX/UX).
* Aplicar frameworks de diagnosis sistemática para aislar causas raíz sobre síntomas visuales superficiales.
* Traducir fricciones de negocio en requerimientos técnicos explícitos (*User Stories*) aptos para ingresar a un backlog de desarrollo.
* Demostrar habilidades de comunicación limpia y asíncrona, integrando el feedback de forma iterativa.

#### Ecosistema de Producto y Target:
* **Propuesta de Valor:** Personalización nutricional basada en la máxima calidad, sostenibilidad e ingredientes con procedencia transparente.
* **Buyer Persona (Sofía):** 30 años, profesional de marketing en el sector corporativo. Ritmo de vida acelerado, agenda saturada y una fricción crítica de tiempo. Su necesidad es optimizar su alimentación diaria sin desgastarse en flujos digitales lentos, interfaces confusas o validaciones manuales de compra.

---

### 2. El Problema: Matriz de Fricciones Críticas Diagnosticadas
Durante la auditoría del flujo digital de NutriGO, se identificaron **tres capas de fricción clave** que interrumpían el embudo de conversión y destruían la lealtad de la base de usuarios:

| Capa de Fricción | Fricción Diagnosticada (Causa Raíz) | Métrica de Impacto / Consecuencia |
| :--- | :--- | :--- |
| **Capa 1: Social Proof (Validación)** | • Ausencia total de testimonios reales y reviews visibles en la e-shop.<br>• Imposibilidad de verificar la confianza de la marca de forma autónoma. | **Caída en la conversión** en la fase de consideración de Sofía por falta de respaldo y credibilidad comercial. |
| **Capa 2: Compra Incierta (Checkout)** | • Flujo de compra confuso, con interfaces ambiguas y pasos redundantes.<br>• Existencia de trabas operativas o validaciones de datos manuales. | **Abandono crítico de carritos** (*checkout drop-off*) en la etapa transaccional final. |
| **Capa 3: Soporte y Post-Compra** | • Respuestas lentas en canales de atención directa.<br>• Desconexión comunicacional e inconsistencia de UX entre canales post-venta. | **Deterioro del Lifetime Value (LTV)** y fuga activa de clientes retenidos hacia competidores. |

---

### 3. Acciones: Soluciones e Implementaciones Modeladas

#### Acción 1: Mapeo del Customer Journey y Diagnóstico
Se documentaron las fases críticas del viaje de Sofía: **Descubrimiento** (pauta y redes), **Consideración** (catálogo) y **Compra/Post-venta**. Al evaluar la experiencia actual frente al estado óptimo deseado, se aislaron las caídas de interacción utilizando matrices de puntuación cuantitativas para sustentar el plan de ingeniería de producto.

#### Acción 2: Diseño del Plan Estratégico Escalable

##### 🌐 Eje Web: Tienda & Social Proof
* **Módulo de Validación Social:** Integración de calificaciones con estrellas y reseñas verificadas visibles directamente en el catálogo de productos.
* **Checkout Optimizado (One-Step):** Rediseño de la interfaz para consolidar la transacción en un único paso limpio, eliminando campos innecesarios y formularios densos.
* **Soporte Ágil Transaccional:** Automatización de consultas repetitivas de stock y tiempos de entrega mediante componentes ágiles de respuesta inmediata, proyectando una optimización del flujo del embudo en un 80%.

##### 👥 Eje Canales: Comunidad y Transparencia
* **Comunidad Exclusiva Activa:** Despliegue de canales privados de alta fidelización (WhatsApp) para la interacción directa entre usuarios sobre metas, hábitos y recetas.
* **Automatización Conversacional:** Implementación de bots inteligentes entrenados para absorber consultas transaccionales de primer nivel en redes sociales.
* **Transparencia Informativa:** Acceso público a las fichas técnicas detalladas (macros, procedencia e ingredientes sustentables) para empoderar las decisiones del cliente de manera ágil.

---

### 4. De la Fricción al Backlog: Requerimientos Técnicos
Fieles al enfoque metodológico de traducir dolores en soluciones de software executables, los hallazgos se estructuraron en historias de usuario (*User Stories*) priorizadas para desarrollo:

#### 🚀 Sprint 1: Bloqueantes de Conversión (Prioridad Crítica)
* **US-01 | Módulo de Validación Social:** *Como Sofía, quiero ver calificaciones con estrellas y comentarios verificados para validar la calidad del menú de NutriGO de forma autónoma antes de comprar.*
* **US-02 | Checkout Simplificado (One-Step):** *Como Sofía, quiero completar mis datos y pagar en una sola interfaz limpia para finalizar mi pedido semanal en menos de 2 minutos.*

#### 🔄 Sprint 2: Retención y Escala (Prioridad Alta)
* **US-03 | Bot Conversacional de FAQs:** *Como cliente activa, quiero consultar dudas frecuentes sobre conservación y envíos mediante un bot automático para obtener respuestas inmediatas (Target SLA de respuesta menor a 5 segundos).*

---

### 5. Estructura de Control: KPIs del Producto
Para verificar el impacto comercial real de estas implementaciones en NutriGO, se estableció un tablero de control cuantitativo estándar:
1. **Conversion Rate (CR):** Monitoreo analítico por fases del embudo para medir la efectividad del módulo de prueba social (US-01).
2. **Cart Abandonment Rate:** Métrica de control del checkout para validar la reducción de fricción tras el despliegue del proceso *One-Step* (US-02).
3. **Customer Support SLA:** Acuerdo de nivel de servicio mandatorio fijado en menos de 2 minutos para respuestas automatizadas transaccionales.
4. **Net Promoter Score (NPS):** Indicador periódico de lealtad estructural e impacto relacional post-compra.

---

### 6. Post-Mortem del Proceso Analítico: Línea de Tiempo e Impacto
Alineado con las mejores prácticas de la cultura de post-mortem de Google SRE, este análisis retrospectivo se centró de forma estricta en evaluar el diseño del sistema y los flujos de información, eliminando cualquier búsqueda de culpabilidad individual para potenciar el aprendizaje técnico colectivo.

#### Línea de Tiempo del Diagnóstico del Ecosistema:
* **Día 1 — 09:00:** Extracción de datos del embudo de ventas. Se detecta una caída inusual en la fase de consideración web.
* **Día 1 — 14:30:** Auditoría de la interfaz de la e-shop. Se constata la ausencia total de elementos de *Social Proof* o reseñas de usuarios activos.
* **Día 2 — 11:00:** Mapeo técnico del *customer journey*. Identificación de cuellos de botella críticos en el checkout debido a validaciones de datos manuales y redundantes.
* **Día 2 — 16:00:** Análisis de canales de atención. Se evidencia un retraso promedio superior a 4 horas en la resolución de consultas básicas de entrega por falta de herramientas automatizadas.
* **Día 3 — 10:00:** Consolidación de datos de satisfacción. El NPS y la retención muestran una correlación directa con la falta de un canal relacional post-compra.

<img width="1358" height="636" alt="screenshot-1782494772809" src="https://github.com/user-attachments/assets/ed9781fe-61dd-4f27-a7dd-f5f908860544" />


#### Impacto Identificado:
* Pérdida medible del porcentaje potencial de conversión en el checkout debido a la fricción operativa.
* Sobrecarga de atención manual en consultas básicas repetitivas sobre stock y logística.
* Reducción del Lifetime Value (LTV) por fallas de seguimiento relacional y falta de soporte ágil.

#### Causas Raíz:
1. **Falta de Infraestructura de Validación:** El sistema carecía de un módulo integrado para recopilar, validar y renderizar opiniones reales directamente en el catálogo de productos.
2. **Arquitectura Transaccional Compleja:** El flujo de checkout original heredaba estructuras rígidas de múltiples pasos con campos redundantes en lugar de un enfoque moderno centrado en la conversión.
3. **Inexistencia de Capa de Automatización Básica:** El soporte dependía en su totalidad de la intervención humana manual para dar respuesta a preguntas frecuentes de naturaleza transaccional.

---

### 7. Reflexión: Aplicación de Feedback Radicalmente Sincero (Modelo SCI)
El desarrollo de este análisis maduró gracias a la integración sistemática de feedback radicalmente sincero. Adoptar una mentalidad de crecimiento permitió procesar las observaciones del proyecto no como críticas personales, sino como valiosos activos de datos para iterar hacia la excelencia del producto.

El documento evolucionó a través de tres ciclos iterativos claros:
* **Iteración 1 a Iteración 2 (Foco en Causa Raíz):** Tras recibir feedback indicando que las fricciones listadas eran síntomas superficiales y visuales, se profundizaron los análisis estructurales para mapear las deficiencias de infraestructura subyacentes.
* **Iteración 2 a Iteración 3 (Estructura de Control):** Ante el señalamiento de que las sugerencias eran puramente cualitativas, se incorporaron KPIs comerciales duros, metas de conversión y acuerdos de nivel de servicio (SLAs) cuantitativos.
* **Iteración 3 a Versión Final (Hiperpersonalización):** Se ajustaron de forma milimétrica todas las soluciones técnicas propuestas para responder con exactitud al perfil real de la Buyer Persona (Sofía), garantizando aplicabilidad práctica en el nicho de bienestar.

Para consolidar esta competencia de comunicación, apliqué el modelo **SCI (Situación, Comportamiento, Impacto)** en el proceso colaborativo de revisión:
> *"Durante la revisión intermedia del backlog (Situación), cuando nos enfocamos en describir dolores visuales en vez de fallas sistémicas (Comportamiento), perdimos la capacidad de definir requerimientos de código precisos para desarrollo (Impacto). Por ende, propongo reformular las fricciones comerciales directamente en historias de usuario con criterios de aceptación claros para el equipo técnico (Acción Correctiva)."*

---

### 8. Aprendizajes Clave & Conclusiones
* **La Experiencia Integrada es la Clave Competitiva:** Un producto excepcional no sobrevive a un ecosistema digital que presente puntos de dolor críticos. El cambio transformacional requiere una visión holística donde cada interacción técnica esté al servicio de aliviar las fricciones humanas del usuario.
* **La Confianza requiere Evidencia:** La prueba social y la transparencia de datos no son adornos de diseño; constituyen pilares críticos del backend comercial para disparar la conversión autónoma.
* **Automatizar para Humanizar:** Delegar las tareas puramente transaccionales y repetitivas a flujos de automatización ágiles (FAQs, bots) libera el ancho de banda necesario para que el equipo humano aporte valor real en las estrategias relacionales de la comunidad.
* **La Comunicación Clara es una Competencia Técnica:** Traducir arquitecturas de información y métricas complejas en estructuras organizadas (*Contexto → Problema → Acciones → Impacto*) es indispensable para lograr la alineación fluida entre las áreas técnicas, operativas y ejecutivas de una organización.

---

## Paso 4 — Evidencia de control de versiones

### En Notion
Notion registra de manera nativa e inalterable el historial de actualizaciones de la página pública. El desarrollo de este documento refleja una secuencia lógica de evolución profesional estructurada en cinco hitos de edición:
* **Edición 1 — 14/06/2026:** Estructura inicial del documento de auditoría y mapeo básico del caso NutriGO.
* **Edición 2 — 17/06/2026:** Incorporación de la matriz profunda de fricciones críticas y desglose analítico de causas raíz.
* **Edición 3 — 20/06/2026:** Traducción de las soluciones CX al backlog de ingeniería mediante historias de usuario (User Stories).
* **Edición 4 — 23/06/2026:** Configuración del tablero de control con KPIs cuantitativos y métricas de SLA.
* **Edición 5 — 26/06/2026:** Revisión final de lenguaje técnico para audiencias diversas, unificación estructural y despliegue público web mediante *Share to web*.

> <img width="1358" height="636" alt="screenshot-1782495517807" src="https://github.com/user-attachments/assets/bff42e91-554b-47d7-8da5-73c4d0baaa34" />

### En GitHub
Para asegurar un versionado explícito que deje trazabilidad real de los commits y de las decisiones de producto del proyecto, el contenido del blog se gestiona en un repositorio público.

* **Repositorio:** [https://github.com/milenamelanovgg-ship-it/blog-tecnico-postmortem](https://github.com/milenamelanovgg-ship-it/blog-tecnico-postmortem)

Los commits que estructuran el control de versiones son:

| Commit | Descripción |
| :---: | :--- |
| **8f2a1b0** | docs: inicializar estructura base del readme y manifiesto del hub técnico |
| **3c9d4e1** | docs: agregar diagnóstico causa raíz y matriz de fricciones de nutrigo |
| **b5e6f2a** | feat: incorporar user stories (backlog) y métricas cuantitativas de control (kpis) |
| **fa7d3c9** | docs: añadir post-mortem detallado y sección de feedback radical sincero (sci) |
| **2e1b4d8** | style: refinamiento de formato markdown para lectura limpia y consistencia final |
