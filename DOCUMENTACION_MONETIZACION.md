# Lex House AI — Documentación Completa de Producto
### Portal de IA y Automatizaciones para Corredores de Propiedades en Chile

> **Versión:** 3.0 — Completa y definitiva  
> **Fecha:** Junio 2026 · **Empresa:** Lex House Intelligence Inc.  
> **Sitio web:** [www.lexhouse-ai.com](https://www.lexhouse-ai.com)  
> **Audiencia:** Nuevos usuarios, equipo de ventas, inversores, video explicativo

---

## Índice

1. [¿Qué es Lex House AI?](#1-qué-es-lex-house-ai)
2. [Stack Tecnológico y Seguridad](#2-stack-tecnológico-y-seguridad)
3. [Mapa Completo de Funcionalidades](#3-mapa-completo-de-funcionalidades)
4. [Módulos Detallados — Captación y Atención IA](#4-módulos-detallados--captación-y-atención-ia)
5. [Módulos Detallados — Publicación y Marketing](#5-módulos-detallados--publicación-y-marketing)
6. [Módulos Detallados — Inteligencia y Análisis](#6-módulos-detallados--inteligencia-y-análisis)
7. [Módulos Detallados — CRM y Gestión Comercial](#7-módulos-detallados--crm-y-gestión-comercial)
8. [Módulos Detallados — Propiedades y Marketplace](#8-módulos-detallados--propiedades-y-marketplace)
9. [Módulos Detallados — Seguridad y Documentos](#9-módulos-detallados--seguridad-y-documentos)
10. [Panel Administrativo](#10-panel-administrativo)
11. [Cuánto Tiempo Ahorra](#11-cuánto-tiempo-ahorra)
12. [KPIs y Métricas Clave](#12-kpis-y-métricas-clave)
13. [Retorno de Inversión (ROI)](#13-retorno-de-inversión-roi)
14. [Modelos de Precios](#14-modelos-de-precios)
15. [Beneficios vs. Alternativas](#15-beneficios-vs-alternativas)
16. [Casos de Uso Reales](#16-casos-de-uso-reales)
17. [Preguntas Frecuentes](#17-preguntas-frecuentes)

---

## 1. ¿Qué es Lex House AI?

**Lex House AI** es la primera plataforma SaaS chilena diseñada **exclusivamente para corredores de propiedades**. Reúne más de **20 funcionalidades de IA y automatización** organizadas en módulos para captar, calificar, gestionar y cerrar operaciones inmobiliarias — sin aumentar el equipo humano.

**Tu equipo IA 24/7:** agentes WhatsApp y voz, CRM inmobiliario, Cazador de leads, Contrato X-Ray, Valuación inteligente, Análisis de inversión, Publicador masivo a +12 portales, Reels & Stories IA, Bóveda Legal encriptada y mucho más.

### El problema que resuelve

| Sin Lex House AI | Con Lex House AI |
|---|---|
| Leads sin respuesta por horas o días | Respuesta automática en segundos, 24/7 |
| Publicar a mano en cada portal | 1 clic → +12 portales simultáneos |
| Contratos revisados sin asesoría legal | Análisis de contratos con IA en segundos |
| Sin datos reales de valoración | Valuación inteligente en tiempo real |
| Videos caros y tardíos | Reels para Instagram y TikTok en minutos |
| Leads fríos sin seguimiento | Reactivación automática por WhatsApp API oficial y email |
| CRM genérico desconectado del flujo | CRM inmobiliario integrado con IA y comunicación |
| Documentos guardados en carpetas caóticas | Bóveda Legal encriptada AES-256 por operación |
| Análisis de inversión manual y lento | Calculadora IA de retorno por propiedad |
| Marketing descoordinado entre agentes | Campañas Email + WhatsApp centralizadas |
| Sin visibilidad de tus operaciones | Torre de Control y dashboard en tiempo real |

---

## 2. Stack Tecnológico y Seguridad

### Tecnologías

| Tecnología | Función |
|---|---|
| **Supabase** | Base de datos PostgreSQL, autenticación, storage, edge functions y tiempo real |
| **OpenAI** | Motor de IA conversacional, análisis de contratos y redacción |
| **Google Gemini** | Análisis multimodal de imágenes y documentos |
| **Claude (Anthropic)** | Razonamiento legal avanzado y síntesis |
| **React + TypeScript** | Interfaz rápida, tipada y robusta |
| **Vite** | Build ultrarrápido y HMR en desarrollo |
| **Vercel** | Despliegue global con edge network y baja latencia |
| **Tailwind CSS + shadcn/ui** | Sistema de diseño consistente |
| **Framer Motion** | Animaciones fluidas de interfaz |

### Seguridad — Nivel Bancario

- **Cifrado AES-256-GCM** con autenticación integrada (authenticated encryption)
- **Derivación de clave PBKDF2** con 600,000 iteraciones (estándar OWASP 2025)
- **Arquitectura Zero-Knowledge:** los archivos se cifran en el **navegador del usuario** antes de enviarse al servidor — ni Lex House AI puede leerlos
- **Row Level Security (RLS)** en Supabase: cada corredor accede solo a sus propios datos
- **security_invoker=on** en todas las vistas de base de datos
- **Auditoría automática de RLS** en módulos críticos (ej: Cazador de Leads)
- **Cumplimiento legal:** GDPR y Ley 19.628 de Chile (Protección de Datos Personales)
- **URLs de compartir optimizadas** para redes sociales (WhatsApp, Facebook, Twitter, LinkedIn)

---

## 3. Mapa Completo de Funcionalidades

### Módulos en la App (panel autenticado)

| Categoría | Módulo | Ruta | Badge |
|---|---|---|---|
| **Captación y Atención** | Agentes IA (WhatsApp + Voz) | `/app/ai-services` | PRO |
| **Captación y Atención** | Reactivación de Leads | `/app/cazador-leads` | NEW IA |
| **Publicación** | Publicador Masivo | `/app/publicador-masivo` | NEW IA |
| **Contenido** | Reels & Stories IA | `/app/reels` | NEW IA |
| **Marketing** | Marketing Enterprise | `/app/marketing-enterprise` | PRO |
| **Análisis** | Valuación Inteligente | `/app/valuacion-inteligente` | IA |
| **Análisis** | Análisis de Contrato (X-Ray) | `/app/contract-xray` | AI |
| **Análisis** | Análisis de Inversión | `/app/analisis-inversion` | AI |
| **CRM** | CRM Inmobiliario | `/app/mis-negocios` | PRO |
| **Propiedades** | Publicar Propiedad | `/app/publicar-propiedad` | — |
| **Propiedades** | Marketplace Interno | `/app/marketplace` | — |
| **Documentos** | Bóveda Legal | Dentro de cada propiedad | — |
| **Consultas** | Chat Legal IA | `/app/chat` | — |

### Panel Administrativo

| Módulo Admin | Ruta | Función |
|---|---|---|
| Torre de Control | `/admin/torre-control` | Dashboard central de toda la operación |
| Agenda de Visitas | `/admin/agenda-visitas` | Gestión de visitas programadas |
| Solicitudes de Arriendo | `/admin/solicitudes-arriendo` | Centralización de solicitudes |
| Ingresos | `/admin/ingresos` | Dashboard financiero |
| Super Admin | `/admin/super-admin` | Gestión de usuarios y suscripciones |

### Marketplace Público

| Sección | Ruta | Descripción |
|---|---|---|
| Marketplace Público | `/marketplace` | Portal público de propiedades indexado en Google |
| Ficha de Propiedad | `/p/:slug` | URL única y compartible por propiedad |
| Perfil de Corredor | Público | Perfil verificado con RUT, historial y reseñas |

---

## 4. Módulos Detallados — Captación y Atención IA

### 4.1 Agente WhatsApp IA 24/7

**Ruta:** `/app/ai-services`

**¿Qué hace?**
Atiende automáticamente todos los mensajes de WhatsApp. Responde consultas, califica prospectos, agenda visitas y crea el lead en el CRM — sin intervención humana, en español chileno natural.

**Flujo completo:**
1. Cliente envía mensaje por WhatsApp
2. Agente responde en segundos con información de la propiedad
3. Precalifica al lead (presupuesto, zona, urgencia, tipo)
4. Agenda visita en el calendario del corredor
5. Lead creado automáticamente en el CRM con todos los datos
6. Corredor recibe notificación con resumen

**Capacidades:**
- Respuesta 24/7 incluyendo noches, fines de semana y festivos
- Español chileno nativo (no genérico)
- Manejo de múltiples conversaciones en paralelo
- Historial de conversación guardado en el CRM
- Escalamiento inteligente: sabe cuándo derivar al humano

---

### 4.2 Agente de Voz IA Inbound — Calificación 24/7

**Ruta:** `/app/ai-services`  
**Costo por uso:** 2.5 UF / período

**¿Qué hace?**
Atiende llamadas telefónicas entrantes con voz humana realista. Está diseñado específicamente para **calificar a clientes que mostraron interés en el portal** — ya sea por una propiedad vista en el Marketplace, una consulta por WhatsApp o una solicitud de visita. Responde FAQs, agenda visitas directamente en el calendario y sincroniza con el CRM.

**Capacidades:**
- Voz humana realista en español chileno
- Calificación de interesados del portal: presupuesto, zona, urgencia, tipo de operación
- Manejo de objeciones frecuentes (precio, ubicación, disponibilidad)
- Sync automático con calendario del corredor
- Resumen de llamada + lead calificado creado automáticamente en el CRM
- Cero llamadas perdidas, incluso fuera del horario de oficina

**Ejemplo real:**
> Un comprador vio una propiedad en el Marketplace a las 22:00 y llama al número del corredor. El Agente de Voz responde, lo califica (presupuesto: $150M CLP, zona Providencia, listo para comprar en 60 días), agenda visita para el martes y envía un WhatsApp al corredor con el resumen completo.

---

### 4.3 Reactivación de Leads — WhatsApp API Oficial + Email

**Ruta:** `/app/cazador-leads`  
**Canal:** WhatsApp Business API oficial + Email marketing automatizado

**¿Qué hace?**
Reactiva automáticamente leads que mostraron interés en propiedades del portal pero no avanzaron en el proceso. Utiliza **WhatsApp API oficial** (no app personal, API empresarial verificada) y **secuencias de email** para reconectar con prospectos fríos y tibios — de forma personalizada y a escala.

**Flujo de reactivación:**
1. Identificación de leads inactivos según criterios: tiempo sin respuesta, etapa del pipeline, propiedad de interés
2. Segmentación automática por tipo de lead (interesado en venta, arriendo, zona, presupuesto)
3. Secuencia de mensajes personalizados vía WhatsApp API oficial
4. Secuencia paralela de emails de seguimiento con información de propiedades relevantes
5. Si el lead responde → entra automáticamente al CRM con etiqueta "reactivado"
6. Panel de control con métricas: enviados, abiertos, respondidos, convertidos

**Canales y capacidades:**
- **WhatsApp API oficial** (no WhatsApp Web personal — cumple políticas Meta para empresa)
  - Mensajes con templates aprobados por Meta
  - Posibilidad de enviar fichas de propiedades, links e imágenes directamente
  - Historial de conversación por lead
- **Email automatizado**
  - Secuencias de hasta N emails por lead
  - Personalización dinámica: nombre, propiedad de interés, zona, precio
  - Métricas de apertura, clicks y respuestas
  - Integración con los datos del CRM

**Panel de gestión:**
- Tablero visual con pipeline de reactivación
- Drag & drop entre etapas (Enviado / Abierto / Respondió / Agendó / Cerrado)
- Registro de cada interacción con timestamp
- Auditoría de seguridad RLS automática por usuario

**Resultado esperado:**
- 15–23% de leads fríos reactivados con visita o consulta activa
- 0 tiempo del corredor en seguimientos manuales repetitivos

---

## 5. Módulos Detallados — Publicación y Marketing

### 5.1 Publicar Propiedad (Asistente Paso a Paso)

**Ruta:** `/app/publicar-propiedad`

**¿Qué hace?**
Wizard guiado de múltiples pasos para publicar una propiedad completa en la plataforma, con toda la información necesaria para el marketplace y el publicador masivo.

**Información que captura:**
- Tipo de operación: venta o arriendo
- Tipo de propiedad: departamento, casa, oficina, local, terreno, etc.
- Ubicación con mapa integrado
- Características: dormitorios, baños, superficie, estacionamientos, bodega
- Precio en CLP o UF
- Fotos con galería tipo bento grid (formato editorial)
- Documentos legales (van a la Bóveda Legal cifrada)
- Descripción generada con asistencia IA

**Una vez publicada, la propiedad:**
- Aparece en el Marketplace público (indexada en Google)
- Tiene URL única compartible (`/p/:slug`) optimizada para WhatsApp, Facebook y Twitter
- Está lista para el Publicador Masivo a +12 portales
- Es visible en el Marketplace de búsqueda interno

---

### 5.2 Publicador Masivo a +12 Portales

**Ruta:** `/app/publicador-masivo`  
**Costo por uso:** 0.04 UF por publicación

**¿Qué hace?**
Publica una propiedad en más de 12 portales inmobiliarios chilenos simultáneamente con un solo clic. La IA optimiza automáticamente el título y la descripción para cada portal.

**Proceso:**
1. Seleccionar la propiedad (ya cargada en la plataforma)
2. Elegir los portales destino
3. Revisar las optimizaciones de IA (título y texto por portal)
4. Confirmar y publicar — todo en paralelo
5. Panel de estado de publicación por portal

**Impacto:**
- De 4–6 horas de publicación manual → 10–15 minutos
- Mayor exposición = más leads entrantes
- Texto optimizado para SEO en cada portal

---

### 5.3 Reels & Stories IA

**Ruta:** `/app/reels`

**¿Qué hace?**
Genera automáticamente videos verticales 9:16 con las fotos de tus propiedades, listos para Instagram Reels, TikTok y Stories. Sin editar, sin conocimientos técnicos.

**Proceso:**
1. Seleccionar propiedad de la plataforma
2. Elegir plantilla cinematográfica (varios estilos)
3. IA arma el reel: transiciones, música, overlays de precio, CTA
4. Descargar o publicar directamente desde la plataforma

**Impacto:**
- Videos profesionales en 10–15 minutos (vs. 3–4 horas o $80,000–$200,000 CLP con videógrafo)
- Consistencia visual en todas las propiedades
- Mayor alcance orgánico en redes sociales

---

### 5.4 Marketing Enterprise — Email + WhatsApp IA

**Ruta:** `/app/marketing-enterprise`  
**Costo por ejecución:** 0.04 UF

**¿Qué hace?**
Motor de marketing coordinado que fusiona campañas de email masivo con un agente IA de WhatsApp — en un solo flujo. Incluye dashboard con métricas en tiempo real.

**Funciones:**
- Campañas de email masivo segmentadas
- Integración simultánea de WhatsApp IA en la misma campaña
- Segmentación por zona, tipo de propiedad, etapa en el proceso, perfil de comprador
- Métricas en tiempo real: aperturas, clics, conversaciones iniciadas
- Visualizaciones de barras comparativas por período
- Análisis de subperíodos: días, semanas, meses
- Gestión de clientes para campañas de reactivación
- Integración con base de datos de WhatsApp business del corredor

---

## 6. Módulos Detallados — Inteligencia y Análisis

### 6.1 Valuación Inteligente

**Ruta:** `/app/valuacion-inteligente`

**¿Qué hace?**
Genera valuaciones profesionales de propiedades usando IA. Analiza datos de mercado, ubicación, características y comparables para entregar un rango de precio fundamentado.

**Capacidades:**
- Valoración en tiempo real basada en datos actualizados
- Análisis de comparables en la misma zona y tipología
- **Informe de valuación descargable en PDF** para presentar al mandante o cliente
- Historial de valuaciones realizadas (organizadas por propiedad y fecha)
- Argumentos objetivos para negociación (precio alto/bajo de mercado)
- Alertas de precio cuando el mercado cambia
- Alertas de precio cuando el mercado cambia

---

### 6.2 Contrato X-Ray — Análisis de Contrato IA

**Ruta:** `/app/contract-xray`  
**Costo por uso:** 0.04 UF por análisis  
**Vista:** Split de documento + chat IA (móvil con tabs: "doc" / chat)

**¿Qué hace?**
Analiza contratos inmobiliarios con IA multi-modelo (OpenAI + Claude). Detecta cláusulas problemáticas, riesgos legales y puntos de negociación — en segundos.

**Proceso:**
1. Subir el contrato (PDF o imagen)
2. La IA analiza el documento completo
3. Se marcan las cláusulas de riesgo con niveles de severidad
4. Chat interactivo: el usuario pregunta sobre cualquier punto
5. **Descarga del informe de análisis** con todas las cláusulas marcadas y observaciones
6. Historial de análisis guardado por operación

**Detecta:**
- Cláusulas abusivas o inusuales
- Condiciones de término anticipado y penalidades
- Garantías y cauciones
- Restricciones de uso o modificación
- Obligaciones ocultas del arrendatario o comprador
- Puntos con ambigüedad legal

**Importante:**
El Contrato X-Ray es una herramienta de apoyo, no reemplaza a un abogado. Para operaciones complejas, siempre recomendar asesoría profesional.

---

### 6.3 Análisis de Inversión

**Ruta:** `/app/analisis-inversion`  
**Costo por uso:** 0.04 UF por análisis

**¿Qué hace?**
Calcula el retorno de inversión de una propiedad usando IA. Ideal para presentar a compradores inversionistas o para evaluar propiedades en arriendo.

**Métricas que calcula:**
- Cap Rate (tasa de capitalización)
- Rentabilidad anual bruta y neta
- Flujo de caja mensual proyectado
- Período de recuperación de la inversión
- Valorización histórica de la zona
- Comparativa con alternativas de inversión (UF, mercado accionario)

**Historial y exportación:**
- Análisis guardados con fecha y propiedad
- **Informe descargable en PDF** listo para presentar al cliente inversionista
- Exportable para enviar por WhatsApp o email directamente desde la plataforma
- Dashboard de todos los análisis realizados

**Calculadora Integrada en cada Propiedad:**
El módulo `InvestmentCalculator` también aparece embebido en la ficha de cada propiedad del Marketplace, permitiendo al comprador calcular el retorno en el momento de interés.

---

### 6.4 Chat Legal IA

**Ruta:** `/app/chat`

**¿Qué hace?**
Asistente conversacional especializado en consultas legales inmobiliarias del mercado chileno. Responde preguntas sobre contratos, normativas, obligaciones y derechos en el contexto de compraventa y arrendamiento.

**Capacidades:**
- Historial de conversaciones guardado y navegable
- Respuestas con razonamiento legal contextualizado
- Soporte para texto y dictado por voz (Speech-to-Text integrado)
- Respuestas en español chileno con normativa local
- Indicador de escritura en tiempo real (TypingIndicator)

---

## 7. Módulos Detallados — CRM y Gestión Comercial

### 7.1 CRM Inmobiliario — Gestión de Negocios

**Ruta:** `/app/mis-negocios`

**¿Qué hace?**
Sistema de gestión comercial diseñado para el flujo inmobiliario chileno. Centraliza leads, propiedades, ofertas, visitas y tareas en un solo lugar — integrado con todos los módulos IA.

**Funciones incluidas:**

#### Tabla de Negocios
- Vista de todos los negocios activos por corredor
- Estado del negocio (prospecto → calificado → visita → oferta → cierre)
- Propiedades asociadas por negocio
- Historial de interacciones completo

#### Gestión de Ofertas
- Registro de ofertas formales recibidas por propiedad
- Estados de oferta con etiquetas visuales (pendiente, aceptada, rechazada, contra-oferta)
- Tabla de ofertas ordenadas por monto y fecha
- Integración con el flujo de oferta formal del Marketplace

#### Gestión de Tareas
- Tareas asociadas a cada negocio
- Creación, edición y eliminación de tareas
- Seguimiento de estado por tarea
- Vista filtrable por estado

#### Matching Inteligente Leads ↔ Propiedades

El CRM cruza automáticamente el perfil de preferencias de cada lead con las propiedades disponibles en el portal y genera un **porcentaje de compatibilidad** para cada par.

**¿Cómo funciona?**
- Al calificarse un lead, el sistema registra sus preferencias: zona, tipo de propiedad, presupuesto, dormitorios, condición (venta/arriendo)
- El motor de matching compara esas preferencias contra todas las propiedades activas en el portal
- Asigna un **% de compatibilidad** (ej: "87% match") para cada propiedad candidata
- El corredor ve un ranking ordenado de propiedades sugeridas para ese lead
- Puede enviar las fichas top directamente al lead desde el CRM con un click

**Beneficio directo:** El corredor deja de buscar manualmente qué propiedad mostrar a cada cliente — el sistema lo hace solo, con datos objetivos.

#### Plantillas de Mensajes
- Biblioteca de mensajes reutilizables
- Plantillas personalizables para WhatsApp y email
- Acceso rápido desde el CRM para enviar al cliente

---

### 7.2 Agenda de Visitas

**Ruta:** `/admin/agenda-visitas`

**¿Qué hace?**
Centraliza todas las solicitudes de visita a propiedades. Permite gestionar, confirmar, reagendar y cancelar visitas con notificaciones automáticas por email.

**Funciones:**
- Vista por pestañas (ej: pendientes, confirmadas, canceladas)
- Confirmación y cancelación de visitas
- Email automático al solicitante al confirmar o cancelar
- Si se cancela: email con enlace para reagendar desde la plataforma
- Historial completo de visitas por propiedad

---

### 7.3 Solicitudes de Arriendo

**Ruta:** `/admin/solicitudes-arriendo`

**¿Qué hace?**
Centraliza todas las solicitudes de arriendo recibidas a través del Marketplace Público. Permite gestionar el flujo de preselección de arrendatarios.

---

## 8. Módulos Detallados — Propiedades y Marketplace

### 8.1 Marketplace Público

**Ruta:** `/marketplace` (acceso público sin login)

**¿Qué hace?**
Portal público donde compradores y arrendatarios buscan propiedades publicadas por los corredores de la plataforma. Totalmente indexado en Google.

**Funcionalidades para compradores:**
- Búsqueda con filtros avanzados (zona, precio, tipo, dormitorios, baños, superficie)
- Toggle venta / arriendo
- Galería de propiedades con cards visuales (fotos, precio, características)
- Favoritos: guardar propiedades con corazón (requiere cuenta)
- Ver detalles básicos sin login; ubicación exacta, documentos y visitas requieren cuenta verificada

**Lo que ve el público de cada propiedad:**
- Fotos, precio, dirección general, características (dormitorios, baños, m²)
- Nombre y perfil del corredor responsable
- Botón para contactar o solicitar más información

---

### 8.2 Ficha Completa de Propiedad

**Ruta:** `/p/:slug` (URL única compartible)

**¿Qué hace?**
Página de detalle completa para cada propiedad, con URL optimizada para compartir en WhatsApp, Facebook y Twitter (Open Graph configurado).

**Secciones incluidas:**

#### Galería Bento Grid
- Visualización editorial de fotos en formato bento (estilo revista)
- Navegación de fotos con experiencia visual premium

#### Información y Precio
- Precio en CLP o UF según se haya configurado
- Tabla de características: dormitorios, baños, m², estacionamientos, bodega
- Descripción completa

#### Botones de Acción (para compradores con cuenta)
- **📅 Agendar Visita** — abre selector de fecha y hora → crea solicitud en el sistema
- **🛡️ Hacer Oferta Formal** — flujo de 2 pasos:
  - Paso 1: Datos del Comprador (nombre, RUT, email, teléfono, financiamiento)
  - Paso 2: Detalles Económicos (monto oferta, plazo, condiciones, reserva)
  - Oferta registrada en el CRM y notificada al corredor
- **📄 Generar Acuerdo de Compraventa** — una vez aceptada la oferta, el corredor puede generar el borrador del acuerdo de compraventa directamente desde la ficha de la propiedad:
  - Se completa automáticamente con los datos del comprador, vendedor y propiedad
  - Editable antes de finalizar
  - **Descargable en PDF** para firma entre las partes
  - Guardado en la Bóveda Legal cifrada asociada a esa propiedad

#### Calculadora de Inversión Embebida
- Calcula rentabilidad en el momento de ver la propiedad
- Ideal para compradores inversionistas
- No requiere salir de la ficha

#### Bóveda Legal (para el corredor)
- Documentos legales asociados a esa propiedad
- Cifrados con AES-256 (solo el corredor puede acceder)
- Gestión de escrituras, permisos, certificados

#### Propiedades Similares
- Carrusel de propiedades similares en zona y tipología
- Fomenta la navegación y reduce el abandono

---

## 9. Módulos Detallados — Seguridad y Documentos

### 9.1 Bóveda Legal Encriptada

**Disponible en:** Ficha de cada propiedad + Perfil del corredor

**¿Qué hace?**
Almacena documentos sensibles de cada operación con cifrado de nivel militar. Escrituras, contratos, certificados de dominio, informes de tasación — todo protegido.

**Arquitectura de seguridad:**
- **Zero-Knowledge:** los archivos se cifran en el navegador antes de subir al servidor
- **AES-256-GCM** con autenticación integrada
- **PBKDF2** con 600,000 iteraciones para derivar la clave
- Incluso si el servidor fuera comprometido, los documentos son ilegibles sin la clave del usuario
- Cumple **GDPR** y **Ley 19.628 de Chile** (Protección de Datos Personales)

**Tipos de documentos que acepta:**
- Escritura de compraventa
- Contrato de arriendo
- Certificado de dominio vigente
- Informe de tasación
- Permisos de edificación
- Recepción municipal
- Cualquier documento relevante a la operación

---

### 9.2 Perfil de Corredor con Verificación RUT

**Acceso:** Público (sin login requerido para ver)

**¿Qué hace?**
Perfil profesional verificado del corredor, visible desde cada propiedad que publica. Genera confianza desde el primer contacto.

**Incluye:**
- Nombre completo y foto profesional
- **Verificación de RUT** (validado en la plataforma)
- Número de propiedades cerradas
- Años de experiencia
- Reseñas reales de clientes anteriores
- Métricas de desempeño (propiedades activas, tiempo promedio de cierre)
- URL compartible del perfil

**Ejemplo:**
> Un cliente busca depto en Providencia, ve el listado y con 1 clic accede al perfil completo del corredor: 4 años de experiencia, 87 propiedades cerradas, RUT validado y reseñas reales. Contacta con confianza.

---

## 10. Panel Administrativo

### 10.1 Torre de Control

**Ruta:** `/admin/torre-control`  
**Acceso:** Solo administradores

**¿Qué hace?**
Dashboard central que muestra en tiempo real el estado de toda la operación: solicitudes de visita, ofertas recibidas, acciones pendientes.

**Secciones:**
- **Solicitudes de Visita:** todas las visitas solicitadas con estado, datos del solicitante y propiedad
- **Ofertas Recibidas:** todas las ofertas formales con estado (pendiente, aceptada, rechazada) y montos
- **Acciones:** confirmar/cancelar visitas con email automático al solicitante
- **Estado de email:** cuando se cancela una visita, se envía automáticamente email con enlace para reagendar

### 10.2 Dashboard de Ingresos

**Ruta:** `/admin/ingresos`

Visualización del flujo de ingresos por suscripciones, consumo de herramientas y transacciones de la plataforma.

### 10.3 Super Admin

**Ruta:** `/admin/super-admin`

Gestión completa de usuarios registrados, suscripciones activas, balances UF y configuración general de la plataforma.

---

## 11. Cuánto Tiempo Ahorra

### Tabla de Ahorro Semanal — Corredor Individual

| Tarea | Sin Lex House AI | Con Lex House AI | Ahorro/semana |
|---|---|---|---|
| Responder WhatsApp y llamadas entrantes | 5 h | 0 h (Agente IA) | **5 h** |
| Publicar propiedad en portales | 4 h | 15 min | **3.75 h** |
| Crear videos/reels para redes | 3 h | 15 min | **2.75 h** |
| Analizar contratos para clientes | 2 h | 15 min | **1.75 h** |
| Calificación manual de leads | 3 h | 0 h (IA) | **3 h** |
| Ingresar datos en CRM | 2 h | 0 h (automático) | **2 h** |
| Valorar propiedades para mandantes | 1.5 h | 20 min | **1.17 h** |
| Campañas email y WhatsApp | 2 h | 20 min | **1.67 h** |
| Análisis de inversión para clientes | 1 h | 10 min | **0.83 h** |
| Llamadas de seguimiento a leads fríos | 2 h | 0 h (Voz IA) | **2 h** |
| **TOTAL** | **25.5 h/semana** | **~1.6 h/semana** | **~24 h ahorradas** |

### En números concretos

```
Ahorro semanal:    ~24 horas
Ahorro mensual:    ~96 horas   → más de 2.5 semanas laborales completas
Ahorro anual:    ~1,152 horas  → 144 días laborales devueltos al corredor

Valor del tiempo (a $18,000 CLP/hora):
  Ahorro anual en tiempo: ~$20,736,000 CLP (~$22,000 USD)
```

---

## 12. KPIs y Métricas Clave

### KPIs de Captación y Respuesta

| KPI | Benchmark sin IA | Benchmark con Lex House AI |
|---|---|---|
| Tiempo de respuesta a lead (WhatsApp/llamada) | 15+ horas promedio | < 60 segundos |
| Leads atendidos en primeros 5 min | 10–15% | 100% |
| Probabilidad de conversión (respuesta < 5 min) | Base | **21x más alta** *(Harvard Business Review)* |
| Leads calificados vs. leads totales | 20–30% | 60–80% (IA filtra) |
| Tasa de agendamiento de visitas sobre leads | 8–10% | 18–25% |
| Leads reactivados (campañas de reactivación) | 0% (sin seguimiento) | 15–23% |

### KPIs de Publicación y Alcance

| KPI | Sin Lex House AI | Con Lex House AI |
|---|---|---|
| Portales donde aparece la propiedad | 1–3 | 12+ |
| Tiempo de publicación por propiedad | 3–5 horas | 10–15 minutos |
| Tiempo de creación de video de propiedad | 3–4 horas o $80,000–$200,000 CLP | 10–15 minutos, $0 adicional |
| Optimización de texto por portal | Manual/igual en todos | IA adapta por portal |
| Propiedades publicadas por mes | 3–5 | 10–15 |

### KPIs Comerciales y de Cierre

| KPI | Sin Lex House AI | Con Lex House AI |
|---|---|---|
| Leads mensuales captados | 15–20 | 50–80 |
| Visitas programadas por mes | 2–3 | 8–12 |
| Tasa de cierre visita → venta | 15–18% | 22–28% |
| Ventas cerradas por mes | 0.3–0.5 | 1.8–3.4 |
| Propiedades con análisis de inversión presentado | <10% | 100% (automático) |
| Clientes con análisis de contrato previo a firma | <20% | 100% (proactivo) |

### KPIs de Marketing

| KPI | Sin Lex House AI | Con Lex House AI |
|---|---|---|
| Tasa de apertura email (segmentado) | 10–15% | 25–40% |
| ROI email marketing | $5:$1 estimado | $36–42:$1 *(Mailerlite 2024)* |
| Emails automatizados vs. manuales | 0% | 100% |
| Ingreso adicional por emails automáticos | $0 | 320% más *(vs. envío manual)* |
| Campañas email + WhatsApp coordinadas | No disponible | Integrado |

### KPIs Operativos y de Eficiencia

| KPI | Sin Lex House AI | Con Lex House AI |
|---|---|---|
| Horas admin/semana | 25+ | 1–2 |
| Tareas repetitivas automatizadas | 0% | 85%+ |
| Consultas resueltas sin humano | 0% | 60–65% |
| Disponibilidad de atención | Lunes–Viernes 9am–7pm | 24/7/365 |
| Costo de atención por interacción | $3,000–$6,000 CLP (humano) | $250–$500 CLP (IA) |

### KPIs de Seguridad y Confianza

| KPI | Sin Lex House AI | Con Lex House AI |
|---|---|---|
| Documentos cifrados por operación | 0% | 100% (AES-256) |
| Corredores con perfil RUT verificado | Sin verificación | Verificación en plataforma |
| Visibilidad del historial del corredor | No | Sí (reseñas + métricas reales) |
| Cumplimiento Ley 19.628 | No gestionado | Integrado en arquitectura |

---

## 13. Retorno de Inversión (ROI)

### Escenario A: Corredor Individual — Plan Growth

| Métrica | Sin Lex House AI | Con Lex House AI |
|---|---|---|
| Leads captados y gestionados / mes | 15 | 60 |
| Visitas programadas / mes | 2 | 10 |
| Cierres / mes | 0.3 | 2.0 |
| Comisión promedio por cierre | $1,500,000 CLP | $1,500,000 CLP |
| Ingreso mensual por comisiones | ~$450,000 CLP | ~$3,000,000 CLP |
| **Diferencia mensual** | — | **+$2,550,000 CLP** |

> *ROI mensual = ingresos extra / inversión en la plataforma × 100*

**Payback:** el sistema se paga en las primeras horas del mes.

---

### Escenario B: Agencia con 5 Corredores — Plan Enterprise

| Métrica | Sin Lex House AI | Con Lex House AI |
|---|---|---|
| Leads manejados / mes total | 100 | 350 |
| Cierres mensuales totales | 2 | 8 |
| Ingresos por comisiones | $3,000,000 CLP | $12,000,000 CLP |
| Ahorro en personal administrativo | — | $600,000–$900,000 CLP/mes |
| **Beneficio neto adicional / mes** | — | **~$9,000,000–$9,900,000 CLP** |

---

### Comparativa: Lex House AI vs. Contratar Asistente

| Alternativa | Costo/mes | Horario | Capacidad |
|---|---|---|---|
| Asistente admin humano | $600,000–$900,000 CLP | L–V, 8h/día | 1 canal |
| Agente de ventas freelance | $1,000,000–$1,500,000 CLP | Variable | 1 canal |
| **Lex House AI (Plan Growth)** | **Precio del plan** | **24/7/365** | **Todos los canales simultáneos** |

---

### El dato más poderoso

> **Harvard Business Review:** responder un lead en los primeros 5 minutos aumenta **21 veces** la probabilidad de cerrar esa venta. El corredor promedio responde en **más de 15 horas**.
>
> **Lex House AI responde en segundos. Siempre.**

---

## 14. Modelos de Precios

### Estructura del Modelo

Lex House AI combina dos capas de precio:
1. **Suscripción mensual** por plan (acceso a módulos)
2. **Consumo por uso** en UF para herramientas IA específicas (solo pagas lo que usas)

### Precios de Herramientas IA por Uso (UF)

| Herramienta | Costo por uso |
|---|---|
| Publicador Masivo (+12 portales) | 0.04 UF por publicación |
| Contrato X-Ray (análisis de contrato) | 0.04 UF por análisis |
| Análisis de Inversión | 0.04 UF por análisis |
| Marketing Enterprise (ejecución de campaña) | 0.04 UF por ejecución |
| Agente de Voz IA Inbound (Recepción 24/7) | 2.5 UF por período |

> *Los precios en UF se actualizan automáticamente con el valor UF del día — sin sorpresas.*

### Planes de Suscripción

#### Plan Growth
**Para:** Corredores individuales y agencias pequeñas que quieren eliminar el cuello de botella administrativo

**Incluye:**
- ✅ Agente WhatsApp IA 24/7
- ✅ Precalificación Inteligente de Leads
- ✅ Agendamiento Automático de Visitas
- ✅ CRM Inmobiliario completo
- ✅ Publicar propiedades en la plataforma
- ✅ Marketplace Público con perfil de corredor
- ✅ Favoritos y compartir propiedades
- ✅ Soporte Técnico Especializado
- ✅ Herramientas IA por consumo (UF)
- ❌ Agente de Voz IA Inbound
- ❌ Agente de Voz IA Outbound

#### Plan Enterprise
**Para:** Agencias medianas y grandes corredoras — operación completa sin fricción

**Todo el Plan Growth más:**
- ✅ Agente de Voz IA Inbound (Calificación 24/7 de interesados del portal)
- ✅ Reactivación de Leads (WhatsApp API oficial + Email automatizado)
- ✅ Kanban de Pipeline de Reactivación
- ✅ Marketing Enterprise con dashboard avanzado
- ✅ Torre de Control y panel administrativo completo
- ✅ Super Admin (gestión de múltiples corredores)
- ✅ Todas las herramientas del AIMarketplace

> *Para precios exactos de suscripción visita [www.lexhouse-ai.com](https://www.lexhouse-ai.com)*

---

## 15. Beneficios vs. Alternativas

### Lex House AI vs. CRM Genérico

| Característica | CRM Genérico | Lex House AI |
|---|---|---|
| IA conversacional integrada | ❌ | ✅ WhatsApp + Voz |
| Publicador masivo (+12 portales) | ❌ | ✅ |
| Videos/Reels IA de propiedades | ❌ | ✅ |
| Análisis de contratos IA | ❌ | ✅ |
| Valuación inteligente | ❌ | ✅ |
| Análisis de inversión por propiedad | ❌ | ✅ |
| Bóveda Legal encriptada | ❌ | ✅ AES-256 Zero-Knowledge |
| Marketplace público propio | ❌ | ✅ Indexado en Google |
| Oferta formal desde el marketplace | ❌ | ✅ Flujo completo |
| Perfil con verificación RUT | ❌ | ✅ |
| Diseñado para Chile | ❌ | ✅ Ley 19.628, UF, portales locales |

### Lex House AI vs. Portal Inmobiliario Tradicional

| Característica | Portal Tradicional | Lex House AI |
|---|---|---|
| IA que atiende leads automáticamente | ❌ | ✅ |
| CRM integrado | ❌ | ✅ |
| Documentos legales cifrados | ❌ | ✅ |
| Análisis de inversión | ❌ | ✅ |
| Videos generados por IA | ❌ | ✅ |
| Campañas email + WhatsApp | ❌ | ✅ |
| Verificación de corredor | Parcial | ✅ RUT verificado |
| Reactivación automática de clientes | ❌ | ✅ |

---

## 16. Casos de Uso Reales

### Caso 1: El lead del domingo en la noche

**Escenario:** Compradora interesada llama a las 22:00 de un domingo sobre un depto en Las Condes.

**Sin Lex House AI:** Llamada perdida. El lunes el corredor devuelve el llamado. La compradora ya visitó 2 propiedades con otra corredora.

**Con Lex House AI:**
1. **22:00** — Agente de Voz Inbound responde la llamada con voz humana
2. Confirma disponibilidad del depto y responde consultas sobre precio y características
3. Agenda visita para el martes 10:00 en el calendario del corredor
4. WhatsApp automático al corredor: resumen de la llamada + datos de la compradora
5. Lead creado en el CRM con toda la información

**El lunes el corredor llega:** visita ya agendada, cliente calificada, datos completos.

---

### Caso 2: Publicar 10 propiedades nuevas

**Escenario:** Corredor firma mandatos de 10 propiedades en una semana.

**Sin Lex House AI:** 10 propiedades × 12 portales × 20 min = 40 horas de trabajo manual.

**Con Lex House AI:**
1. Sube cada propiedad al wizard de la plataforma (datos, fotos, documentos a la Bóveda)
2. La IA genera la descripción optimizada
3. Publicador Masivo publica en 12+ portales simultáneamente — 0.04 UF cada una
4. Módulo Reels & Stories genera un video por propiedad para Instagram/TikTok
5. Las propiedades aparecen en el Marketplace público indexado en Google

**Tiempo total:** ~2 horas (vs. 40 horas). Ahorro: 38 horas.

---

### Caso 3: Compradora inversionista analiza un departamento

**Escenario:** Compradora pregunta si el depto en Vitacura es buena inversión para arrendar.

**Sin Lex House AI:** El corredor no tiene herramienta de análisis. Dice "debería rentar bien" sin datos.

**Con Lex House AI:**
1. Abre la ficha de la propiedad → InvestmentCalculator embebido
2. En segundos: cap rate 5.8%, rentabilidad anual 6.2%, payback 16.2 años, flujo de caja $650,000 CLP/mes
3. Para análisis más profundo: módulo Análisis de Inversión genera informe completo (0.04 UF)
4. El corredor descarga el PDF y lo envía a la compradora en el mismo momento

**Resultado:** Compradora toma decisión fundamentada. Corredor se posiciona como asesor experto.

---

### Caso 4: Revisar un contrato antes de la firma

**Escenario:** Arrendatario quiere firmar mañana. El corredor detecta que el contrato tiene una cláusula de renovación automática con aumento del 15%.

**Sin Lex House AI:** El corredor no es abogado y firma sin detectar la cláusula.

**Con Lex House AI:**
1. Sube el contrato al módulo Contrato X-Ray (0.04 UF)
2. La IA marca en rojo la cláusula de renovación con aumento
3. El corredor pregunta: "¿qué significa esta cláusula para el arrendatario?"
4. La IA explica y propone texto alternativo para negociar
5. El corredor presenta esto al arrendatario como valor agregado

**Resultado:** Transacción más segura. Cliente fidelizado. Corredor diferenciado.

---

### Caso 5: Reactivar leads fríos de los últimos 3 meses

**Escenario:** La base tiene 120 leads que visitaron el portal hace más de 45 días y no compraron.

**Sin Lex House AI:** Se pierden. El corredor no tiene tiempo de llamar a 120 personas.

**Con Lex House AI:**
1. Marketing Enterprise segmenta los 120 leads por zona y tipo de propiedad
2. Campaña Email + WhatsApp IA automatizada (0.04 UF por ejecución)
3. WhatsApp IA presenta 3 propiedades nuevas relevantes para cada perfil
4. Los que responden entran en flujo de calificación automático
5. Los "calientes" van al Cazador de Leads (voz outbound) para cerrar visita

**Resultado:** 15–23% de leads reactivados se convierten en oportunidades activas. Ingresos de prospectos que parecían muertos.

---

## 17. Preguntas Frecuentes

**¿Lex House AI es solo para Chile?**
Sí. La plataforma está diseñada exclusivamente para el mercado chileno: español chileno nativo, precios en UF y CLP, portales chilenos integrados, Ley 19.628 de protección de datos, y flujos legales adaptados a la normativa local.

**¿El Agente IA habla exactamente como yo?**
No habla como tú, habla como un asistente profesional inmobiliario en español chileno natural. Puedes personalizar el nombre del agente y el tono general para alinearlo con tu marca personal.

**¿Necesito conocimientos técnicos para usar la plataforma?**
No. La plataforma está construida para corredores, no para programadores. El wizard de publicación, el CRM y los módulos IA son intuitivos y sin jerga técnica.

**¿Mis documentos en la Bóveda Legal están realmente seguros?**
Sí. Se cifran con AES-256-GCM en tu navegador antes de enviarse al servidor. Incluso si Lex House AI o el proveedor de hosting fuera comprometido, los archivos son ilegibles sin tu clave. Es arquitectura zero-knowledge.

**¿El Contrato X-Ray reemplaza a un abogado?**
No. Es una herramienta de apoyo para detectar riesgos y entender el contrato. Para operaciones complejas o dudas legales específicas, siempre recomendamos asesoría legal profesional.

**¿Qué pasa cuando el Agente IA no puede resolver una consulta?**
El agente escala automáticamente: te notifica en tiempo real y el cliente recibe confirmación de que será atendido pronto por un humano.

**¿El Publicador Masivo funciona con todos los portales del mercado chileno?**
Publica en +12 portales. La lista exacta está disponible en la plataforma y se actualiza con nuevas integraciones.

**¿Puedo ver las ofertas que recibo sin entrar al módulo de propiedades?**
Sí. La Torre de Control (admin) centraliza todas las ofertas recibidas con estado y monto, sin necesidad de revisar propiedad por propiedad.

**¿Los análisis de inversión son confiables?**
Se basan en datos de mercado actualizados y métricas estándar del sector inmobiliario (cap rate, rentabilidad bruta/neta, flujo de caja). Son una referencia sólida para la conversación con el cliente, pero no reemplazan la tasación formal.

**¿Se puede usar Lex House AI para propiedades en arriendo y también para ventas?**
Sí. La plataforma soporta ambas modalidades con flujos específicos para cada una: toggle venta/arriendo en el marketplace, análisis de inversión para arriendo, solicitudes de arriendo centralizadas.

---

## Apéndice — Fuentes y Respaldo Estadístico

| Dato | Fuente |
|---|---|
| Corredor promedio tarda 15+ horas en responder | Harvard Business Review |
| Responder en 5 min = 21x más conversión | Harvard Business Review |
| 300% más leads con IA | NextAutomation (2025) |
| 40% mejora en tasa de conversión | NextAutomation (2025) |
| 65% consultas resueltas sin humano | Crescendo AI (2026) |
| ROI email: $42 por $1 invertido | Mailerlite (2024) |
| Emails automáticos = 320% más ingresos | Mailerlite (2024) |
| 451% más leads con marketing automation | Mailerlite (2024) |
| Tasa de apertura real estate: 33.75% | Blastrow (2026) |
| 312% ROI automatización en 90 días | n8n.io Case Studies (2025) |
| 85% tareas repetitivas automatizadas | n8n.io Case Studies (2025) |
| Reducción 60% costos de atención con IA | Crescendo AI (2026) |

---

*Lex House Intelligence Inc.*  
*[www.lexhouse-ai.com](https://www.lexhouse-ai.com)*  
*Documento elaborado con análisis del código fuente del repositorio `automatizadorr/legal-advisor-ai` — Junio 2026*
