# MEP Controls Dashboard & Risk Register

A portfolio-ready project-controls dashboard based on the MEP project described in Shubham Kumar's resume. It turns sample project data into a practical control-tower interface for schedule, cost, resources, risks, dependencies, and actions.

## Features

- Portfolio overview for Nexus Tower and Orbit Data Centre sample projects
- Baseline vs actual schedule variance tracker with search and status filters
- Progress KPIs and work-package progress bars
- Planned vs actual cost view with discipline resource allocation
- Risk register with probability, impact, severity score, mitigation, and owner
- Dependency register and two-week look-ahead action log
- Exportable plain-text snapshot for handover packs
- Responsive layout suitable for desktop review and mobile reference

## Run locally

This is a dependency-light static app. Serve the project directory with any static server, for example:

```bash
python3 -m http.server 3000
```

Then open `http://localhost:3000`.

## Data model

All sample data is intentionally visible in `app.js` so the project can be adapted to Excel, a REST API, or a managed database later. The dashboard is labeled as sample portfolio data and does not represent a live project.
