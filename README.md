# OmniaTech AI

OmniaTech AI è una piattaforma enterprise multi‑settore che integra orchestrazione, compliance, incident management e billing in un unico monorepo.

## 🚀 Caratteristiche principali
- Orchestrator, Superior Agent, Workforce
- Security: JWT/JWKS, mTLS, audit trail
- Compliance: checklist dinamiche e report mensili
- Incident Management: escalation automatica e notifiche Telegram/Matrix
- Billing: multi‑tenant, fatturazione e KPI
- Observability: Prometheus, Grafana, OpenTelemetry

## 📦 Installazione
### Docker Compose
```bash
git clone https://github.com/HighKali/omniatech-ai.git
cd omniatech-ai
docker compose -f infra/docker-compose.yml up -d --build
```

### Pacchetti
Scaricabili da [Releases](https://github.com/HighKali/omniatech-ai/releases).

## 🔑 Secrets richiesti
- DOCKER_USERNAME, DOCKER_PASSWORD
- POSTGRES_PASSWORD
- JWT_ISSUER, JWT_AUDIENCE, JWKS_URL

## 📊 Dashboard
http://localhost:8080/dash/status

## 🌐 Dominio GitHub Pages
Documentazione pubblica: https://highkali.github.io/omniatech-ai/
