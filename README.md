# LinkTree Argento — GitHub/Vercel Patched
- Raíz redirige a `/landing/`
- **Landing** usa rutas robustas y `postMessage` para previsualizar sin `blob:`
- **App** soporta `?config=` y fallback a `/clients/barberia-demo.json` con path resuelto
- Mail a **diego.rotryng@gmail.com** con JSON normalizado + descarga `cliente.json`

## Local
```bash
python -m http.server 5500
# http://localhost:5500/landing/
```
