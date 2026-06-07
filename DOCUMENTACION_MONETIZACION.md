# Lex House AI — Documentación de Monetización
### Portal de IA y Automatizaciones para Corredores de Propiedades en Chile

> **Versión:** 2.0 · **Fecha:** Junio 2026 · **Empresa:** Lex House Intelligence Inc.  
> **Sitio web:** [www.lexhouse-ai.com](https://www.lexhouse-ai.com)  
> **Audiencia:** Nuevos usuarios, inversores, equipo de ventas

---

## Índice

1. [¿Qué es Lex House AI?](#1-qué-es-lex-house-ai)
2. [Stack Tecnológico](#2-stack-tecnológico)
3. [Los 12 Módulos IA](#3-los-12-módulos-ia)
4. [Cuánto Tiempo Ahorra](#4-cuánto-tiempo-ahorra)
5. [Retorno de Inversión (ROI)](#5-retorno-de-inversión-roi)
6. [Beneficios Clave](#6-beneficios-clave)
7. [Casos de Uso Reales](#7-casos-de-uso-reales)
8. [Modelos de Precios](#8-modelos-de-precios)
9. [Guión para Video Explicativo](#9-guión-para-video-explicativo)
10. [Preguntas Frecuentes (FAQ)](#10-preguntas-frecuentes-faq)

---

## 1. ¿Qué es Lex House AI?

**Lex House AI** es la primera plataforma SaaS chilena diseñada **exclusivamente para corredores de propiedades**. Reúne **12 módulos de IA y automatización** para captar, calificar, gestionar y cerrar operaciones inmobiliarias sin aumentar el equipo humano.

Es tu **equipo IA 24/7**: agentes WhatsApp y voz, CRM, Cazador de leads, Contratos IA y Publicador a más de 12 portales — todo en una sola plataforma.

### El problema que resuelve

| Sin Lex House AI | Con Lex House AI |
|---|---|
| Leads sin respuesta por horas (o días) | Respuesta automática en segundos, 24/7 |
| Publicar a mano en cada portal | Publicación masiva a +12 portales con 1 clic |
| Contratos revisados sin asesoría | Análisis IA de contratos al instante |
| Sin datos de valoración confiable | Valuación inteligente en tiempo real |
| Videos de propiedades caros y lentos | Reels y Stories IA listos en minutos |
| Leads perdidos sin seguimiento | Cazador de leads activo 24/7 |
| CRM separado del resto del flujo | CRM inmobiliario integrado con todo |
| Marketing difícil de medir | Dashboard Enterprise con métricas en tiempo real |

---

## 2. Stack Tecnológico

Lex House AI está construida sobre tecnologías de vanguardia que garantizan velocidad, seguridad y escala:

| Tecnología | Función en la plataforma |
|---|---|
| **Supabase** | Base de datos, autenticación, almacenamiento seguro y edge functions |
| **OpenAI** | Motor de IA conversacional y análisis de contratos |
| **Google Gemini** | Análisis multimodal de imágenes y documentos |
| **Claude (Anthropic)** | Redacción avanzada y razonamiento legal |
| **React + TypeScript** | Interfaz rápida y robusta |
| **Vercel** | Despliegue global con baja latencia |
| **AES-256-GCM** | Cifrado militar de archivos (cliente → servidor) |

**Seguridad:**
- Cifrado AES-256-GCM con PBKDF2 (600,000 iteraciones, estándar OWASP)
- Los archivos se cifran en el navegador **antes** de subirse al servidor
- Row Level Security (RLS) activo en Supabase — cada usuario accede solo a sus datos
- Políticas `security_invoker=on` en todas las vistas de base de datos

---

## 3. Los 12 Módulos IA

### Módulo 1 — Agente WhatsApp IA 24/7
**Ruta:** `/app/ai-services`  
**Badge:** PRO

**¿Qué hace?**
Responde automáticamente mensajes de WhatsApp las 24 horas. Atiende consultas, agenda visitas, califica leads y los crea en el CRM sin intervención humana.

**Beneficios clave:**
- Respuesta en segundos (vs. horas o días sin el agente)
- Español chileno natural, sin respuestas robóticas
- Lead creado automáticamente en el CRM tras cada conversación
- Agenda visitas directamente en tu calendario

**Escenario real:**
> Un domingo a las 22:00 alguien pregunta por un depto en Las Condes. LeyIA responde, confirma disponibilidad, agenda visita para el martes y te avisa al instante.

---

### Módulo 2 — Agente de Voz IA Inbound (Recepción 24/7)
**Ruta:** `/app/ai-services`  
**Precio:** 2.5 UF / mes  
**Badge:** PRO

**¿Qué hace?**
Atiende llamadas telefónicas entrantes con voz humana realista. Responde FAQs, agenda visitas automáticamente y sincroniza con tu calendario.

**Funciones incluidas:**
- Voz humana realista en español chileno
- Manejo de objeciones frecuentes
- Sync con calendario
- Resumen de la llamada + lead creado automático

**Impacto:**
- Cero llamadas perdidas, incluso fuera del horario laboral
- El 65% de consultas se resuelven sin intervención humana

---

### Módulo 3 — Agente de Voz IA Outbound — Cazador de Leads
**Ruta:** `/app/cazador-leads`  
**Badge:** ENTERPRISE

**¿Qué hace?**
Llama activamente a bases de prospectos, califica su intención de compra/arriendo y programa reuniones con los agentes solo para los leads "calientes".

**Funciones incluidas:**
- Llamadas outbound automatizadas
- Precalificación con preguntas inteligentes (presupuesto, zona, plazo)
- Escalamiento al agente solo cuando el lead está calificado
- Auditoría automática RLS para proteger datos de cada corredor

---

### Módulo 4 — Precalificación Inteligente de Leads
**Disponible en:** Growth + Enterprise

**¿Qué hace?**
Analiza automáticamente cada lead entrante y lo clasifica según su intención real de compra o arriendo, presupuesto estimado y urgencia.

**Beneficios:**
- Los agentes reciben solo leads realmente interesados
- Ahorra horas de conversaciones con prospectos sin intención real
- Datos enriquecidos en el CRM desde el primer contacto

---

### Módulo 5 — CRM Inmobiliario
**Ruta:** `/app/mis-negocios`  
**Badge:** PRO

**¿Qué hace?**
Sistema de gestión de negocios diseñado específicamente para el flujo inmobiliario chileno. Centraliza leads, propiedades, ofertas y visitas en un solo lugar.

**Funciones incluidas:**
- Tabla de ofertas por propiedad
- Gestión de tareas por negocio
- Historial completo de interacciones
- Agendamiento automático de visitas desde `/app/agenda-visitas`
- Solicitudes de arriendo centralizadas
- Integración total con todos los módulos IA

---

### Módulo 6 — Publicador Masivo a +12 Portales
**Ruta:** `/app/publicador-masivo`  
**Badge:** NEW IA

**¿Qué hace?**
Publica una propiedad simultáneamente en más de 12 portales inmobiliarios con un solo clic. Elimina el proceso manual de publicar una a una.

**Funciones incluidas:**
- Publicación simultánea en +12 portales
- Optimización automática de descripción y título por portal
- Sincronización de precios y disponibilidad
- Gestión centralizada de todas las publicaciones

**Impacto:**
- De 3-4 horas de publicación manual → 5 minutos con IA
- Mayor exposición = más leads entrantes

---

### Módulo 7 — Marketing Enterprise
**Ruta:** `/app/marketing-enterprise`  
**Badge:** PRO

**¿Qué hace?**
Motor de marketing digital completo con Email + WhatsApp IA en una sola campaña. Fusiona campañas de correo masivo con un agente IA de WhatsApp.

**Funciones incluidas:**
- Dashboard con métricas en tiempo real
- Campañas segmentadas por zona, tipo de propiedad, perfil de comprador
- Visualización por barras, fechas y comparativos
- Email marketing masivo integrado con seguimiento de apertura y clicks
- Fusión Email + WhatsApp en el mismo flujo de campaña

---

### Módulo 8 — Reels & Stories IA
**Ruta:** `/app/reels`  
**Badge:** NEW IA

**¿Qué hace?**
Genera automáticamente videos verticales 9:16 con tus propiedades, listos para Instagram y TikTok.

**Proceso:**
1. Seleccionas una propiedad
2. Eliges plantilla cinematográfica
3. La IA arma el reel con transiciones, música, overlays de precio y CTA
4. Descárgalo o publícalo directo desde la plataforma

**Impacto:**
- Videos profesionales en minutos (vs. horas con edición manual)
- Mayor engagement en redes sociales = más leads

---

### Módulo 9 — Valuación Inteligente
**Ruta:** `/app/valuacion-inteligente`

**¿Qué hace?**
Valúa propiedades en tiempo real usando datos de mercado, ubicación, características y transacciones comparables.

**Beneficios:**
- Argumentos objetivos para negociación con mandantes y compradores
- Datos actualizados del mercado chileno
- Informes de valoración exportables para presentar a clientes

---

### Módulo 10 — Contrato X-Ray (Análisis IA de Contratos)
**Ruta:** `/app/contractxray`

**¿Qué hace?**
Analiza contratos inmobiliarios con IA. Detecta cláusulas problemáticas, riesgos legales y puntos de negociación antes de firmar.

**Funciones incluidas:**
- Subida y análisis de contratos en segundos
- Detección de cláusulas riesgosas o inusuales
- Chat con el contrato: pregunta sobre cualquier punto y la IA responde
- Historial de análisis guardado por operación

---

### Módulo 11 — Perfil de Corredor con Verificación RUT
**Ruta:** Marketplace público

**¿Qué hace?**
Perfil público verificado que genera confianza en compradores y arrendatarios desde el primer contacto.

**Funciones incluidas:**
- Verificación de RUT
- Ficha completa por propiedad
- Historial de propiedades cerradas
- Reseñas y métricas reales de clientes
- Enlace compartible optimizado para WhatsApp, Facebook y Twitter

**Ejemplo real:**
> Un cliente busca depto en Providencia, encuentra tu listado y en 1 click ve tu perfil completo: 4 años de experiencia, 87 propiedades cerradas, RUT validado y reseñas reales. Te contacta con confianza.

---

### Módulo 12 — Torre de Control (Panel Administrativo)
**Ruta:** `/admin/torre-control`  
**Acceso:** Admin

**¿Qué hace?**
Panel central de monitoreo y gestión de toda la operación: ingresos, solicitudes de arriendo, agenda de visitas y supervisión de agentes.

**Secciones:**
- Dashboard de ingresos (`/admin/ingresos`)
- Agenda de visitas centralizada
- Solicitudes de arriendo
- Panel SuperAdmin para gestión de usuarios y suscripciones

---

## 4. Cuánto Tiempo Ahorra

### Cálculo por tarea semanal — Corredor Individual

| Tarea | Sin Lex House AI | Con Lex House AI | Ahorro |
|---|---|---|---|
| Responder consultas WhatsApp/llamadas | 4 h/semana | 0 h (Módulos 1-2) | **4 h** |
| Publicar propiedades en portales | 3 h/semana | 15 min (Módulo 6) | **2.75 h** |
| Crear videos/reels para redes | 3 h/semana | 20 min (Módulo 8) | **2.67 h** |
| Revisar y analizar contratos | 2 h/semana | 15 min (Módulo 10) | **1.75 h** |
| Calificación manual de leads | 3 h/semana | 0 h (Módulos 3-4) | **3 h** |
| Ingresar datos al CRM | 2 h/semana | 0 h (automático) | **2 h** |
| Campañas de email/WhatsApp | 2 h/semana | 30 min (Módulo 7) | **1.5 h** |
| Valorar propiedades para mandantes | 1.5 h/semana | 15 min (Módulo 9) | **1.25 h** |
| **TOTAL** | **20.5 h/semana** | **1.58 h/semana** | **~19 h ahorradas/semana** |

### En números concretos

```
Un corredor ahorra con Lex House AI:

  Por semana:    ~19 horas
  Por mes:       ~76 horas  →  casi 2 semanas laborales completas
  Por año:      ~912 horas  →  114 días laborales

Si el valor hora del corredor es $20,000 CLP/hora:
  Ahorro anual en tiempo:  ~$18,240,000 CLP (~$19,000 USD)
```

> Fuentes: NextAutomation (2025), Harvard Business Review, n8n case studies

---

## 5. Retorno de Inversión (ROI)

### Escenario: Corredor Individual — Plan Growth

**Inversión mensual en Lex House AI:** (precio del plan Growth)

| Métrica | Sin Lex House AI | Con Lex House AI | Diferencia |
|---|---|---|---|
| Leads captados/mes | 15 | 50+ | +233% |
| Leads atendidos a tiempo (<5 min) | 2 (13%) | 50 (100%) | +2,400% |
| Tasa conversión lead→visita | 8% | 20% | +150% |
| Visitas programadas/mes | 1–2 | 10 | +400% |
| Propiedades publicadas/mes | 3–4 | 10+ (en 12 portales) | +650% de exposición |
| Horas semanales en admin | 20 h | 1.5 h | -93% |

**ROI en comisiones:**

```
Sin Lex House AI:
  1–2 visitas/mes × 15% de cierre = 0.3 ventas/mes
  Comisión promedio: $1,500,000 CLP
  Ingreso mensual: ~$450,000 CLP

Con Lex House AI:
  10 visitas/mes × 25% de cierre = 2.5 ventas/mes
  Comisión promedio: $1,500,000 CLP
  Ingreso mensual: ~$3,750,000 CLP

Diferencia mensual:  +$3,300,000 CLP
```

> Fuentes: NextAutomation (2025), Artsmart AI (2025), Crescendo AI (2026)

---

### Comparativa: Lex House AI vs. Contratar Asistente

| Alternativa | Costo/mes | Horario | Capacidad |
|---|---|---|---|
| Asistente humano administrativo | $600,000–$900,000 CLP | 8h/día, L-V | 1 canal a la vez |
| **Lex House AI** | **Precio del plan** | **24h/día, 7 días** | **Todos los canales simultáneos** |

---

### Dato clave de la industria

> El corredor promedio tarda **más de 15 horas** en responder un lead. Un lead respondido en los primeros **5 minutos** tiene **21 veces más probabilidad** de convertirse en venta.  
> *(Harvard Business Review)*

Lex House AI responde en **segundos**, las 24 horas, incluyendo domingos y festivos.

---

## 6. Beneficios Clave

### Para el Corredor Individual

**Más tiempo en lo que importa**
- 19 horas semanales devueltas para captación, visitas y cierre
- La plataforma trabaja mientras duermes, en fines de semana y feriados
- Cero oportunidades perdidas por no contestar a tiempo

**Competir de igual a igual con grandes agencias**
- Acceso a la misma tecnología que empresas con presupuestos millonarios
- Imagen profesional validada (RUT, reseñas, historial real)
- Presencia en +12 portales sin esfuerzo extra

**Crecimiento sin contratar personal**
- De 15 leads mensuales a 50+ con la misma dedicación
- Automatización escala sin límite: 10 leads o 100, igual esfuerzo
- Sin costos de RRHH, AFP, licencias ni vacaciones

---

### Para la Agencia o Corredora

**Estandarización de la operación**
- Todos los agentes siguen el mismo proceso de calidad
- Trazabilidad completa: quién hizo qué, cuándo y con qué resultado
- Reportes automáticos para gerencia en tiempo real

**Reducción de costos operativos**
- Menos personal administrativo necesario
- Publicación centralizada en lugar de cada agente publicando por separado
- Marketing enterprise coordinado, no duplicado por agente

**Datos para decisiones**
- Dashboard de ingresos en tiempo real
- Métricas de rendimiento por agente
- Visualización de tendencias por zona, tipo y período

---

### Beneficios Diferenciales vs. Competencia

| Característica | Software CRM genérico | Portal inmobiliario clásico | **Lex House AI** |
|---|---|---|---|
| IA conversacional integrada | ❌ | ❌ | ✅ WhatsApp + Voz |
| Publicador masivo (+12 portales) | ❌ | Parcial | ✅ |
| Reels y videos IA | ❌ | ❌ | ✅ |
| Análisis de contratos IA | ❌ | ❌ | ✅ |
| Valuación inteligente | ❌ | ❌ | ✅ |
| Cazador de leads outbound | ❌ | ❌ | ✅ |
| Perfil con verificación RUT | ❌ | Parcial | ✅ |
| Cifrado AES-256-GCM | ❌ | ❌ | ✅ |
| Diseñado para Chile | ❌ | Parcial | ✅ Español chileno nativo |

---

## 7. Casos de Uso Reales

### Caso 1: El lead de domingo a las 10pm

**Escenario:** Un comprador llama un domingo a las 22:00 por un departamento en Las Condes.

**Sin Lex House AI:** Llamada perdida. El lunes el corredor llama de vuelta, pero el comprador ya visitó a otra corredora el sábado anterior.

**Con Lex House AI:**
1. El Agente de Voz Inbound responde la llamada en tiempo real
2. Confirma disponibilidad del departamento
3. Agenda visita para el martes en el calendario del corredor
4. Envía resumen al corredor por WhatsApp
5. Lead creado automáticamente en el CRM con todos los datos

**Resultado:** Visita programada mientras el corredor dormía.

---

### Caso 2: Publicar 8 propiedades nuevas

**Escenario:** Corredor tiene 8 propiedades nuevas para publicar.

**Sin Lex House AI:** 8 propiedades × 12 portales × 15 min c/u = 24 horas de trabajo.

**Con Lex House AI:**
1. Sube fotos y datos básicos a la plataforma
2. La IA optimiza descripción y título para cada portal
3. Publicador Masivo publica en los 12 portales simultáneamente
4. Perfil de corredor con RUT verificado aparece en cada listado

**Tiempo total:** 45 minutos (vs. 24 horas). **Ahorro: 23 horas y 15 minutos.**

---

### Caso 3: Revisar contrato antes de firmar

**Escenario:** Cliente quiere firmar contrato de arrendamiento mañana. El corredor no es abogado.

**Sin Lex House AI:** Pagar $80,000–$150,000 CLP por revisión de abogado, o firmar sin revisar (riesgo).

**Con Lex House AI:**
1. Sube el contrato al módulo Contrato X-Ray
2. La IA analiza en segundos y marca cláusulas problemáticas
3. El corredor puede chatear con el contrato: "¿Qué pasa si el arrendatario no paga?"
4. Entrega reporte al cliente con los puntos a negociar

**Resultado:** Transacción más segura, corredor diferenciado como asesor de confianza.

---

### Caso 4: Video para Instagram de una propiedad

**Escenario:** Corredor quiere publicar un reel de un penthouse en Vitacura.

**Sin Lex House AI:** Contratar videógrafo ($80,000–$200,000 CLP) o editar el video a mano (3–4 horas).

**Con Lex House AI:**
1. Selecciona la propiedad en el módulo Reels & Stories
2. Elige plantilla cinematográfica
3. La IA arma el reel con fotos, transiciones, música, overlay de precio y CTA
4. Descarga el video 9:16 listo para Instagram o TikTok

**Tiempo total:** 10–15 minutos. **Ahorro: 3–4 horas o $80,000–$200,000 CLP.**

---

## 8. Modelos de Precios

### Estructura de Planes

Lex House AI opera con un modelo de suscripción mensual más **consumo variable por herramientas IA** medido en **UF** (Unidades de Fomento), lo que hace que el costo escale con el uso real.

#### Plan Growth
**Para:** Corredores individuales y agencias pequeñas

**Incluye:**
- ✅ Agente WhatsApp IA 24/7
- ✅ Precalificación Inteligente de Leads
- ✅ Agendamiento Automático de Visitas
- ✅ CRM Inmobiliario
- ✅ Publicador Masivo (+12 portales)
- ✅ Soporte Técnico Especializado
- ❌ Agente de Voz IA Inbound
- ❌ Agente de Voz IA Outbound (Cazador)
- ❌ Herramientas Enterprise

#### Plan Enterprise
**Para:** Agencias medianas y grandes corredoras

**Incluye todo el Plan Growth más:**
- ✅ Agente de Voz IA Inbound (Recepción 24/7)
- ✅ Agente de Voz IA Outbound (Cazador de Leads)
- ✅ Marketing Enterprise con dashboard avanzado
- ✅ Torre de Control y panel administrativo
- ✅ Reels & Stories IA
- ✅ Todas las herramientas del marketplace IA
- ✅ Acceso completo a todos los módulos

### Herramientas por Consumo (UF)

Algunas herramientas se cobran por uso en UF adicionales al plan:
- **Recepción 24/7 (Voz Inbound):** 2.5 UF / período
- Otras herramientas del marketplace con precios individuales en UF

> *Nota: Los precios exactos de suscripción se encuentran en [www.lexhouse-ai.com](https://www.lexhouse-ai.com). Los valores en UF se actualizan automáticamente con la inflación.*

---

## 9. Guión para Video Explicativo

*(Ver archivo separado: `GUION_VIDEO_EXPLICATIVO.md`)*

---

## 10. Preguntas Frecuentes (FAQ)

**¿Lex House AI es solo para corredores en Chile?**
Sí. La plataforma está diseñada exclusivamente para el mercado chileno: español chileno nativo, precios en UF y CLP, portales chilenos integrados, y flujos legales adaptados a la normativa local.

**¿Necesito conocimientos técnicos para usar la plataforma?**
No. La plataforma está construida para corredores, no para programadores. La interfaz es intuitiva y el onboarding está asistido.

**¿El Agente WhatsApp habla igual que yo?**
No habla igual que tú, pero habla como un asistente profesional en español chileno natural. Puedes personalizar el nombre y el tono para que se alinee con tu marca personal.

**¿Mis datos y los de mis clientes están seguros?**
Sí. Los archivos se cifran con AES-256-GCM directamente en tu navegador antes de enviarse al servidor. Incluso si el almacenamiento fuera comprometido, los datos son ilegibles sin tu clave. Además, cada corredor accede solo a sus propios datos gracias a las políticas RLS de Supabase.

**¿El Publicador Masivo funciona con todos los portales del mercado?**
Publica en +12 portales. La lista exacta está disponible en la plataforma. Se agregan nuevos portales periódicamente.

**¿Puedo usar Contrato X-Ray para reemplazar a un abogado?**
No. Contrato X-Ray es una herramienta de apoyo para detectar riesgos y entender el contrato. Para operaciones complejas o dudas legales específicas, siempre recomendamos asesoría legal profesional.

**¿Qué pasa si el Agente de Voz no puede resolver una consulta?**
El agente escala automáticamente: te notifica en tiempo real y el cliente recibe confirmación de que pronto será atendido por un humano.

**¿Puedo probar la plataforma antes de suscribirme?**
Para información sobre período de prueba, visita [www.lexhouse-ai.com](https://www.lexhouse-ai.com) o contáctanos directamente.

---

## Fuentes y Respaldo Estadístico

- Harvard Business Review: *The Short Life of Online Sales Leads* — dato 5 min / 21x
- NextAutomation (2025): *AI Automation for Real Estate — 300% leads, 40% conversión*
- Artsmart AI (2025): *AI in Real Estate — 30+ Statistics*
- Crescendo AI (2026): *Conversational AI for Real Estate — 65% consultas sin humano*
- Mailerlite (2024): *Email Marketing ROI — $42 por $1 invertido*
- n8n.io Case Studies (2025): *312% ROI en 90 días*
- Morgan Stanley (2025): *AI in Real Estate: Innovations Reshaping the Sector*

---

*Documento preparado por Lex House Intelligence Inc.*  
*Sitio web: [www.lexhouse-ai.com](https://www.lexhouse-ai.com)*
