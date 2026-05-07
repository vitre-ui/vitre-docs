# vitre-docs

Documentation for Vitre UI, covering `vitre-css` and `vitre-js`.

This site is built with Vite and uses Vitre packages as normal npm
dependencies. The first implementation is plain semantic HTML with no UI
framework.

## Development

```sh
pnpm install
pnpm dev
```

## Build

```sh
pnpm build
pnpm serve
```

## Deployment

GitHub Pages builds from `main` with `.github/workflows/pages.yml`.

- Build command: `pnpm build`
- Build output directory: `dist`
- Pages URL: `https://docs.vitre-ui.com/`
