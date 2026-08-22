# Cómo generar el APK de "10 SECONDS" (automático, gratis, sin instalar nada)

Este proyecto incluye un robot (GitHub Actions) que compila el APK por ti en la nube.
Tú solo subes los archivos, esperas ~3 minutos y descargas el APK ya listo.

## Paso 1 — Crear cuenta en GitHub (si no tienes)
1. Ve a https://github.com/signup
2. Crea una cuenta gratuita.

## Paso 2 — Crear el repositorio
1. Entra a https://github.com/new
2. Nombre del repositorio: `10-seconds-game` (o el que quieras)
3. Déjalo en **Public** o **Private**, cualquiera funciona.
4. NO marques "Add a README" (ya tenemos uno).
5. Click en **Create repository**.

## Paso 3 — Subir los archivos (sin usar comandos)
1. En la página del repositorio recién creado, click en **"uploading an existing file"**
   (o el botón **Add file → Upload files**).
2. Arrastra **TODO el contenido** de esta carpeta que te entregué (todas las carpetas y
   archivos: `www`, `assets`, `.github`, `package.json`, `capacitor.config.ts`, etc.)
   directamente al navegador.
   - Importante: arrastra el *contenido* de la carpeta, no la carpeta comprimida en sí.
3. Abajo, en "Commit changes", deja el mensaje por defecto y click en **Commit changes**.

## Paso 4 — Ver cómo se compila solo
1. Click en la pestaña **Actions** (arriba del repositorio).
2. Verás un proceso llamado "Build 10 SECONDS APK" corriendo (círculo amarillo girando).
3. Espera 2–4 minutos hasta que se ponga con un ✅ verde.
   - Si sale ❌ rojo, click adentro para ver el error y pégamelo aquí, lo arreglamos.

## Paso 5 — Descargar el APK
1. Con el ✅ verde, click en esa ejecución (el nombre "Build 10 SECONDS APK").
2. Baja hasta la sección **Artifacts**.
3. Descarga **10-SECONDS-apk** (es un .zip que contiene el .apk adentro).
4. Descomprime ese .zip en tu computadora → ahí está `app-debug.apk`.

## Paso 6 — Instalar en tu Samsung
1. Pásate el archivo `app-debug.apk` al teléfono (por USB, Google Drive, WhatsApp a ti mismo, etc.)
2. Ábrelo desde el Administrador de archivos del teléfono.
3. Android te va a pedir permiso para "instalar apps de origen desconocido" — acéptalo
   (es normal para un APK de prueba que no viene de Play Store).
4. Instala y abre **10 SECONDS** 🎉

---

Cuando lo tengas corriendo en tu Samsung, jugalo y anota todo lo que se te ocurra
("esto está muy fácil", "este color no me gusta", etc.) y lo vamos iterando — eso es la Fase 2.
