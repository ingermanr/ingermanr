<div align="center">

<h1>Germán Alonso Rodríguez Díaz</h1>

<h3>Process Engineer · ML Engineer · Data Scientist</h3>

I turn messy operations into measurable systems — process mining, mathematical
optimization, and machine learning for industrial and trade workflows.

[![Portfolio](https://img.shields.io/badge/vector--liquidprocess.com-0f172a?style=flat-square&logo=googlechrome&logoColor=white)](https://www.vector-liquidprocess.com/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/germandsp)
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=flat-square&logo=kaggle&logoColor=white)](https://kaggle.com/germanrodriguezdiaz)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:ingenierogerman@outlook.com)

![Followers](https://img.shields.io/github/followers/ingermanr?style=flat-square&color=0f172a&label=Followers)
![Public repos](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Fusers%2Fingermanr&query=%24.public_repos&label=Repos&color=0f172a&style=flat-square)
![Location](https://img.shields.io/badge/Medell%C3%ADn-Colombia-0f172a?style=flat-square&logo=googlemaps&logoColor=white)

</div>

---

## About

Industrial engineer turned data scientist, with **10+ years** bridging plant-floor
operations and software. I care about the part most analytics projects skip: a
model only counts when it changes a decision someone actually makes.

**How I work**

- **Domain first.** The process is modelled before the code: explicit rules, named
  boundaries, no hidden I/O. Most of my repositories are hexagonal and
  framework-free at the core.
- **Measured outcomes.** Every initiative is tied to a number — cycle time,
  forecast error, inventory, cost per transaction.
- **Tools people keep using.** A CLI that fits the daily routine beats a dashboard
  nobody opens.

---

## Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### protas
**[github.com/ingermanr/protas](https://github.com/ingermanr/protas)**

Daily notes and tasks as one workspace per day. Unfinished work rolls over
automatically, and any task can grow into its own project. Zero dependencies,
SQLite local, CLI + TUI, optional Omarchy panel.

`Python` `SQLite` `TUI`

</td>
<td width="50%" valign="top">

### adicar360
**[github.com/ingermanr/adicar360](https://github.com/ingermanr/adicar360)**

SaaS domain engine that autoliquidates DIAN Form 500 customs charges from
explicit inputs. No I/O in the domain, no clock reads: persistence sits behind a
repository port with a SQLite adapter.

`Python` `Hexagonal` `Customs`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Bilt — task composition
**[github.com/ingermanr/sistema-tareas-prediseniadas-bilt](https://github.com/ingermanr/sistema-tareas-prediseniadas-bilt)**

Business processes built from reusable task templates: DAG definitions,
immutable published versions, and execution as an append-only event log with
business calendar, SLA and metrics. Pilot: a Colombian customs agency.

`TypeScript` `Hexagonal` `PostgreSQL`

</td>
<td width="50%" valign="top">

### Analisis de procesos (procmine)
**[github.com/ingermanr/analisis-de-procesos](https://github.com/ingermanr/analisis-de-procesos)**

Turns a CSV event log and a YAML config into a self-contained HTML report: data
quality, variants, discovered models, conformance, performance and
organizational analysis, built on pm4py.

`Python` `pm4py` `Process mining`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Optimization Studio
**[github.com/ingermanr/optimizacion-matematica](https://github.com/ingermanr/optimizacion-matematica)**

Guided mathematical optimization for non-experts: model a real decision,
solve it, and read the result without writing a solver script.

`FastAPI` `React` `Python`

</td>
<td width="50%" valign="top">

### DocExtract
**[github.com/ingermanr/docExtract](https://github.com/ingermanr/docExtract)**

Extraction platform for foreign trade documents — invoices, transport
documents, packing lists, certificates of origin, insurance policies — with a
review SPA and Entra ID authentication.

`FastAPI` `React` `Azure`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Rapidash Dashboard Generator
**[github.com/ingermanr/rapidash-dashboard-generator](https://github.com/ingermanr/rapidash-dashboard-generator)**

Generates dashboard layout and palette variants, previews the combinations of
charts, KPI cards and filters, and exports the chosen structure to PDF.

`Next.js` `TypeScript` `Tailwind`

</td>
<td width="50%" valign="top">

### Dataman AI
**[github.com/ingermanr/dataman-ai](https://github.com/ingermanr/dataman-ai)**

A Claude Code harness for data analysts: six checkpoint-gated phases that take a
vague business ask to a defensible answer, with the analyst directing every step.

`AI harness` `Markdown` `Analytics`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### GoPro Webcam for Omarchy
**[github.com/ingermanr/omarchy-gopro](https://github.com/ingermanr/omarchy-gopro)**

Bar widget that drives a USB GoPro HERO12 as a webcam through v4l2loopback:
start/stop the stream, switch lens and resolution, record, take a photo and
download the newest SD card file.

`QML` `Bash` `v4l2loopback`

</td>
<td width="50%" valign="top">

### Spotify for Omarchy
**[github.com/ingermanr/omarchy-spotify](https://github.com/ingermanr/omarchy-spotify)**

Bar widget with playback control over MPRIS/D-Bus, plus track search, main
artists and featured playlists through the Spotify Web API.

`QML` `D-Bus` `Spotify API`

</td>
</tr>
</table>

> **Most starred:** [data_analytics](https://github.com/ingermanr/data_analytics) — a
> structured path of resources and notebooks for learning data analytics.

---

## Current Focus

```python
current_focus = {
    "trade_operations": "customs, DIAN filings and document validation as testable domains",
    "process_mining":   "turning event logs into evidence of where the process actually breaks",
    "optimization":     "guided interfaces so operations teams can solve their own models",
    "local_first_tools": "small, dependency-free utilities that survive the daily routine",
}
```

Currently building **adicar360** (import declaration autoliquidation) and a
task-composition system for a Colombian customs agency, while keeping
**protas** as the tool I use every morning.

---

## Tech Stack

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Data & ML**
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![pm4py](https://img.shields.io/badge/pm4py-1A7F37?style=flat-square)

**Engineering**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**Analytics & BI**
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)

---

## Selected Impact

| Metric | Result | Context |
| :-- | :-- | :-- |
| Cost savings | **+$250M COP** | Process redesign + analytics in manufacturing |
| Forecast accuracy | **90%** | Demand forecasting for planning and inventory |
| Response time | **5x faster** | Automated reporting replacing manual cycles |
| Inventory reduction | **25%** | Policy tuning driven by forecast and variability |

---

## Certifications & Education

- **MSc-level ML Specialization** — Universidad EAN (2025)
- **Applied Statistics** — Universidad Católica de Manizales (2023)
- **Lean Six Sigma Black Belt** — Universidad EAFIT (2020)
- **Industrial Engineering** — Universidad Nacional de Colombia

---

## GitHub at a Glance

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=ingermanr&theme=github_dark">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=ingermanr&theme=default" alt="GitHub profile summary" width="100%">
</picture>

</div>

---

<div align="center">

**Open to collaborations** on process mining, industrial data science and
decision-support tooling.

📫 `ingenierogerman@outlook.com` · 🌍 Medellín, Colombia · 🌐 [vector-liquidprocess.com](https://www.vector-liquidprocess.com/)

<sub><em>“In day and night, data is in the path.”</em></sub>

</div>
