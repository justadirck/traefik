# hub.traefik.io

connect a new agent: https://hub.traefik.io/dashboard

```bash
docker compose -f agent.yml up -d --build;
```

```bash
docker compose -f portainer.yml up -d --build;
```

configure portainer service: https://localhost:9443

```bash
publish the portainer service
```

test portainer service: https://crude-lobster-lf534a.jr1pgi6h.traefikhub.io/

```bash
docker compose -f portainer.yml down;
docker compose -f agent.yml down;
```
