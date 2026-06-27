# HDI Classifier — Herb-Drug Interaction Analysis Pipeline

Live Frontend: https://hdi-frontend-wo54.vercel.app
Live API: https://tvganesh538-nlp-classifier-api.hf.space
API Docs: https://tvganesh538-nlp-classifier-api.hf.space/docs
Model Repo: https://huggingface.co/tvganesh538/hdi-models



\---

title: NLP Classifier API

emoji: 🧬

colorFrom: green

colorTo: blue

sdk: docker

pinned: false

app\_port: 7860

\---



\# NLP Herb-Drug Interaction Classifier API



A FastAPI-based REST API for classifying herb-drug interactions using Groq LLM.



\## Endpoints



\- `GET /health` — public health check

\- `POST /classify` — classify text (requires API key)

\- `GET /analytics/summary` — analytics (requires API key)

\- `GET /history` — classification history (requires API key)

\- `GET /dashboard` — live dashboard (public page, key entered in UI)

\- `GET /docs` — Swagger UI



\## Usage



All protected endpoints require `X-API-Key` header.



Generate a key via the `/admin/keys` endpoint using the admin key printed in container logs on first startup.



