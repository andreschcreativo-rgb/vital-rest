# Reglas del proyecto - Agencia landing pages

## Stack técnico
- Proyecto HTML puro, NUNCA usar Next.js ni otros frameworks
- index.html debe estar siempre en la raíz del proyecto
- CSS y JS pueden ir en carpetas separadas (css/, js/) o inline en el HTML

## Git
- Antes de hacer push, siempre correr: git pull origin master --no-edit
- Mensajes de commit claros y en español, describiendo el cambio real

## Despliegue
- El proyecto se despliega automáticamente vía GitHub → Vercel al hacer push a master
- No se requiere configuración adicional de build (sitio estático)

## Estilo de trabajo
- Antes de escribir código, siempre proponer un plan corto y pedir aprobación
- Cambios pequeños y verificables, no reescribir archivos completos sin necesidad
