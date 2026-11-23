# Jaider Rendón · VOID

**Desarrollador Full Stack · React, Node & Odoo** — Risaralda, Colombia

Desarrollo y mantengo software en producción: una app web que genera PDFs en masa desde Excel, una app Android de telemetría GPS publicada en Google Play y módulos fiscales para Odoo (DIAN / RNDC). Trabajo con React, TypeScript, Node y Python, y administro mi propio VPS. Ahora mismo estoy aprendiendo Rust con servicios reales desplegados.

[![Portafolio](https://img.shields.io/badge/Portafolio-void--x--labs.com-e5a952?style=for-the-badge&labelColor=101014)](https://www.void-x-labs.com/portfolio/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-jaider--rendon-60a5fa?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=101014)](https://www.linkedin.com/in/jaider-rendon/)
[![Email](https://img.shields.io/badge/Email-jaiderrendon66@gmail.com-f87171?style=for-the-badge&logo=gmail&logoColor=white&labelColor=101014)](mailto:jaiderrendon66@gmail.com)

---

### Stack

**Uso a diario**

![React](https://img.shields.io/badge/React-101014?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-101014?style=flat-square&logo=typescript&logoColor=3178C6)
![Node.js](https://img.shields.io/badge/Node.js-101014?style=flat-square&logo=nodedotjs&logoColor=5FA04E)
![Python](https://img.shields.io/badge/Python-101014?style=flat-square&logo=python&logoColor=FFD43B)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-101014?style=flat-square&logo=postgresql&logoColor=60a5fa)
![Git](https://img.shields.io/badge/Git-101014?style=flat-square&logo=git&logoColor=F05032)
![Linux](https://img.shields.io/badge/Linux_/_VPS-101014?style=flat-square&logo=linux&logoColor=e5a952)
![Docker](https://img.shields.io/badge/Docker-101014?style=flat-square&logo=docker&logoColor=2496ED)

**He usado en producción**

![Odoo](https://img.shields.io/badge/Odoo_17_/_19-101014?style=flat-square&logo=odoo&logoColor=c084fc)
![NestJS](https://img.shields.io/badge/NestJS-101014?style=flat-square&logo=nestjs&logoColor=E0234E)
![Express](https://img.shields.io/badge/Express-101014?style=flat-square&logo=express&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-101014?style=flat-square&logo=redis&logoColor=FF4438)
![Supabase](https://img.shields.io/badge/Supabase-101014?style=flat-square&logo=supabase&logoColor=3ECF8E)
![Cloudflare R2](https://img.shields.io/badge/Cloudflare_R2-101014?style=flat-square&logo=cloudflare&logoColor=F38020)
![Kotlin](https://img.shields.io/badge/Kotlin-101014?style=flat-square&logo=kotlin&logoColor=7F52FF)
![.NET](https://img.shields.io/badge/C%23_/_.NET-101014?style=flat-square&logo=dotnet&logoColor=a855f7)

**Aprendiendo**

![Rust](https://img.shields.io/badge/Rust_(Axum_/_Tokio)-101014?style=flat-square&logo=rust&logoColor=f97316)

---

### Proyectos en producción

#### FastFill PDF · [fastfillpdf.void-x-labs.com](https://fastfillpdf.void-x-labs.com/)
SaaS para generar lotes de PDFs personalizados a partir de un Excel o CSV, mapeando campos sobre un lienzo visual en el navegador.
- Editor en **React + TypeScript** sobre **PDF.js**, con guías magnéticas y campos de texto/QR.
- Backend en **Rust (Axum + Tokio)** que inyecta los datos en el PDF original con `lopdf` y entrega el ZIP por streaming, sin escribir en disco. Llegó a ~480 PDF/s en pruebas de carga.
- **PostgreSQL (SQLx)**, almacenamiento en **Cloudflare R2**, cobro por créditos con Mercado Pago y métricas con Prometheus.

#### Road Wear · [Google Play](https://play.google.com/store/apps/details?id=com.roadwear.app)
App Android en **Kotlin**: velocímetro GPS y control preventivo de desgaste (llantas, aceite, frenos) según kilometraje.
- Tres modos de velocímetro, modo HUD nocturno y garaje con varios vehículos.
- Registro de rutas con OpenStreetMap y alertas de mantenimiento según el kilometraje de cada vehículo.

#### Scraper del precio del café · [argos_coffee_price_scraper](https://github.com/VOIDX66/argos_coffee_price_scrapper)
Construí mi primer servicio en **Rust + Redis**: extrae el boletín diario de la Federación Nacional de Cafeteros y lo sirve en <1 ms en el servidor desde caché.
- API HTTP con **Axum**, caché en **Redis** con protección contra peticiones concurrentes y límite de 30 s para limpiar la caché.
- Corre en mi VPS; se puede consultar en vivo desde el [portafolio](https://www.void-x-labs.com/portfolio/#work).

### Trabajo en empresa

#### Odoo 17 y 19 · PETI Soluciones Productivas (abr – oct 2026)
- Rediseñé seis plantillas PDF fiscales en QWeb (factura electrónica DIAN, notas crédito/débito, exportación, documento soporte) heredando la vista base.
- Programé en Python las reglas del módulo logístico (TMS) para clasificar manifiestos RNDC en seis modalidades.
- Construí un módulo que consulta seis portales estatales (RUNT, SIMIT, ADRES, etc.) y lo migré de Odoo 17 a 19.

> El código de este trabajo pertenece a la empresa y no es público.

### Otros repositorios

- [Lucy-Tejada-Back](https://github.com/VOIDX66/Lucy-Tejada-Back) — API REST en NestJS + TypeScript con PostgreSQL / Supabase.
- [cluster_almacenamiento](https://github.com/VOIDX66/cluster_almacenamiento) — CLI en Rust para crear y administrar un clúster de almacenamiento con GlusterFS.

---

### Actividad

<p align="center">
  <img height="165" src="https://github-readme-stats-fast.vercel.app/api?username=VOIDX66&show_icons=true&hide_border=true&bg_color=101014&title_color=e5a952&icon_color=e5a952&text_color=d4d4d8" alt="Estadísticas de GitHub" />
  <img height="165" src="https://github-readme-stats-fast.vercel.app/api/top-langs?username=VOIDX66&layout=compact&hide_border=true&bg_color=101014&title_color=e5a952&text_color=d4d4d8" alt="Lenguajes más usados" />
</p>

---

**Cómo trabajo:** principios SOLID, Clean Architecture y Scrum/Kanban. Uso herramientas de IA (Antigravity, OpenCode, modelos locales en LM Studio) como apoyo, y reviso cada cambio antes de desplegarlo.
