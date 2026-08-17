<h1 align="center">Juan Esteban Galvis M.</h1>
<h3 align="center">Full Stack Developer · Health Tech · Fundador ZeroUno · Pereira, Colombia 🇨🇴</h3>

<p align="center">
  <a href="mailto:juanestebangalvismora@gmail.com">
    <img src="https://img.shields.io/badge/juanestebangalvismora@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://linkedin.com/in/juan-esteban-galvis-mora-001aa7251" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
</p>

---

## About me

Full Stack Developer con 5 años de experiencia construyendo y sosteniendo **sistemas críticos para el sector salud en Colombia** — historia clínica electrónica, imagenología DICOM/PACS, facturación electrónica ante la DIAN, triage hospitalario y agentes de IA conectados a la operación real.

Fundador de **ZeroUno** (2018), casa de software colombiana. No solo escribo el código: levanto el proceso con el cliente, construyo en fases, despliego, administro la infraestructura y respondo cuando algo falla en producción.

---

## 🛠 Tech Stack

**Backend**

![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=c-sharp&logoColor=white)
![ASP.NET](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React_18-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![Astro](https://img.shields.io/badge/Astro-BC52EE?style=flat-square&logo=astro&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)
![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=flat-square&logo=greensock&logoColor=black)

**Mobile**

![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)

**Databases**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=flat-square&logo=sqlite&logoColor=white)

**Health & Interoperability**

![DICOM](https://img.shields.io/badge/DICOM-0066CC?style=flat-square&logoColor=white)
![Orthanc](https://img.shields.io/badge/Orthanc_PACS-1A73E8?style=flat-square&logoColor=white)
![OHIF](https://img.shields.io/badge/OHIF_v3-2196F3?style=flat-square&logoColor=white)

**DevOps / Infra**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![nginx](https://img.shields.io/badge/nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS_S3-232F3E?style=flat-square&logo=amazonaws&logoColor=white)

---

## 🏥 Proyectos en Producción

### 🔬 Plataforma de Imagenología Médica y PACS
> Hospital de segundo nivel · 2025 · Python · Flask · React · TypeScript · Orthanc · OHIF v3 · Docker · AWS S3

- Recepción automática de estudios desde equipos de rayos X (FujiFilm CR, DigiEye DX) vía **DICOM C-STORE** → Orthanc → hook Lua → backend. Cero digitación manual.
- Visor diagnóstico **OHIF v3** en el navegador con zoom, ventana/nivel y mediciones; editor de informe y visor lado a lado en una sola pantalla
- **Dictado por voz en español** para redacción de informes radiológicos
- Flujo de firma: borrador → revisión → firma del radiólogo → **PDF generado automáticamente**
- Panel de **dosis de radiación** extraído de metadatos DICOM (kVp, mAs, exposición) por estudio
- Portal del paciente: acceso con número de teléfono + clave por WhatsApp/SMS o código QR

`Python` `Flask` `React` `TypeScript` `DICOM` `Orthanc` `OHIF` `Docker` `AWS S3` `Twilio` `MySQL`

---

### 🏨 Sistema de Gestión Clínica y HCE
> Varias IPS · 2019 · PHP · MySQL · REST · Android

- Historia clínica electrónica con plantillas por especialidad; agenda con generación automática de horarios y festivos
- **Núcleo de servicios compartido** (pacientes, consultas, citas, facturación, firmas) para múltiples sedes sin duplicar lógica de negocio
- Módulo de hospitalización, resolución por EPS; consultas preparadas PDO en todo el acceso a datos
- Aplicación Android con **modo geriátrico** — ronda por habitación en lugar de agenda por cita, funciona con conectividad intermitente

`PHP` `MySQL` `REST` `Android` `Kotlin`

---

### 💰 Sistema de Costeo de Servicios de Salud
> IPS y ESE · 2025 · PHP · MySQL · SQLite · Multitenant

- Costeo por actividades siguiendo la **Resolución 3280 del MINSALUD**; reemplaza hojas de cálculo manuales
- Autocompletado sobre catálogo de **9.400 códigos CUPS**; costo por recurso humano (minuto/salario) e insumos
- Recalculo automático al cambiar salarios o precios; comparación contra tarifa SOAT/contrato con indicador visual
- **Multitenant** con superadmin — sin dependencias externas, pensado para hosting compartido cPanel

`PHP` `MySQL` `SQLite` `Multitenant`

---

### 🧾 Facturación Electrónica ante la DIAN
> Sector salud · 2020 · PHP · Laravel · XML/UBL

- Emisión, validación previa, notas crédito/débito y manejo de rechazos
- Traducción de rechazos DIAN a diagnóstico legible para el operador
- Reintentos automáticos y cola de contingencia

`PHP` `Laravel` `XML/UBL` `MySQL`

---

### 🚨 Triage y Sistema de Turnos para Urgencias
> Varias IPS · 2022 · PHP · WebSockets · Docker · Android

- Priorización por criterio clínico, no por orden de llegada; **pantallas de llamado en tiempo real con audio**
- Impresión de tickets en térmica Epson TM-T81; métricas de tiempo de espera por punto de atención
- Dockerizado para despliegue repetible entre sedes

`PHP` `WebSockets` `Docker` `Android` `MySQL`

---

### 🤖 Agentes de IA para Agendamiento Clínico
> 2025 · Node.js · LLM · WhatsApp API

- Agentes conversacionales que **escriben en el sistema real** — consultan disponibilidad y agendan sobre la agenda clínica real, no un calendario aparte
- Agendamiento, confirmación y reprogramación por WhatsApp
- Escalamiento a humano cuando la certeza no es suficiente; registro auditable de cada conversación

`Node.js` `LLM` `WhatsApp API`

---

### 🐾 VetApp — Gestión de Clínica Veterinaria
> 2024 · Node.js · React · PostgreSQL · Multi-tenant

- Historia clínica, agenda multi-profesional, inventario y facturación para clínicas veterinarias
- API desacoplada del frontend para escalar por partes

`Node.js` `React` `PostgreSQL` `Multi-tenant`

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://streak-stats.demolab.com?user=juanestebangalvismora&theme=github-dark&hide_border=true&date_format=j%20M%5B%20Y%5D" height="150"/>
</p>

---

<p align="center">
  <i>Disponible de inmediato — remoto o presencial en Colombia</i>
</p>
