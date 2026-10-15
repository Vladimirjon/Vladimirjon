<h1 align="center">Johann Pasquel</h1>

<p align="center"><strong>Computer Science Engineering student building reliable data systems</strong></p>

<p align="center">Python · SQL · PostgreSQL · Data Engineering · Backend Systems</p>

<p align="center">
  Quito, Ecuador ·
  <a href="https://vladimirjon.github.io/JohannPasquel_PersonalWebsite/">Portfolio</a> ·
  <a href="https://www.linkedin.com/in/johannpasquel/">LinkedIn</a>
</p>

## About me

I am a Computer Science Engineering student at **Escuela Politécnica Nacional** with practical experience in backend development, relational databases, Linux environments, and workflow automation.

I am moving toward **data engineering** because I enjoy the part of software where reliability matters most: acquiring source data, preserving evidence, validating it, modeling relationships, and making the result useful for analytics.

```text
source → raw evidence → validation → relational storage → transformation → analytics
```

I am currently looking for internships and junior roles in **data engineering, analytics engineering, and backend data systems**.

## Featured work

### 01 · [Ecuador Public Procurement Data Quality Monitor](https://github.com/Vladimirjon/ec-public-procurement-quality-monitor)

An auditable foundation for preserving and assessing Ecuadorian public-procurement source data.

- Built content-addressed raw storage with SHA-256 integrity verification.
- Implemented typed source access and PostgreSQL persistence for runs, observations, and audit events.
- Added checksum-verified migrations, append-only rules, and automated unit and integration tests.
- Documented explicit boundaries between source evidence, normalized data, and future quality results.

**Status:** active development. The storage and persistence foundations are implemented; end-to-end ingestion and quality reporting are still pending.

`Python` `PostgreSQL` `SQL` `httpx` `psycopg` `Docker` `GitHub Actions`

---

### 02 · [Computer Vision Game Reconstruction](https://github.com/Vladimirjon/Captura_automatica_de_posiciones_con_AI_Vision)

End-to-end pipeline for reconstructing physical Amazons matches from images.

- Detects pieces, corrects perspective, reconstructs the board, validates moves, and tracks match state.
- The YOLOv8-nano model reached **99.38% precision, 100% recall, and 99.50% mAP50** on the project evaluation.
- Connects model output with deterministic game rules instead of stopping at object detection.

`Python` `YOLOv8` `OpenCV` `Roboflow`

---

### 03 · [Distributed Identity and High Availability](https://github.com/Vladimirjon/PasquelJ-MiniIdM)

Identity architecture deployed across three Linux virtual machines.

- Configured replicated OpenLDAP, redundant Kerberos, PKI/TLS, HAProxy, and Keepalived.
- Designed controlled failure tests that maintained **12/12 successful requests**.
- Practiced service redundancy, certificate management, health checks, and operational recovery.

`Linux` `OpenLDAP` `Kerberos` `HAProxy` `Keepalived` `PKI/TLS`

---

### 04 · [Concurrent Web Server in C](https://github.com/Vladimirjon/PasquelJ-MiniHTTPd)

Single-process HTTP server built around non-blocking TCP I/O and event multiplexing.

- Supports persistent connections, timeouts, static-file delivery, and MIME handling.
- Includes protections against path traversal and malformed requests.
- Strengthened my understanding of networking, concurrency, and systems-level failure modes.

`C` `Linux` `TCP` `Non-blocking I/O` `Systems Programming`

## Experience that supports data engineering

### Abimatik Medical Instruments

Built an offline-capable technical-reporting product that turns one structured capture into a PDF, an Excel file based on the official template, and a client email. Implemented synchronized local data, versioned corrections, append-only audit records, and automated delivery workflows.

### Conservatorio Nacional de Música

Developed backend modules and academic reporting flows with NestJS, TypeORM, MySQL, JWT, and Next.js. Unified fragmented grade structures, implemented relational integrity rules, and built reports around enrollment and academic records.

### ARCONEL

Restored and validated an institutional data-processing environment on AlmaLinux using Apache, Python, ODBC, and SQL Server. Also implemented an institutional scheduling workflow with Microsoft Bookings, Forms, and Power Automate.

## Technical toolkit

| Area | Technologies and practices |
| --- | --- |
| Data engineering | Python, SQL, PostgreSQL, MySQL, SQL Server, relational modeling, source evidence, data validation |
| Analytics | Power BI, Power Query, DAX, reproducible reporting |
| Backend | TypeScript, PHP, NestJS, TypeORM, REST APIs, JWT |
| Infrastructure | Docker, Linux, Apache, GitHub Actions |
| Automation | n8n, Power Automate, Microsoft Forms and Bookings |

## How I approach engineering

- Preserve raw evidence before transforming it.
- Make integrity rules explicit in the data model and persistence layer.
- Prefer reproducible migrations, automated checks, and observable failures.
- State project limitations instead of presenting prototypes as finished systems.
- Keep documentation close to the decisions it explains.

## Recognition and credentials

- **3rd place in Ecuador — IEEEXtreme 19.0**, Team Kiubit.
- **Cambridge English C1**.
- **n8n Professional Certificate**, 2026.
- **Power BI: Data Analysis and Data Modeling**, Santander Open Academy, 2026.
- **Scrum Fundamentals Certified**, 2025.

## Current focus

- Completing an auditable public-procurement ingestion and quality workflow.
- Strengthening batch-processing, data-profiling, and PostgreSQL design practices.
- Building a portfolio where every highlighted project has clear evidence, limitations, and reproducible setup.

<p align="center">
  <strong>Open to data engineering, analytics engineering, and backend data opportunities.</strong>
</p>

