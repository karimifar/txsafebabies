# Texas Safe Babies

A multi-year public health website for the **Texas Safe Babies** initiative, serving as a hub for annual summits, webinar series, and clinical implementation resources around perinatal health.

## Overview

Texas Safe Babies is a statewide initiative focused on improving birth outcomes through evidence-based perinatal practices. This site hosts resources across several program areas:

- **Annual Summits** — conference pages for the 2022 and 2023 Perinatal and Behavioral Health Summits, with agendas, speaker bios, and session recordings
- **2024 Webinar Series** — speaker profiles and PDF slides for a multi-session webinar program
- **PAP (Prenatal Alcohol Prevention)** — implementation manuals, clinic-flow worksheets, and data entry instructions
- **POSC (Perinatal Opioid Safety Checklist)** — provider toolkit, implementation guide, brochures in English and Spanish, and provider scripts

## Site Structure

| Directory | Content |
|-----------|---------|
| `/` | Main hub landing page with links to all programs |
| `2022summit/` | 2022 Perinatal & Behavioral Health Summit |
| `2023summit/` | 2023 Summit with virtual attendance option |
| `2024Series/` | 2024 webinar series with speaker profiles |
| `pap/` | Prenatal Alcohol Prevention resources |
| `posc/` | Perinatal Opioid Safety Checklist program |
| `webinar-series/` | Earlier webinar series archive |

## Tech Stack

- **Bootstrap 4** — responsive layout and components
- **Vanilla CSS / HTML** — custom styling per section
- **Google Analytics** — page-level tracking

## Running Locally

```bash
npx serve .
```
