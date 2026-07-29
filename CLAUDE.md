# Vital Rest — reglas del proyecto

- Este proyecto se despliega vía **GitHub → Vercel** (push a `master` dispara el deploy automático).
- **Nunca usar Next.js** ni ningún framework o paso de build. Es HTML estático puro.
- `index.html` siempre debe estar en la **raíz** del repositorio (el Root Directory en Vercel es `.`).
- Antes de hacer `push`, siempre correr primero:
  ```
  git pull origin master --no-edit
  ```
