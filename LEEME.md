# Cronómetro Barista: cómo publicarla

La carpeta tiene todo lo necesario:

- `index.html`: la app
- `manifest.json`: nombre, ícono y colores para instalarla en el celular
- `sw.js`: hace que funcione sin internet después de abrirla una vez
- `icon-192.png` e `icon-512.png`: íconos

## Opción 1: Netlify Drop (la más rápida, gratis)

1. Descomprime el zip.
2. Entra a https://app.netlify.com/drop
3. Arrastra la carpeta `cafe-app` completa a la página.
4. Te da un link tipo `https://algo.netlify.app`. Crea una cuenta gratis para que el link no expire y para cambiarle el nombre.

## Opción 2: GitHub Pages (gratis)

1. Crea un repositorio nuevo en GitHub, por ejemplo `cafe`.
2. Sube los 5 archivos a la raíz del repositorio.
3. Ve a Settings → Pages, elige la rama `main` y la carpeta `/ (root)`.
4. En un par de minutos queda en `https://TU-USUARIO.github.io/cafe/`.

## Instalarla en el celular

- **Android (Chrome):** abre el link, menú ⋮ → "Instalar app" o "Agregar a pantalla principal".
- **iPhone (Safari):** abre el link, botón Compartir → "Agregar a inicio".

Queda con su ícono y se abre a pantalla completa, como una app normal.

## Si haces cambios

Edita `index.html` y vuelve a subir los archivos. En `sw.js` cambia `barista-v1` por `barista-v2` para que los celulares descarguen la versión nueva.

Nota: abrir `index.html` con doble clic funciona para probarla, pero para instalarla y usarla sin internet tiene que estar publicada en un link `https://`.
