# DocuFran 📂

PWA personal para buscar documentos en Nextcloud.

## Archivos
- `index.html` — app principal
- `manifest.json` — configuración PWA
- `sw.js` — service worker (funciona sin conexión)
- `catalogo_archivos.csv` — catálogo de documentos (actualizar periódicamente)
- `icons/` — iconos de la app

## Cómo actualizar el catálogo
1. Ejecuta `generar_catalogo.ps1` en tu PC
2. Sube el nuevo `catalogo_archivos.csv` a este repositorio (reemplaza el anterior)

## Cómo publicar en GitHub Pages
1. Ve a Settings → Pages en tu repositorio
2. Source: `Deploy from branch` → `main` → `/ (root)`
3. Guarda. En unos minutos tendrás la URL lista.

## Cómo instalar en móvil/tablet
- **Android**: abre la URL en Chrome → menú → "Añadir a pantalla de inicio"
- **iOS**: abre la URL en Safari → compartir → "Añadir a pantalla de inicio"
