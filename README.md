# Osvaldo Hernández Ortiz — Sitio personal

Sitio personal de **Osvaldo Hernández Ortiz**, especialista en Marketing Digital, Social Media y Performance.

HTML, CSS y JavaScript puro en un solo archivo (`index.html`), sin frameworks ni proceso de build.

## Características

- Bilingüe español / inglés (detecta el idioma del navegador).
- Modo claro y oscuro (respeta la preferencia del sistema).
- Control de tamaño de texto (A− / A+), base de 18px.
- Accesible: navegación por teclado, contraste AA, respeta `prefers-reduced-motion`.
- Contacto directo por WhatsApp y correo, con mensaje prellenado según el idioma.

## Estructura

```
index.html   → todo el sitio
foto.jpg     → retrato (opcional; si no existe se muestra un marcador)
cv.pdf       → currículum (opcional)
```

## Publicar en GitHub Pages

1. Sube este repositorio a GitHub.
2. En el repositorio: **Settings → Pages**.
3. En **Source** elige `Deploy from a branch`, rama `main`, carpeta `/ (root)` y guarda.
4. En uno o dos minutos el sitio queda en `https://<tu-usuario>.github.io/<repositorio>/`.

> Si nombras el repositorio `<tu-usuario>.github.io`, el sitio queda en la raíz: `https://<tu-usuario>.github.io/`.

## Editar contenido

Todo el texto está en `index.html`. Cada frase existe dos veces: `data-l="es"` (español) y `data-l="en"` (inglés). Edita ambas versiones.

Correo y WhatsApp se configuran en las constantes `EMAIL` y `PHONE` al final del archivo (y en los `href` del HTML).
