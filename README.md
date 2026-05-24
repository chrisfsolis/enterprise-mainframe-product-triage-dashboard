# Enterprise Mainframe Product Triage Dashboard

A product management dashboard prototype for prioritizing **fictional** enterprise mainframe customer requests by renewal risk, regulatory impact, modernization value, customer severity, engineering effort, and adoption potential.

## Why this artifact exists
This project is a public portfolio artifact for PM interview preparation. It demonstrates practical product judgment for mature enterprise software domains where continuity, compliance, modernization, and customer retention must be balanced.

## Target audience
- Recruiters evaluating PM communication and clarity
- Hiring managers assessing product judgment and prioritization logic
- Product, Engineering, Support, Sales, and Architecture stakeholders discussing roadmap tradeoffs

## Product management problem statement
Customer requests for mature enterprise products often come from fragmented channels and can be difficult to compare consistently. This prototype shows a lightweight way to triage requests using a transparent scoring model and explicit PM decision rationale.

## UI Prototype
- Dashboard source: [`dashboard/`](dashboard/)
- Run locally and view the static prototype in browser.

## Backlog and PM Artifacts
- Product backlog outline: [`product-backlog-outline.md`](product-backlog-outline.md)
- Customer triage matrix: [`customer-request-triage-matrix.md`](customer-request-triage-matrix.md)
- Sample customer requests: [`sample-customer-requests.md`](sample-customer-requests.md)
- Prioritization model: [`prioritization-model.md`](prioritization-model.md)
- Interview narrative and resume bullets: [`interview-talking-points.md`](interview-talking-points.md)

## Local run instructions
```bash
cd dashboard
npm install
npm run dev
```

## Build instructions
```bash
cd dashboard
npm run build
```


## Vercel deployment settings
- Project root: `dashboard`
- Framework preset: `Vite`
- Install command: `npm ci` (if `package-lock.json` exists) or `npm install`
- Build command: `npm run build`
- Output directory: `dist`
- Live Demo: TODO - add Vercel deployment URL

## Disclaimer
All data in this repository is fictional and public/demo-safe. This project does **not** contain proprietary information and does **not** represent any specific company’s internal roadmap.
