# QrAsistenciasTDT
# Asistencia con QR · Alfabetizadores

Dos páginas estáticas que usan la API de Apps Script de la planilla:

- `encargada.html`: la encargada entra con su sede y PIN y muestra un QR que cambia cada 30 segundos.
- `marcar.html`: se abre al escanear el QR, toma la ubicación del celular y registra la asistencia.

## Configuración
En **ambos** archivos, reemplazar `PEGAR_AQUI_LA_URL_DE_APPS_SCRIPT` por la URL de la aplicación web
de Apps Script (termina en `/exec`).

## Publicación (GitHub Pages)
1. Crear un repositorio público y subir `marcar.html` y `encargada.html` (en la raíz).
2. Settings → Pages → Source: "Deploy from a branch" → rama `main`, carpeta `/ (root)` → Save.
3. En 1-2 minutos queda en `https://USUARIO.github.io/REPO/encargada.html`.

Las dos páginas tienen que estar en la misma carpeta: el QR apunta a `marcar.html` junto a `encargada.html`.

