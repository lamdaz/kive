# LobeChat + Ragib API

Render-ready LobeChat deployment using an OpenAI-compatible API.

API base:
https://api.ragib.tech/v1

## Render

Create a Render Web Service from this repository using Docker.

Environment variables:
- OPENAI_API_KEY = your API key
- OPENAI_PROXY_URL = https://api.ragib.tech/v1
- ACCESS_CODE = password for LobeChat access
- PORT = 3210

## Local

```bash
cp .env.example .env
docker compose up --build
```

Open http://localhost:3210

Do not commit real API keys or access codes.
