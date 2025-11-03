# Run haproxy with letsencrypt and dozzle log viewer on /logs
```
cd proxy
docker compose -p proxy up -d
```

NB! `-p proxy` is important

See [proxy/README.md](proxy/README.md) for more details.

# Run Dozzle logging UI
`docker compose -f logging-compose.yml up -d`
