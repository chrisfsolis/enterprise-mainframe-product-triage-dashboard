# Enterprise Mainframe Product Triage Dashboard

A recruiter-facing product management prototype for prioritizing fictional enterprise mainframe customer requests by renewal risk, regulatory impact, modernization value, engineering effort, and adoption potential.

## Live UI Prototype
- Dashboard source: [`dashboard/`](dashboard/)
- Live Demo: TODO - add deployed Vercel URL

## Build validation
- GitHub Actions workflow: [`.github/workflows/dashboard-ci.yml`](.github/workflows/dashboard-ci.yml)
- Note: This repository includes CI to validate dashboard builds on `push` to `main` and `pull_request`.

## Why this artifact exists
This project is a public portfolio artifact for PM interview preparation. It demonstrates practical product judgment for mature enterprise software domains where continuity, compliance, modernization, and customer retention must be balanced.

## Local run instructions
```bash
cd dashboard
npm install
npm run dev
```

## Build instructions
```bash
cd dashboard
npm install
npm run build
```

## Deployment instructions (Vercel)
- Root Directory: `dashboard`
- Framework Preset: `Vite`
- Install Command: `npm install`
- Build Command: `npm run build`
- Output Directory: `dist`

## Backlog and PM Artifacts
- Product backlog outline: [`product-backlog-outline.md`](product-backlog-outline.md)
- Customer triage matrix: [`customer-request-triage-matrix.md`](customer-request-triage-matrix.md)
- Sample customer requests: [`sample-customer-requests.md`](sample-customer-requests.md)
- Prioritization model: [`prioritization-model.md`](prioritization-model.md)
- Interview narrative and resume bullets: [`interview-talking-points.md`](interview-talking-points.md)

## Public portfolio disclaimer
This project uses fictional customer data and does not contain proprietary information or represent any specific company’s internal roadmap.
