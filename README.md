# A starter kit for tailwindcss without bundlers

## Requirements

- [Tailwindcss](https://tailwindcss.com/)
- [Tailwindcss CLI](https://tailwindcss.com/docs/installation)
- [Live Server](https://www.npmjs.com/package/live-server)
- [NPM Run All](https://www.npmjs.com/package/npm-run-all)

## How to use

1. Run `npm install`
2. Run `npm run dev`
3. Open `http://localhost:8080`

## How to build css

In order to build css from src run:

```sh
npm run build
```

It will create `./css/app.css` containing the compiled css.

## How to watch css

If you want to watch css changes and recompile them run:

```sh
npm run watch-css
```

It will watch changes and recompile `src/app.css` to `./css/app.css`

## How to serve the project

If you want to serve the project run:

```sh
npm run serve
```

It will serve the project on `http://localhost:8080` or use another random port if it is already in use.

## What are [subgrids](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_grid_layout/Subgrid)

Subgrids are a new feature of css grid layout that allows you to specify a grid inside a grid that aligns with the outer (direct) parent grid. Nested grid uses the tracks defined on the parent

Tailwindcss can be used to specify subgrids.

## Examples of subgrids

- [subgrid-1.html](subgrid-1.html)
- [subgrid-2.html](subgrid-2.html)
- [subgrid-3.html](subgrid-3.html)
- [subgrid-4.html](subgrid-4.html)
- [subgrid-5.html](subgrid-5.html)
- [subgrid-6.html](subgrid-6.html)

These pages are examples of how to use tailwindcss to specify subgrids in various layouts.

The `index.html` is the index of the examples.
