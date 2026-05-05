# C·NOW

## English

C·NOW is a small static web app that displays the current time, day, month, year, and season in Chinese, along with pinyin and quick access to related learning content.

### What it does

- Shows the live clock in Chinese numerals.
- Shows the current weekday, month, year, and season.
- Displays pinyin pronunciation for each value.
- Uses a fixed mobile-friendly layout and can run as a standalone PWA.
- Links out to the related `chinese-words` resource through the configured base URL.

### Project structure

```text
index.html
manifest.json
images/
```

### Run locally

This project has no build step or package installation.

1. Open `index.html` directly in a browser, or
2. Serve the folder with any static web server if you want a more realistic PWA test.

### Notes

- The page loads Google Fonts and Font Awesome from external CDNs.
- The access link is resolved dynamically from `https://eugeniosaintemarie.github.io/config-central/url.json`.
- App icons are stored in the `images/` folder.

## Español

C·NOW es una pequeña aplicación web estática que muestra la hora, el día, el mes, el año y la estación actual en chino, junto con la pronunciación en pinyin y un acceso rápido a contenido relacionado.

### Qué hace

- Muestra el reloj en vivo con números chinos.
- Muestra el día de la semana, el mes, el año y la estación actuales.
- Incluye la pronunciación en pinyin de cada valor.
- Usa un diseño fijo adaptado a mobile y puede funcionar como PWA independiente.
- Enlaza al recurso relacionado `chinese-words` mediante la base URL configurada.

### Estructura del proyecto

```text
index.html
manifest.json
images/
```

### Cómo ejecutarlo

Este proyecto no necesita build ni instalación de dependencias.

1. Abrí `index.html` directamente en el navegador, o
2. Serví la carpeta con cualquier servidor web estático si querés probar la PWA de forma más realista.

### Notas

- La página carga Google Fonts y Font Awesome desde CDNs externos.
- El enlace de acceso se resuelve dinámicamente desde `https://eugeniosaintemarie.github.io/config-central/url.json`.
- Los íconos de la app están en la carpeta `images/`.