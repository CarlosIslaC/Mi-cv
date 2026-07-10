# Portafolio · Carlos Isla Correa

## Qué hay adentro

- `index.html` — la página principal (Sobre mí, experiencia, skills, contacto).
- `cv.pdf` — tu CV, se descarga desde el botón "Descargar CV ↓".
- `styles.css` — sistema de diseño reutilizable (lo usan los posts).
- `post-spec-driven-45.html` — un post técnico ya redactado, listo para publicar.
- `LEEME.md` — este archivo.

## Cómo publicarla (elige uno)

### Opción A · Netlify Drop  (2 minutos, sin cuenta)

1. Entra a **https://app.netlify.com/drop**
2. Arrastra esta carpeta completa (o el zip) sobre la caja grande.
3. Netlify te da un enlace tipo `nombre-al-azar-1234.netlify.app`.
4. Opcional: crea una cuenta gratis y en *Site settings → Change site name*
   cambias el subdominio a algo como `carlos-isla.netlify.app`.

### Opción B · GitHub Pages  (mejor URL, usa tu cuenta)

1. En GitHub crea un repo **público** llamado `portafolio` (o el nombre que quieras).
2. Sube los archivos: botón **"Add file → Upload files"** → arrastra todo → Commit.
3. En el repo ve a **Settings → Pages**.
4. En *Source* elige **Deploy from a branch**, rama `main`, carpeta `/ (root)`.
   Guardar.
5. Tu URL queda como `https://TUUSUARIO.github.io/portafolio/`.
   Tarda 1–2 minutos en estar viva la primera vez.

## Para actualizarla después

- **En Netlify Drop:** arrastras la carpeta actualizada, reemplaza todo.
- **En GitHub:** subes los archivos nuevos al repo (o `git push` si trabajas con Git).

## Dominio propio (opcional)

Ambos servicios te dejan conectar un dominio comprado (tipo `carlosisla.dev`).
En Netlify se hace en *Domain settings*; en GitHub Pages en *Settings → Pages → Custom domain*.
Un dominio cuesta ~10–15 USD/año en Namecheap o Porkbun.
