# IRON PULSE — App Móvil Instalable (PWA)

Este paquete contiene los archivos listos para instalar **IRON PULSE** como una aplicación nativa en **Android** y **iOS (iPhone/iPad)**, con funcionamiento offline y pantalla completa sin barra de navegador.

## Archivos incluidos
- `index.html`: Aplicación completa de control de pesos, volumen semanal, calendario y PRs.
- `manifest.json`: Manifiesto de instalación móvil (nombre, colores, orientación e íconos).
- `sw.js`: Service Worker para caché offline.
- `icon-192.png` y `icon-512.png`: Íconos para el cajón de aplicaciones y pantalla de inicio.

## Cómo instalar en tu teléfono (2 opciones)

### Opción 1: Subir gratis en 30 segundos (Recomendado)
1. Descomprime esta carpeta.
2. Entra a [Netlify Drop](https://app.netlify.com/drop) o [Vercel](https://vercel.com) (o GitHub Pages) y arrastra la carpeta descomprimida.
3. Abre el enlace HTTPS generado desde tu teléfono:
   - **Android (Chrome):** Toca el banner **"Instalar"** que aparece arriba o en menú `⋮` → **"Instalar aplicación"**.
   - **iPhone / iPad (Safari):** Toca el botón **Compartir** (`□↑`) → **"Agregar a inicio"**.

### Opción 2: Generar APK nativo para Android (Opcional)
Si deseas un archivo `.apk` instalable directamente:
1. Sube la carpeta a un enlace HTTPS (como Netlify Drop o GitHub Pages).
2. Entra a [PWABuilder.com](https://www.pwabuilder.com), pega tu enlace y descarga el paquete **Android (.apk)** listo para instalar.
