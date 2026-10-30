# CargoShare application

This directory contains the CargoShare web app, API, infrastructure, and observability configuration.

For the complete project overview, setup guide, architecture, demo accounts, API reference, and deployment notes, see the **[canonical repository README](../README.md)**.

## Common commands

```bash
npm ci
npm run dev       # Vite development server
npm run lint      # ESLint
npm run build     # Type-check and production build
npm run preview   # Preview the production build
```

The frontend demo runs at <http://localhost:5173> by default and does not require backend services. To start the complete supporting stack, copy the local environment template and run:

```bash
cp .env.example .env
docker compose up --build
```

See the root README for service URLs, configuration, demo credentials, and production cautions.
