# Lampac Backend

Minimal self-hosted Lampac backend for Lampa.

Before starting, change the password:

```bash
printf '%s' 'your_strong_password' > passwd
```

Start:

```bash
docker compose up -d
```

Check:

```bash
curl -I http://SERVER_IP:9118/online.js
```

Use in Lampa:

```text
http://SERVER_IP:9118/online.js
```

