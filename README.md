# Enrique Julián Gracia López

**Desarrollador Full Stack Jr. | Next.js · React · TypeScript · Node.js · PostgreSQL**

Estudiante de Ingeniería en Tecnologías de la Información (Desarrollo y Gestión de Software) en la Universidad Tecnológica de Tehuacán. Busco prácticas profesionales o un puesto junior de medio tiempo o remoto, compatible con mis estudios.

📍 Chapulco, Puebla, México · 📧 quiquesin1@gmail.com

[Español](#español) · [English](#english)

---

## Español

### 👋 Sobre mí

Desarrollo aplicaciones web y móviles de punta a punta: interfaz, API, base de datos y despliegue. Actualmente construyo **Barber Digital**, una plataforma SaaS de reservas y pagos para barberías. Me enfoco en que lo que construyo sea seguro y confiable: autenticación con roles, validación de datos, pruebas automatizadas y lógica que evita errores reales, como vender más producto del que hay en inventario o perder centavos al calcular un total.

### 🛠️ Tecnologías

**Frontend**
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

**Móvil**
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Expo](https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white)

**Backend**
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socketdotio&logoColor=white)

**Bases de datos**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

**Seguridad, nube y herramientas**
![Auth0](https://img.shields.io/badge/Auth0-EB5424?style=for-the-badge&logo=auth0&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=for-the-badge&logo=stripe&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![AWS Rekognition](https://img.shields.io/badge/AWS_Rekognition-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white)

**Además:** Zod · seguridad por filas (RLS) y pruebas pgTAP · JWT, MFA/TOTP y control de acceso por roles · Helmet, CORS y rate limiting · Vitest y Supertest · Meilisearch · Scrum

### 🚀 Proyectos destacados

#### 💈 Barber Digital: SaaS de reservas y pagos para barberías *(repositorio privado, en desarrollo)*
- Cada barbería tiene su propio sitio con servicios y **reservas sin cuenta**; el cliente elige pagar en el local o con tarjeta (**Stripe Connect**, en modo prueba).
- El dueño administra agenda, horarios, personal, productos con inventario y su mensualidad, protegido con **verificación en dos pasos (TOTP)**.
- **PostgreSQL en Supabase** con 50 migraciones, **seguridad por filas (RLS)** y 45 suites de pruebas pgTAP.
- Monorepo con contratos **Zod** compartidos, CI en **GitHub Actions**, detector de secretos antes de cada commit, despliegue en **Vercel** y tareas programadas con **Cloudflare Cron**.
- Más de 230 commits y 100 pull requests, con decisiones de arquitectura documentadas (ADR).
- *Next.js 16 · React 19 · TypeScript · Supabase · PostgreSQL · Stripe · Zod · Vitest · Vercel*

#### 🛍️ [Backend-Yolik](https://github.com/EJ-Zaskier/Backend-Yolik): API para tienda en línea de ropa tradicional
- Autenticación con **Auth0** (tokens RS256) y **control de acceso por roles**; límite de peticiones separado por área (auth, carrito, pedidos, admin).
- Carrito, pedidos, catálogo público y **dashboard de administración**.
- Arquitectura de pagos preparada para conectar **Stripe, Mercado Pago o PayPal**, activable con un *feature flag*.
- Montos calculados en **centavos** y precio guardado en cada pedido, para que los totales no cambien si después cambia el catálogo.
- Pruebas automatizadas por módulo (pedidos, pagos, seguridad) y **Dockerfile** para desplegar.
- *Node.js · Express · MongoDB · Auth0 · Docker*

#### 🛒 [Mini e-commerce full stack](https://github.com/EJ-Zaskier/Mini-proyecto-e-comerce)
- Catálogo público; el inicio de sesión se pide solo al agregar al carrito o comprar.
- Inventario por talla con **descuento de stock atómico** para evitar sobreventa cuando dos personas compran al mismo tiempo.
- Panel de administración: productos, roles, historial de sesiones y **bitácora de auditoría**.
- Seguridad basada en **OWASP**: validación estricta, JWT con expiración, roles verificados en el backend y errores que no exponen detalles internos.
- *React · Vite · Vitest · Node.js · Express · MongoDB*

#### 📱 [AsistenciaApp](https://github.com/EJ-Zaskier/AsistenciaApp): asistencias con reconocimiento facial
- App móvil que registra asistencias identificando a la persona con **AWS Rekognition**.
- Reportes exportables a Excel y PDF, y gráficas que se actualizan en tiempo real con Socket.io.
- *React Native · Expo · TypeScript · AWS Rekognition · Socket.io*

**Otros:** [Gestión de inscripciones y pagos](https://github.com/EJ-Zaskier/Gestion-de-Inscripciones-Pagos--Frontend) (Angular 19) · [Buscador con Meilisearch](https://github.com/EJ-Zaskier/Meilisearch-Activity-Ej-Enrique-Julian) (React) · [Tareas-EJGL](https://github.com/EJ-Zaskier/Tareas-EJGL) (Angular)

### 💼 Experiencia

**Face Guard — Desarrollador de software** · UTT San Pablo Tepetzingo · ene 2025 – abr 2025
- Asumí el desarrollo completo de la app móvil ante la falta de personal, aumentando la eficiencia del software en un 30%.
- Implementé y optimicé las funciones de seguridad del sistema.
- Coordiné entregas y pruebas funcionales con el equipo.
- *React Native, Expo, TypeScript, AWS Rekognition, Socket.io*

**Codex — Desarrollador web y de bases de datos** · UTT San Pablo Tepetzingo · may 2024 – ago 2024
- Diseñé e implementé el sistema de autenticación y la página de inicio de la plataforma.
- Optimicé la base de datos y las consultas, reduciendo el tiempo de respuesta en un 20%.
- Rediseñé partes de la interfaz para hacerla más clara para los usuarios.
- *JavaScript, Node.js, Express, MongoDB, MySQL*

### 🎓 Educación

- **Ingeniería en Tecnologías de la Información** (Desarrollo y Gestión de Software) — Universidad Tecnológica de Tehuacán · 2025 – 2027 (en curso)
- **TSU en Tecnologías de la Información** (Desarrollo de Software Multiplataforma) — Universidad Tecnológica de Tehuacán · 2023 – 2025
- **Técnico en Programación** — CBTIS 229 · 2020 – 2023

### 🌍 Idiomas

Español: nativo · Inglés: básico (en estudio)

### 📬 Contacto

📧 quiquesin1@gmail.com · 💻 [github.com/EJ-Zaskier](https://github.com/EJ-Zaskier)

---

## English

### 👋 About me

Junior Full Stack Developer and IT Engineering student at Universidad Tecnológica de Tehuacán (Mexico). I build web and mobile apps end to end; I'm currently building **Barber Digital**, a booking and payments SaaS for barbershops. I focus on security and reliability: role-based auth, input validation, automated tests, and logic that prevents real-world bugs such as overselling stock or rounding errors in totals. I'm looking for an internship or a part-time / remote junior role.

**Stack:** Next.js, React, React Native (Expo), TypeScript, Angular, Node.js, Express, PostgreSQL (Supabase), MongoDB, MySQL, Stripe, Auth0, AWS Rekognition, Docker, Vercel, GitHub Actions, Vitest/Jest, Git.

### 🚀 Featured projects

- **Barber Digital** *(private repo, in development)*: multi-tenant booking and payments SaaS for barbershops. Guest booking, pay at the shop or by card (Stripe Connect, test mode), owner dashboard with TOTP two-factor auth, PostgreSQL on Supabase with row-level security, 50 migrations and pgTAP tests, CI on GitHub Actions, deployed on Vercel.
- **[Backend-Yolik](https://github.com/EJ-Zaskier/Backend-Yolik)**: e-commerce REST API with Auth0 (RS256) and role-based access control, cart, orders, admin dashboard, a payment-provider layer ready for Stripe / Mercado Pago / PayPal, cent-based money math, automated tests and a Dockerfile.
- **[Mini e-commerce](https://github.com/EJ-Zaskier/Mini-proyecto-e-comerce)**: full stack store (React + Node.js + MongoDB) with per-size inventory, atomic stock updates to prevent overselling, admin panel with audit logs, and OWASP-oriented security.
- **[AsistenciaApp](https://github.com/EJ-Zaskier/AsistenciaApp)**: mobile attendance app with facial recognition (AWS Rekognition), Excel/PDF reports and real-time charts.

### 💼 Experience

- **Face Guard, Software Developer** (Jan–Apr 2025): took over full development of the mobile app; increased software efficiency by 30%.
- **Codex, Web & Database Developer** (May–Aug 2024): built the authentication system and landing page; cut response time by 20% through database and query optimization.

📧 quiquesin1@gmail.com
