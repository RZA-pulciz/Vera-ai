# OmniaTech AI

OmniaTech AI è una piattaforma multi‑settore che orchestra processi tecnici e business in un unico monorepo.

## 🚀 Funzionalità
- Orchestrator, Superior Agent, Workforce
- Compliance, Audit, Incident Management
- Billing, Reports, Dashboard
- Gateway sicuro con JWT/mTLS
- Ops: bootstrap, backup, restore

## 📦 Installazione
### Docker Compose
```bash
git clone https://github.com/HighKali/omniatech-ai.git
cd omniatech-ai
docker compose -f infra/docker-compose.yml up -d --build
```

### Pacchetti
Scaricabili da [Releases](https://github.com/HighKali/omniatech-ai/releases).

## 🔑 Secrets
- DOCKER_USERNAME, DOCKER_PASSWORD
- POSTGRES_PASSWORD
- JWT_ISSUER, JWT_AUDIENCE, JWKS_URL

## 📊 Dashboard
http://localhost:8080/dash/status

## 📚 Documentazione
Consulta la [Wiki](https://github.com/HighKali/omniatech-ai/wiki).
