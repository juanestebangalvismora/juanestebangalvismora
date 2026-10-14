<h1 align="center">Juan Esteban Galvis M.</h1>
<h3 align="center">Full Stack Developer · Health Tech · DevOps con agentes de IA · Pereira, Colombia 🇨🇴</h3>

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

Full Stack Developer con 5 años de experiencia construyendo y sosteniendo **sistemas críticos para el sector salud en Colombia**: historia clínica electrónica, imagenología DICOM/PACS, facturación electrónica ante la DIAN, costeo de servicios de salud, triage hospitalario y agentes de IA conectados a la operación real.

Desarrollador principal en **ZeroUno** desde 2021, casa de software colombiana que opera con clientes desde 2019. No solo escribo el código: levanto el proceso con el cliente, construyo por fases, despliego, administro la infraestructura y respondo cuando algo falla en producción.

Hoy trabajo con **desarrollo asistido por IA bajo control humano**. Agentes (Claude Code) proponen cambios en ramas aisladas, yo los reviso en un preview y nada llega a producción sin mi aprobación, un backup previo y una verificación posterior.

---

## 🚀 Lo que estoy construyendo ahora

### 🐉 Hydra: oficina remota con agentes de IA
> 2026 · Ubuntu VPS · Docker · Caddy · Node.js · Python · Telegram Bot API · Whisper · Claude Code · restic

Plataforma propia para operar todos mis proyectos de clientes desde el celular, con flujo de aprobación de punta a punta:

- **Voz → código → producción:** dicto un cambio por Siri o por nota de voz en Telegram. Whisper lo transcribe, un agente lo implementa en una rama aislada, abre el Pull Request y levanta un **preview protegido** para probarlo.
- **Un toque para publicar:** apruebo desde Telegram. El despliegue hace backup de código y base de datos, aplica migraciones con **doble confirmación**, verifica la salud del sitio y hace **rollback automático** si algo falla.
- **Entornos de prueba idénticos a producción** (PHP 7.4 / 8.2, MariaDB) en contenedores, con **datos sintéticos**. Los datos reales de pacientes y clientes nunca salen de producción.
- **Seguridad por diseño:** usuarios separados por rol, llaves SSH dedicadas, secretos fuera de git con permisos restringidos, escaneo de secretos (gitleaks) antes de cada PR y auditoría de cada comando por voz.
- **Resiliencia:** backup offsite cifrado e inmutable (restic + Object Lock) con prueba de restauración documentada.

`Linux` `Docker` `Caddy` `Node.js` `Python` `Telegram API` `Whisper` `Claude Code` `GitHub` `restic`

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

![React](https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-443E38?style=flat-square&logoColor=white)
![Astro](https://img.shields.io/badge/Astro-BC52EE?style=flat-square&logo=astro&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)
![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=flat-square&logo=greensock&logoColor=black)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white)

**Mobile**

![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)

**Databases**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=flat-square&logo=sqlite&logoColor=white)

**Health & Interoperability**

![DICOMweb](https://img.shields.io/badge/DICOMweb-0066CC?style=flat-square&logoColor=white)
![CIE-10 · RIPS · CUPS](https://img.shields.io/badge/CIE--10_·_RIPS_·_CUPS-2E7D32?style=flat-square&logoColor=white)
![DICOM](https://img.shields.io/badge/DICOM-0066CC?style=flat-square&logoColor=white)
![Orthanc](https://img.shields.io/badge/Orthanc_PACS-1A73E8?style=flat-square&logoColor=white)
![OHIF](https://img.shields.io/badge/OHIF_v3-2196F3?style=flat-square&logoColor=white)
![DIAN](https://img.shields.io/badge/DIAN_UBL_2.1-FFCD00?style=flat-square&logoColor=black)

**DevOps / Infra**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![nginx](https://img.shields.io/badge/nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Caddy](https://img.shields.io/badge/Caddy-1F88C0?style=flat-square&logo=caddy&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white)
![cPanel](https://img.shields.io/badge/cPanel-FF6C2C?style=flat-square&logo=cpanel&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS_S3-232F3E?style=flat-square&logo=amazonaws&logoColor=white)

**IA**

![Claude](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white)
![Whisper](https://img.shields.io/badge/Whisper-412991?style=flat-square&logo=openai&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram_Bots-26A5E4?style=flat-square&logo=telegram&logoColor=white)

---

## 🏥 Proyectos en Producción

### 🔬 Plataforma de Imagenología Médica y PACS
> Hospital de segundo nivel · 2025 · Python · Flask · React · TypeScript · Orthanc · OHIF v3 · Docker · AWS S3

- Recepción automática de estudios desde equipos de rayos X (FujiFilm CR, DigiEye DX) vía **DICOM C-STORE** → Orthanc → hook Lua → backend. Cero digitación manual.
- Visor diagnóstico **OHIF v3** en el navegador con zoom, ventana/nivel y mediciones; editor de informe y visor lado a lado en una sola pantalla.
- **Dictado por voz en español** para redacción de informes radiológicos.
- Flujo de firma: borrador → revisión → firma del radiólogo → **PDF generado automáticamente**.
- Panel de **dosis de radiación** extraído de metadatos DICOM (kVp, mAs, exposición) por estudio.
- Portal del paciente: acceso con número de teléfono + clave por WhatsApp/SMS o código QR.
- Watchdog que monitorea el endpoint de salud y reinicia el servicio automáticamente si falla.

`Python` `Flask` `React` `TypeScript` `DICOM` `Orthanc` `OHIF` `Docker` `AWS S3` `Twilio` `MySQL`

---

### 💰 SICOS: Costeo de Servicios de Salud (SaaS)
> IPS, ESE y EPS · 2025 · PHP · MySQL · SQLite · Multitenant

Startup propia. Reemplaza las hojas de cálculo con las que hospitales y EPS calculan cuánto les cuesta realmente cada servicio.

- Costeo por actividades: **recurso → actividad (CUPS) → servicio / cápita**, siguiendo la **Resolución 3280 del MINSALUD**.
- Autocompletado sobre un catálogo de **9.400 códigos CUPS**; costo por recurso humano (minuto/salario) e insumos.
- Recálculo automático al cambiar salarios o precios; comparación contra tarifa SOAT/contrato con indicador visual.
- Costos indirectos y margen configurables; exportación CSV por ruta de atención.
- **Multitenant** con superadmin, aislamiento por tenant en cada consulta y sentencias preparadas.
- Sin dependencias externas: pensado para hosting compartido cPanel, con migraciones idempotentes.

`PHP` `MySQL` `SQLite` `Multitenant` `cPanel`

---

### 🐾 VetApp: Gestión de Clínicas Veterinarias (SaaS)
> 2024–2026 · Laravel · React 19 · TypeScript · MariaDB · Multitenant + multisede

- Historia clínica con registro de vacunación, agenda multiprofesional, inventario por sede, punto de venta con caja y reportes.
- **Facturación electrónica DIAN por tenant**: cada empresa con su propio NIT, certificado y resolución de numeración; credenciales cifradas en la base de datos.
- Arquitectura **multitenant con multisede**: varias empresas en una sola instalación, cada una con sus sedes, usuarios e inventario aislados.
- API REST con **Laravel Sanctum** desacoplada del frontend **React 19 + Zustand**.
- Despliegue por voz con preview, aprobación y doble confirmación de migraciones (ver Hydra).

`Laravel` `Sanctum` `React 19` `TypeScript` `Zustand` `MariaDB` `DIAN`

---

### 🏨 Sistema de Gestión Clínica y HCE
> Varias IPS · en producción desde 2019, a mi cargo desde 2021 · PHP · MySQL · REST · Android

- Historia clínica electrónica con plantillas por especialidad; agenda con generación automática de horarios y festivos.
- **Núcleo de servicios compartido** (pacientes, consultas, citas, facturación, firmas) para múltiples sedes sin duplicar lógica de negocio.
- Módulo de hospitalización y resolución por EPS; consultas preparadas PDO en todo el acceso a datos.
- Aplicación Android con **modo geriátrico**: ronda por habitación en lugar de agenda por cita, funciona con conectividad intermitente.

`PHP` `MySQL` `REST` `Android` `Kotlin`

---

### 🧾 Facturación Electrónica ante la DIAN
> Sector salud · en producción desde 2020, a mi cargo desde 2021 · PHP · Laravel · XML/UBL 2.1

- Emisión, validación previa, notas crédito/débito y manejo de rechazos.
- Traducción de rechazos DIAN a diagnóstico legible para el operador.
- Reintentos automáticos y cola de contingencia.

`PHP` `Laravel` `XML/UBL` `MySQL`

---

### 🚨 Digiturno: Triage y Sistema de Turnos para Urgencias
> Varias IPS · 2022 · PHP · WebSockets · Docker · Android

- Priorización por criterio clínico, no por orden de llegada; **pantallas de llamado en tiempo real con audio**.
- Impresión de tickets en térmica Epson TM-T81; métricas de tiempo de espera por punto de atención.
- Dockerizado para despliegue repetible entre sedes.

`PHP` `WebSockets` `Docker` `Android` `MySQL`

---

### 🤖 Agentes de IA para Agendamiento Clínico
> 2025 · Node.js · LLM · WhatsApp API

- Agentes conversacionales que **escriben en el sistema real**: consultan disponibilidad y agendan sobre la agenda clínica real, no en un calendario aparte.
- Agendamiento, confirmación y reprogramación por WhatsApp.
- Escalamiento a humano cuando la certeza no es suficiente; registro auditable de cada conversación.

`Node.js` `LLM` `WhatsApp API`

---

## 🧪 Otros proyectos

- **Búsqueda de empleo automatizada:** sistema propio que recolecta y filtra ofertas según mi perfil.
- **COTA 47:** juego táctico de disparos por hordas, vista cenital, jugable en el celular. Construido por iteraciones y desplegado en Vercel.
- **Centro de mando 3D (Three.js):** visualización en tiempo real de mis proyectos como un planeta, donde cada ciudad es un proyecto y se ve la actividad de los agentes y los commits.

---

## 🌎 Idiomas

- **Español:** nativo.
- **Inglés:** lectura y escritura técnica intermedia; conversación básica, en práctica diaria.

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://streak-stats.demolab.com?user=juanestebangalvismora&theme=github-dark&hide_border=true&date_format=j%20M%5B%20Y%5D" height="150"/>
</p>

---

<p align="center">
  <i>Disponible de inmediato: remoto o presencial en Colombia</i>
</p>
