# 🚀 Macroproyecto: Organización y Valorización de Portafolio de Proyectos

> **Marco de trabajo sistemático para auditar, refactorizar, estructurar y divulgar un portafolio de proyectos de ingeniería, Inteligencia Artificial y automatización, transformando código e ideas en activos públicos de alta autoridad.**

---

## 📖 1. Descripción (Business Case y Motivación)

### ¿Cuál es el problema real?
A lo largo de años de trayectoria en ingeniería, desarrollo de software, automatización de procesos y modelos de Inteligencia Artificial, he acumulado múltiples proyectos técnicos de alto valor. Sin embargo, muchos de estos desarrollos permanecían en un estado de **dispersión cognitiva y técnica**:
* Repositorios locales incompletos o sin archivos `README.md` explicativos.
* Falta de documentación sobre la arquitectura, decisiones de diseño y lecciones aprendidas.
* Ausencia de un pipeline sistemático para comunicar públicamente el valor de negocio y el impacto técnico generado.

### ¿Cuál es la solución propuesta?
Crear este **Macroproyecto de Organización de Portafolio** bajo metodologías ágiles y minimalistas de gestión de proyectos (**OMIMO**, **P1.express**, **micro.P3.express** y principios **NUPP**). El macroproyecto funciona como un orquestador que procesa cada desarrollo a través de una **Definition of Done (DoD) de 3 Capas**:

```text
 ┌─────────────────────────────────────────────────────────────────┐
 │                   MACROPROYECTO DE PORTAFOLIO                    │
 └──────────────────────────────┬──────────────────────────────────┘
                                │
       ┌────────────────────────┼────────────────────────┐
       ▼                        ▼                        ▼
 ┌───────────┐            ┌───────────┐            ┌───────────┐
 │  CAPA 1   │            │  CAPA 2   │            │  CAPA 3   │
 │  NOTION   │ ─────────► │  GITHUB   │ ─────────► │ LINKEDIN  │
 │ (Interno) │            │ (Técnico) │            │ (Público) │
 └───────────┘            └───────────┘            └───────────┘
```

1. **Capa Interna (Notion):** Ficha técnica detallada, business case, arquitectura, roadmap, métricas y lecciones aprendidas.
2. **Capa Técnica (GitHub):** Refactorización de código, higiene de carpetas, trazabilidad de commits y `README.md` profesional.
3. **Capa de Divulgación (LinkedIn):** Plan de contenido estratégico (posts metodológicos, behind-the-scenes y casos de uso/empatía) con carruseles y guiones.

---

## 🛠️ 2. Requisitos e Inventario (Gobernanza y Metodología)

* **Orquestador Principal:** Notion (Hub de proyectos) + GitHub (Control de versiones y seguimiento) + LinkedIn (Canal de divulgación).
* **Marcos Metodológicos:**
  * **OMIMO / P1.express:** Gestión de proyectos orientada a la protección de la energía mental, ciclos diarios focalizados de 1 a 2 horas e implementación de *Postponing* (Postergación Activa).
  * **micro.P3.express:** Estructura de roles, revisión continua y colaboración por pares (*Peer Review*).
  * **NUPP (Nearly Universal Principles of Projects):**
    * *NUP1:* Preferir resultados y verdad (priorización por impacto e independencia de IP).
    * *NUP2:* Evitar desperdicio (gestión preventiva de riesgos de propiedad intelectual y datos sensibles).
* **Roles y Colaboración:**
  * **Daniel Peraza Blanco:** Coordinador y Creador principal.
  * **Colaboradores Externos / Peer Reviewers:**
    * **Luis:** Co-creador y revisor técnico para el proyecto *Asset Foundry*.
    * **Yenni:** Diseñadora gráfica y colaboradora en flujos de datos UX para el proyecto *IMIA*.

---

## 🗺️ 3. Roadmap de Ejecución y Matriz de Priorización

Alineados con **NUP1** y **NUP2**, los proyectos se priorizan según su madurez tecnológica, independencia de IP y potencial de autoridad inmediata:

### 🚀 Fase 1: Pipeline Inmediato

| Prioridad | Proyecto | Área Técnica | Estado | Peer Review | Capas de DoD |
| :---: | :--- | :--- | :---: | :---: | :---: |
| **01** | **Asset Foundry** | Editorial AI, n8n, LLM Workflows, Chatbots | En Progreso | Luis | Notion / GitHub / LinkedIn |
| **02** | **IMIA** | Prospección Inmobiliaria, ML, NLP | En Progreso | Yenni | Notion / GitHub / LinkedIn |
| **03** | **IA Generativa Local** | Dashboard Python/Streamlit, Stable Diffusion, SLMs | Completado | N/A | Notion / GitHub / LinkedIn |
| **04** | **Eloqua** | App Android, LLMs, TTS Adaptativo, Vocabulario | MVP Pausado | N/A | Notion / GitHub / LinkedIn |
| **05** | **Arcade Nouveau** | Plataforma Web Netlify, Vibe Coding, Prototipado | Completado | N/A | Notion / GitHub / LinkedIn |

### 🛑 Cola de Evaluación e IP Risk
* **Workflow Analista de Progreso BL:** Automatización con n8n y Gemma. *Estatus:* En pausa / Evaluación de anonimización mediante datos sintéticos (*dummy data*) para evitar vulneración de confidencialidad de la empresa.

### 📦 Fase 2: Expansión de Portafolio
* Desarrollos académicos, modelos 3D (Godot, Inventor, Onshape) y herramientas complementarias.

---

## ⚙️ 4. Estructura Estándar de las Fichas de Proyecto

Cada proyecto procesado dentro del macroproyecto adopta una estructura uniforme tanto en Notion como en GitHub:

```text
.
├── 1. DESCRIPCIÓN (Business Case y Motivación)
│   ├── Problema Real
│   ├── Solución Propuesta
│   └── Estado Actual
├── 2. REQUISITOS E INVENTARIO (Arquitectura Técnica)
│   ├── Orquestador y Tecnologías
│   └── Roles y Colaboración (micro.P3.express)
├── 3. ROADMAP DE DESARROLLO (Flujos de Trabajo Implementados)
├── 4. IMPACTO Y MÉTRICAS (Resultados en Producción)
├── 5. LECCIONES APRENDIDAS (Trazabilidad y Retrospectiva)
└── PLAN DE PUBLICACIONES PARA LINKEDIN
    ├── Post 1: El Gancho Metodológico
    ├── Post 2: El "Behind the Scenes" Técnico
    └── Post 3: Empatía y Aplicabilidad Real
```

---

## 📊 5. Métricas de Impacto y Control de Progreso

* **Tasa de Cobertura de Portafolio:** Medición del porcentaje de proyectos que han cumplido el DoD de 3 capas.
* **Ritmo de Producción (Velocity):** 1 proyecto completamente procesado y publicado cada 1-2 semanas.
* **Tiempo Dedicado:** Bloques enfáticos de 1 a 2 horas diarias (7 a 14 horas semanales).
* **Consistencia de Publicación:** Mínimo 2-3 publicaciones técnicas semanales en LinkedIn derivadas de las fichas del portafolio.

---

## 💡 6. Lecciones Aprendidas del Macroproyecto

1. **Gestión Preventiva de Propiedad Intelectual (NUP2):** Identificar anticipadamente si un proyecto contiene datos privados o código de terceros antes de iniciar la fase de refactorización pública. Abstraer arquitecturas con datos sintéticos si el valor metodológico lo justifica.
2. **Modularidad en la Documentación:** Separar la documentación interna (Notion) del repositorio público (GitHub) y del mensaje comercial/comunitario (LinkedIn) evita sobrecargar a las distintas audiencias.
3. **Control de Energía y Carga Mental (P1.express):** Limitar la jornada de arqueología de código a un máximo de 2 horas diarias mediante la postergación activa previene la fatiga y mantiene la cadencia a largo plazo.

---

## 📌 Enlaces y Accesos Rápidos

* **Hub de Conocimiento en Notion:** `[https://app.notion.com/p/Daniel-Arturo-Peraza-08e473145bf94fd6b5b61b220b610853?source=copy_link]`
* **Publicaciones en LinkedIn:** `[]`
* **Repositorio Principal:** `[]`

---

## 📄 Licencia y Créditos

Desarrollado y mantenido por **Daniel Peraza Blanco**.  
*Enfoque metodológico basado en OMIMO, P1.express, micro.P3.express y NUPP.*
