# Introducción a la Programación - Honores

Libro hecho con [Quarto](https://quarto.org). El sitio generado queda en la carpeta `docs/`.

- Repositorio: <https://github.com/eerosales24/ip_honores>
- Sitio publicado: <https://eerosales24.github.io/ip_honores/>

## Editar el contenido

- Cada subtema es un archivo: `nivel-1/n1-01.qmd`, `nivel-1/n1-02.qmd`, etc.
- Sus imágenes van en la carpeta `img/` de su nivel, por ejemplo `nivel-1/img/`.
- Mientras editas, deja corriendo `quarto preview`: el navegador se actualiza cada vez que guardas.
- Al terminar, ejecuta `quarto render` para actualizar `docs/`, que es lo que se publica.

## Uso

- Vista previa con recarga automática: `quarto preview`
- Generar el sitio: `quarto render`
- Publicar en GitHub Pages: en el repositorio, **Settings → Pages → Deploy from a branch**, rama `main`, carpeta `/docs`.
