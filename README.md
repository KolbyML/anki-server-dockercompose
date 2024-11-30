Build the docker container from these instructions

```bash
git clone https://github.com/ankitects/anki.git
docker build -f docs/syncserver/Dockerfile --no-cache --build-arg ANKI_VERSION=24.11 -t anki-sync-server .
docker compose up --build
```

Put environment variables in `.env`