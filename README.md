# conferencia-web

Base de micrositio estatico para una conferencia. El proyecto usa solamente `HTML`, `CSS` y `JavaScript` simple, con rutas relativas para funcionar igual en local y en GitHub Pages.

## Estructura

```text
conferencia-web/
- index.html
- conferencia.html
- assets/css/style.css
- assets/js/site-data.js
- assets/img/portada.png
- assets/img/acto1.png
- assets/img/acto2.png
- assets/img/acto3.png
- assets/pdf/memoria-conferencia.pdf
- README.md
```

## Como abrirlo localmente con Live Server en VS Code

1. Abre la carpeta `conferencia-web` en VS Code.
2. Instala la extension `Live Server` si todavia no la tienes.
3. Haz clic derecho sobre `index.html`.
4. Elige `Open with Live Server`.
5. Se abrira el micrositio en tu navegador con las mismas rutas relativas que luego serviran en GitHub Pages.

Tambien puedes abrir `index.html` directamente en el navegador, pero Live Server ayuda a refrescar cambios mas comodo mientras editas.

## Archivo que debes editar para cambiar links

Edita `assets/js/site-data.js`.

En ese archivo puedes cambiar:

- `siteTitle`
- `siteSubtitle`
- `authorName`
- `driveAudioUrl`
- `driveVideoUrl`
- `pdfUrl`

Los enlaces de audio y video vienen con placeholders de Google Drive para que los reemplaces despues por tus URLs reales.

## Que editar despues

- Cambia el texto principal de `index.html` si quieres ajustar la introduccion o los tres bloques resumen.
- Cambia el texto completo de `conferencia.html` para pegar la version final de la conferencia.
- Reemplaza las imagenes dentro de `assets/img/`.
- Reemplaza el archivo `assets/pdf/memoria-conferencia.pdf` por el PDF real manteniendo el mismo nombre, o actualiza `pdfUrl` en `assets/js/site-data.js`.

## Nota importante

Las imagenes y el PDF incluidos son placeholders vacios para dejar la estructura lista. Si todavia no tienes materiales finales, el sitio no se rompe: muestra espacios preparados para insertar el contenido despues.
