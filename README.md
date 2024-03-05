# Web de Prueba ESLAND
Aplicacion web con fines de aprendisaje de tecnologias web. Copia mejorada de la web de los premios ESLAND

> 🧑‍🚀 **Tecnologias Web** utilizadas:
ASTRO:
```sh
npm create astro@latest -- --template basics
```


> 🧑‍🚀 **Dependecias** Utilizadas:

- Tailwind CSS
```sh
npx astro add tailwind
```
- Tailwindcss Animated
```sh
 npm install -D tailwindcss-animated
```
- Fuente texto: ONEST
```sh
 npm install @fontsource-variable/onest
```
- Web Component: Lite-youtube (optimiza el rendimiento de los video en comparacion de los <frame>)
```sh
 npm i @justinribeiro/lite-youtube
```
- PREACT: (Libreria alternativa + liviana que React, ideal para este caso para cargar componente de Animacion contador Numeros)
```sh
 npx astro add preact
```
- PhotoSwipe: Galeria de fotos
```sh
 npm i photoswipe --save
```

## 🚀 Estructura del Proyecto

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── Card.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Comandos

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
