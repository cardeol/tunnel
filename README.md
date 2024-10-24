# Tunnel

1. Create .env with OPENVPN_USER= and OPENVPN_PASSWORD=

2. Clone gluetun

```
git clone https://github.com/qdm12/gluetun
```

## Dedicated IP Server US 1082

```
docker compose -f dedicated-compose.yml up --build -d
```

## Ireland Server 1083

```
docker compose -f ireland-compose.yml up --build -d
```

