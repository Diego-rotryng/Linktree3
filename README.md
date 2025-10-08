# LinkTree Argento — Dark Premium (GitHub-ready)

## Estructura
- `/landing/` → Landing comercial con discurso + formulario + **previsualización** (no muestra JSON).
- `/app/` → Plantilla Dark que **lee ?config=<url>** con el JSON.
- `/clients/` → Demos: `barberia-demo.json`, `psicologo-demo.json`.

## Local
```bash
python -m http.server 5500
# Abrir http://localhost:5500/landing/
```

## Deploy (GitHub Pages / Vercel)
Subí esta carpeta tal cual. La landing queda en `/landing/`.
