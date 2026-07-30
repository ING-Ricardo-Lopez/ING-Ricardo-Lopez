<p align="center">
  <img src="assets/banner.svg" alt="Ricardo Lopez banner" width="100%">
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=15&duration=2800&pause=800&color=00F0FF&center=true&vCenter=true&width=520&lines=Ingeniero+de+Software;Pentester+Ofensivo;Builder+de+Decepticon;Orquestador+de+Agentes+IA" alt="Typing SVG">
</p>

<p align="center">
  <a href="mailto:rl0051844@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/ricardo-lopez-espinoza-829966257/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="http://wa.me/+526692218002"><img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white"></a>
  <a href="https://github.com/ING-Ricardo-Lopez"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"></a>
</p>

<p align="center"><sub>Mazatlán, Sinaloa, México 🇲🇽</sub></p>

---

> **2 años como Ingeniero de Software full-stack en producción + 6 de freelance.** Me muevo entre **producto empresarial**, **ciberseguridad ofensiva** y **orquestación de agentes de IA**. Fundamentos antes que frameworks. La IA es un acelerador — yo dirijo, ella ejecuta.

### Arsenal

<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,js,go,python,php,cs,nextjs,react,vue,nestjs,tailwind,docker,postgres,graphql&theme=dark&perline=14" alt="tech stack">
</p>

<img src="assets/divider.svg" width="100%">

## 🏭 Producto full-stack empresarial

Sistemas de producción completos — no demos. **NestJS + Prisma + PostgreSQL** en backend, **Next.js / React 19** en frontend, desplegados en producción.

| Proyecto | Dominio | Stack | Lo que lleva dentro |
|---|---|---|---|
| **Auriquim** (ERP) | Industria química / jabones | Monorepo pnpm (admin + PWA + POS + driver), `@auriquim/shared`, Dokploy | Finanzas (facturas globales, notas de crédito, CxC/CxP), inventario dual, precios especiales, comodato de cliente, órdenes de compra, RBAC granular por rol |
| **Hersa** (Inmobiliaria) | Bienes raíces | 4 apps (web/admin/CRM/portal), NestJS 11, 47 modelos Prisma | Ventas, cotización, amortización, reservaciones, comisiones, CFDI, CRM de asesor, ledger. Multi-tenant. Fuzz harness + DTO/schema checker propios |
| **Hello Sushi** (Cadena restaurante) | Food multi-sucursal | hs-platform-api + admin, Next.js, MapLibre | CEDIS, inventario, solicitudes de compra, recepción de mercancía, POS, dispatch con mapa, variantes/modificadores. Roles cedis_operator/manager |
| **ERP de fundición** | Industria metalúrgica (aluminio) | NestJS + Prisma | Foundry orders, fusion calendar con drag & drop, hornos (furnaces), stock reservation polimórfico, aleaciones/recetas (AlSi9Cu3), kiosko, sales orders |
| **TherapIQ** (SaaS salud) | Psicología / clínicas | Monorepo, TanStack Query + Zustand | 8 cambios SDD, 135 tareas, 220+ tests. Admin, integración IA con circuit breaker, auth, notificaciones, import CSV, planes de tratamiento, multi-tenant por clínica |

<img src="assets/divider.svg" width="100%">

## 🎯 Decepticon — framework de pentesting autónomo

Mi proyecto más grande. Un **framework de pentesting basado en LLMs** que orquesta la kill-chain completa —de reconocimiento a reporte— sobre **LangGraph/LangChain**, con agentes especializados por dominio ofensivo.

**11 agentes / grafos:**

| Dominio ofensivo | Agente |
|---|---|
| Kill-chain completa (orquestador) | `decepticon` |
| Active Directory | `ad_operator` |
| OSINT | `osint_operator` |
| IoT / embedded | `iot_operator` |
| Sistemas de control industrial (ICS) | `ics_operator` |
| Red inalámbrica | `wireless_operator` |
| Dispositivos móviles | `mobile_operator` |
| Cadena de suministro (supply chain) | `supply_chain_operator` |
| Campañas de phishing | `phisher` |
| Forensia digital | `forensicator` |
| Blue team / defensa | `blue_cell` |

**Lo que lo diferencia del resto:**
- **Middleware de inteligencia** que hace razonar al agente de explotación como un pentester senior: detección de tech-stack → técnicas de ataque, inferencia de cadenas de exploit a partir de hallazgos acumulados, pensamiento lateral ante fallos.
- **Playbooks** por vertical (API security, auth attack…) para inyectar TTPs de forma uniforme.
- **Generación de reportes** profesional Markdown → **PDF / HTML / DOCX** (resumen ejecutivo + técnico), i18n ES/EN.
- **SDK propio**, **Rules of Engagement** con gates humanos en cada fase, **SARIF** de hallazgos y **benchmark** interno.

### 🔓 Engagements reales — objetivos autorizados

Decepticon probado en campo. Auditorías black-box con el framework + arsenal propio, reportes con severidad CVSS, pruebas de concepto y recomendaciones.

| Objetivo | Hallazgo destacado |
|---|---|
| **Puropollo** (plataforma de pedidos de comida) | **IDOR crítico** exponiendo datos de ~22,450 usuarios sin autenticación |
| **SIGROMEX** (ERP corporativo) | Bypass JWT cross-tenant → escalada a SuperAdmin + fuga de PII (14 vulnerabilidades) |
| **Tarjeta Amiga** (sistema de crédito) | 10 vulnerabilidades (3 críticas) detectadas pre-producción |
| **CBTIS 051 / DGETI** (sistema educativo gubernamental) | Auth bypass + SQLi + volcado de PII |
| **Hello Sushi** (cadena de restaurante) | Investigación de carding masivo vía procesador de pagos Clip |
| **Revista Espejo** (medio de periodismo) | Pentest post-intrusión, OSINT de staff, bypass de WPS Hide Login |

Más objetivos: routers IZZI / MegaCable, monitor mode en BCM4387 (Apple M1 Pro), y **5 máquinas de Hack The Box** comprometidas de forma autónoma como benchmark del framework.

<img src="assets/divider.svg" width="100%">

## 🤖 IA & agentes — tooling propio

| Proyecto | Qué hace |
|---|---|
| **Ecosistema NuevoViruz** | 7 repos de mi entorno de trabajo con agentes: runtime de coding agent, **memoria persistente que aprende tu estilo** (Go), AI code review que enforcea estilo personal, TUI dashboard (Go), CLI (Go), skills y **SDD con sub-agentes** |
| **OpenCode Mobile** | PWA para controlar el agente de código desde el celular (chat + terminal vía `opencode serve`) |
| **Sentinel** | Capa de inteligencia de contexto que **verifica que el código generado por IA realmente funcione**. 3 módulos (Verify · Context · Critic) integrados como MCP tools · TypeScript |
| **Orquestación diaria** | Flujos multi-agente (planificación → spec → implementación → revisión adversarial) sobre opencode + Gentle AI, con memoria persistente |

<img src="assets/divider.svg" width="100%">

## 🎮 Juegos y proyectos abiertos

| Proyecto | Qué es | Link |
|---|---|---|
| **JuegoTrazo** (office-brawler) | Fighting game 2D web multijugador estilo MK/Street Fighter, personajes basados en compañeros de oficina · Phaser + Colyseus + geckos.io | privado |
| **SignoSonoro** | Detección de audio → lenguaje de señas ⭐ 3 | [repo](https://github.com/ING-Ricardo-Lopez/SignoSonoro) |
| **PATO** | Plataforma de Análisis y Training, corrección de ejercicios en tiempo real con visión artificial ⭐ 2 | [repo](https://github.com/ING-Ricardo-Lopez/PATO) |
| **fisioparallevar-redesign** | Landing premium con animaciones scroll-driven para academia de estética | [repo](https://github.com/ING-Ricardo-Lopez/fisioparallevar-redesign) |
| **ERP / Gym Angalf** | Gestión de academia de kickboxing (alumnos, asistencias, mensualidades) · Vue + Laravel | privado |
| **KCA** | Automatizador de marketing digital con IA para academia · Python | privado |
| **QList** | Administración de listas mediante QR | [repo](https://github.com/ING-Ricardo-Lopez/QList) |
| **Calabozos Eternos** | Juego 2D (materia de desarrollo de videojuegos) · C# | privado |

<img src="assets/divider.svg" width="100%">

## 📊 Actividad

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=ING-Ricardo-Lopez&show_icons=true&hide_border=true&bg_color=0d1117&title_color=00f0ff&icon_color=39ff14&text_color=c9d1d9" alt="stats">
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ING-Ricardo-Lopez&layout=compact&hide_border=true&bg_color=0d1117&title_color=00f0ff&text_color=c9d1d9" alt="langs">
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=ING-Ricardo-Lopez&hide_border=true&background=0d1117&ring=00f0ff&fire=39ff14&currLabel=00f0ff&sideLabels=c9d1d9&dates=c9d1d9" alt="streak">
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=ING-Ricardo-Lopez&theme=darkhub&no-frame=true&margin-w=10&column=7" alt="trophy">
</p>

<img src="assets/divider.svg" width="100%">

## 🥋 Fuera del código

- 🥋 **Maestro de Kickboxing y Muay Thai.** Cinta negra 1er Dan, en proceso de avance a 2do Dan. La disciplina marcial es la misma que aplico al oficio: fundamentos, repetición, mejora constante.
- 🎸 **Rock, nu-metal, rap y electrónica.** Linkin Park, Metallica e Ice Cube en rotación permanente.
- 🎮 Videojuegos (LoL, Minecraft), series y tecnología.

---

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=12&duration=4500&color=39FF14&center=true&width=560&lines=%22La+IA+es+una+herramienta.+Nosotros+dirigimos%2C+ella+ejecuta.%22" alt="quote">
</p>
