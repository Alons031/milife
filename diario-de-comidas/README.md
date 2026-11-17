# Mi diario de comidas

App web para registrar comidas (calorías y proteína) y ejercicio (series, repeticiones y peso).
Funciona sin servidor: todo se guarda en el navegador del dispositivo.

## Cómo publicarla con GitHub Pages
1. Crea un repositorio nuevo en GitHub (público).
2. Sube estos archivos a la raíz del repositorio (`index.html` debe quedar afuera de cualquier carpeta).
3. Ve a **Settings → Pages**. En "Build and deployment" elige **Deploy from a branch**,
   rama **main** y carpeta **/ (root)**, y guarda.
4. Espera uno o dos minutos. Tu app quedará en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

## Cómo instalarla como app
- **Android (Chrome):** abre el link, menú ⋮ → **Instalar app** (o "Añadir a la pantalla de inicio").
- **iPhone (Safari):** abre el link, botón Compartir → **Añadir a pantalla de inicio**.
- **Computadora (Chrome o Edge):** en la barra de direcciones aparece un ícono de instalar.

## Notas
- Los datos se guardan por dispositivo y navegador. Si borras los datos del navegador, se pierden.
- Fuera de Claude, las calorías y la proteína se estiman con la lista interna de alimentos
  (la estimación con Claude solo funciona dentro de Claude).
- Para dictar por voz hace falta abrirla con https (GitHub Pages ya lo es) y dar permiso al micrófono.
- Si cambias algún archivo y no ves el cambio, sube el número de `VERSION` en `sw.js`.
