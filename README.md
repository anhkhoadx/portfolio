# Personal Portfolio

This repository contains my personal portfolio website.

The site is intentionally built as a **simple static HTML page**, focused on clarity, storytelling, and long-term maintainability rather than visual effects or heavy frameworks.

🔗 **Live site**  
https://anhkhoadx.github.io/portfolio/

---

## About Me

I started my career as a **Software Engineer**, building backend systems and shipping product features.

As products and teams grew, data became increasingly important — and increasingly unreliable.  
Metrics were unclear, data sources were fragmented, and numbers could not be trusted.

That was when I transitioned into **Data Engineering**.

Since then, I’ve built and owned end-to-end data platforms from zero to business-critical scale:
- discovering and consolidating data sources,
- cleaning and validating messy data,
- designing scalable pipelines and warehouse models,
- enabling self-service analytics through trusted metrics and semantic definitions,
- and evolving data architectures to keep pace with growth.

This portfolio is a short summary of that journey — from writing code that works, to building systems that last.

---

## What This Portfolio Is (and Is Not)

**This portfolio is:**
- A narrative of how I think about engineering systems
- A reflection of real-world experience and trade-offs
- A place to share selected work, writing, and ideas

**This portfolio is not:**
- A flashy landing page
- A frontend showcase
- A list of tools without context

---

## Featured Work

The portfolio highlights a few themes that reflect how I approach data engineering:

### 1) Company-wide Data Platform & Single Source of Truth
- Unifying product, marketing, and finance data into a consistent analytics layer
- Standardizing metrics to improve trust and decision-making
- Enabling high adoption of self-service analytics

### 2) High-volume Event Analytics at Scale
- Designing ingestion + modeling for high-throughput event data
- Supporting both batch and near real-time use cases
- Powering customer-facing analytics features

### 3) Legacy-to-Modern Warehouse Migration (Blueprint)
- Moving from procedural / trigger-driven logic to **model-driven** transformations
- Applying **Medallion architecture** (Bronze → Silver → Gold) and **idempotent** re-runnable models
- Using rigorous validation (row-count reconciliation, metric diffing, controlled parallel runs)
- Considering modern orchestration + transformation patterns (SQLMesh-aligned, Dagster-aligned concepts)
- Evaluating cloud warehouse optimization patterns (partitioning/clustering/cost-aware queries; BigQuery-style best practices)

> Note: In my work, specific tools vary by company. I focus on principles and patterns that transfer across warehouses and orchestrators.

---

## Writing

I regularly write about engineering and real-world system trade-offs:
- Medium (technical writing)
- Guides on data platforms, modeling, validation, and maintainable systems

---

## Tech Stack

The website is deliberately kept simple.

- **HTML5**
- **CSS (minimal, inline styles)**
- **GitHub Pages** for hosting

No frameworks.  
No JavaScript.  
No build step.

This choice reflects how I approach engineering:
- keep systems maintainable,
- reduce unnecessary complexity,
- and optimize for long-term clarity.

---

## Local Development

Just open `index.html` in your browser.

If you want a quick local server:

```bash
python -m http.server 8000
```

Then open: `http://localhost:8000`

---

## Deployment

The site is hosted via **GitHub Pages**.  
Push to the default branch and GitHub Pages will publish the latest `index.html`.

---

## Notes on Customization

- Update content directly in `index.html`
- Keep sections concise and results-driven
- Prefer architectural decisions + trade-offs over long tool lists
