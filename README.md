# GestiPro — Landing Page

Landing page marketing per [GestiPro](https://github.com/loreformi/app-clienti), il gestionale cloud italiano per artigiani e PMI.

## Deploy su Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/loreformi/gestipro-landing)

Oppure:
1. Vai su [vercel.com](https://vercel.com)
2. **Add New Project** → importa `loreformi/gestipro-landing`
3. Framework: **Other** (static HTML)
4. Click **Deploy** — nessuna configurazione necessaria

## Deploy Docker + Nginx

```bash
docker compose up -d --build
```
Sito disponibile su `http://localhost:8080`

## File
- `index.html` — Landing page completa (single file, zero dipendenze)
- `vercel.json` — Configurazione Vercel (rewrites + security headers)
- `Dockerfile` + `nginx.conf` + `docker-compose.yml` — Per deploy Docker
