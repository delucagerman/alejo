💫 Este es un template gratuito para crear tu sitio web de portafolio utilizando **[Astro 2.0](https://astro.build/blog/astro-2/) + [Tailwind CSS](https://tailwindcss.com/)**.

### Modo Oscuro
![Modo Oscuro](https://github.com/veranikabarel/astro-portfolio/assets/48052206/240ab82d-8896-412e-8f52-5cf10d42b1db)
### Modo Claro
![Modo Claro](https://github.com/veranikabarel/astro-portfolio/assets/48052206/bfa88b30-6dcf-4d5f-bf28-efc3caa27d0f)
### Reporte de Lighthouse
![Reporte de Lighthouse](https://github.com/veranikabarel/astro-portfolio/assets/48052206/e7ad23a4-1a9b-477e-a13e-a321ce6bd3d6)

## Tabla de Contenidos

- [Demo](#demo)
- [Características](#características)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Comandos](#comandos)
- [Contribuciones](#contribuciones)
- [Créditos](#créditos)

## Demo

📌 [https://astro-fe-portfolio.netlify.app/](https://astro-fe-portfolio.netlify.app/)

## Características

✔️ Integración con **Tailwind CSS** ([@astrojs/tailwind](https://docs.astro.build/en/guides/integrations-guide/tailwind/)) con soporte para **Modo Oscuro**.

✔️ Utiliza las siguientes integraciones:

- @astrojs/mdx
- @astrojs/image
- @astrojs/tailwind - con complemento de clasificación de clases prettier
- @astro-icon
- @astro-seo
- @astro-navbar

✔️ Se han configurado pruebas de extremo a extremo ([@Playwright](https://github.com/microsoft/playwright)).

🔜 Blog con metadatos (título, descripción, autor, fecha, imagen, etiquetas) y alimentación RSS, mapa del sitio y robots.txt.

🔜 Página de error 404

## Estructura del Proyecto

Dentro de tu proyecto de Astro, verás las siguientes carpetas y archivos:


## Project Structure

Inside of your Astro project, you'll see the following folders and files:

```
/
├── public/
│   └── favicon.ico
|   ├── hero.png
|   └── ...
├── src/
|   ├── assets/
|   |   ├── images/
│   │   |   ├── hero.png
|   |   |   └── ...
│   ├── components/
│   │   ├── ui/
│   │   |   ├── BackToTop.astro
|   |   |   └── ...
│   │   ├── About.astro
│   │   ├── Contact.astro
|   |   └── ...
│   ├── content/
│   │   ├── projects/
│   │   │   ├── project-1.md
│   │   │   ├── project-1.md
│   │   │   └── ...
│   │   └-- config.ts
│   ├── layouts/
│   │   ├── Layout.astro
│   ├── pages/
│   │   ├── index.astro
│   ├── tests/
│   │   ├── index.spec.ts
├── package.json
├── astro.config.mjs
└── ...
```


Astro busca archivos `.astro`, `.md` o `.mdx` en el directorio `src/pages/`. Cada página se expone como una ruta basada en el nombre de su archivo.

`src/components/` es donde colocamos cualquier componente de Astro y de manera similar `src/layouts/` para los diseños.

Las imágenes pueden colocarse en `src/images/`.

El contenido del blog y la documentación se crean como colecciones de archivos Markdown o MDX en `src/content`.

Cualquier recurso estático, por ejemplo, imágenes, puede colocarse en el directorio `public/`.

## Comandos

Todos los comandos se ejecutan desde la raíz del proyecto, desde una terminal:

| Comando             | Acción                                             |
| :------------------ | :------------------------------------------------- |
| `yarn`              | Instala las dependencias                           |
| `yarn dev`          | Inicia el servidor de desarrollo local en `localhost:3000`|
| `yarn build`        | Construye tu sitio de producción en `./dist/`      |
| `yarn preview`      | Previsualiza tu construcción localmente antes de implementarla|
| `yarn astro ...`    | Ejecuta comandos de CLI como `astro add`, `astro preview`|
| `yarn astro --help` | Obtiene ayuda usando el CLI de Astro               |
| `yarn test:e2e`     | Ejecuta pruebas de Playwright                       |

# alejo
