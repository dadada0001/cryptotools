# cryptotools

Small browser-based crypto utilities. Everything runs client-side (Web Crypto) — nothing is sent to a server.

- **[teampulse-secrets.html](teampulse-secrets.html)** — generate the secrets for a TeamPulse deployment (JWT secret, first-admin bootstrap token, database password, and a real VAPID P-256 keypair), and copy a ready-to-run `docker-compose.yml`.

## Hosting (GitHub Pages)

Settings → Pages → Build and deployment → Source: **Deploy from a branch** → `main` / `/ (root)`.
The generator is then live at `https://dadada0001.github.io/cryptotools/teampulse-secrets.html`.
