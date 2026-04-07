<h1 align="center">Oxlo Vision</h1>

<p align="center">
  <strong>Hackathon project built for OxBuild by Oxlo.ai</strong>
</p>

<p align="center">
  <a href="https://oxlovision.vercel.app/"><img src="https://img.shields.io/badge/LIVE%20DEMO-Oxlo%20Vision-0ea5e9?style=for-the-badge&logo=vercel&logoColor=white" alt="Live Demo"></a>
  <a href="https://oxlovision.vercel.app/"><img src="https://img.shields.io/badge/OPEN%20NOW-oxlovision.vercel.app-22c55e?style=for-the-badge" alt="Open Now"></a>
</p>

<h2 align="center">🚀 Judges: Try the deployed project here</h2>

<p align="center">
  <a href="https://oxlovision.vercel.app/"><strong>https://oxlovision.vercel.app/</strong></a>
</p>

---

## Judges First

Oxlo Vision was built to demonstrate a complete, real-world AI workflow in one product:

- Input: upload digital or scanned PDFs
- Processing: extract text + OCR fallback
- Intelligence: orchestrate Oxlo.ai models through a unified backend
- Output: summaries, key points, mind maps, concept maps, markdown, and diagrams

For judging, the fastest validation path is to test the live product directly:

## https://oxlovision.vercel.app/

---

## Why Oxlo Vision
Oxlo Vision transforms PDF documents into actionable knowledge for students, researchers, and developers:

- Extracts text from standard PDFs and scanned PDFs (OCR fallback)
- Generates concise summaries and key points
- Builds mind maps and concept maps from real extracted content
- Produces markdown and AI-ready skill outputs for developer workflows
- Supports chat-based exploration over uploaded document content

## Built For OxBuild Judges
This project is designed to demonstrate practical value, technical execution, and product readiness:

- Fast end-to-end experience: upload PDF -> extract -> analyze -> visualize
- Real AI orchestration through Oxlo.ai model ecosystem
- Clear developer-focused outputs (markdown, diagrams, skills)
- Production-style deployment and API proxy strategy

## Tech Stack

![Frontend](https://img.shields.io/badge/Frontend-React%20%2B%20TypeScript-38bdf8?style=flat-square&logo=react&logoColor=white)
![Build Tool](https://img.shields.io/badge/Build-Vite-f59e0b?style=flat-square&logo=vite&logoColor=white)
![Backend](https://img.shields.io/badge/Backend-Micronaut-1f2937?style=flat-square&logo=micronaut&logoColor=white)
![Java](https://img.shields.io/badge/Java-JDK%2021-e11d48?style=flat-square&logo=openjdk&logoColor=white)
![AI Platform](https://img.shields.io/badge/AI-Oxlo.ai-16a34a?style=flat-square)
![Deploy](https://img.shields.io/badge/Deploy-Vercel-111827?style=flat-square&logo=vercel&logoColor=white)

## Architecture Snapshot

```mermaid
flowchart LR
  U[User]
  FE[Oxlo Vision Frontend\nReact + TypeScript]
  API[Proxy Layer\n/api + /v1]
  BE[Backend\nMicronaut + JDK 21]
  OX[Oxlo.ai Platform\nLLMs + Vision + OCR + Embeddings]

  U --> FE --> API --> BE --> OX
  OX --> BE --> FE --> U
```

## Core Features
- PDF upload with drag-and-drop and file selector
- Text extraction with OCR support for scanned pages
- Document summary and key-point generation
- Mind map generation from extracted document semantics
- Concept map generation for structured understanding
- AI chat over uploaded document context
- Diagram generation support for technical documentation

## Judge Quick Checklist
- Product value: solves a real information extraction bottleneck
- AI integration depth: multiple Oxlo.ai capabilities in one flow
- Developer usefulness: exports and structures ready for AI-assisted coding workflows
- UX completeness: from raw PDF to insights in one interface
- Deployment readiness: publicly available and testable now

## Live Project
### https://oxlovision.vercel.app/

If you are evaluating Oxlo Vision, please start with the live demo above.

## Licenses

- Frontend: [MIT](../../front-end/LICENSE)
- Backend: [MIT](../../back-end/LICENSE)
