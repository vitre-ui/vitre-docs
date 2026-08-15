# vitre-docs

![Vitre UI](https://vitre-ui.com/images/vitre-ui-dark.webp)

Documentation for Vitre UI, the `vitre-css` package.

This site is plain static HTML/CSS/JS. It loads the latest published
`vitre-css` from unpkg &mdash; both `vitre.css` and the optional `vitre.js`
&mdash; so it showcases current behavior without a local package install or
build step.

Pages:

- `index.html` &mdash; overview, installation, directives, and the token reference.
- `components.html` &mdash; per-component markup, demos, and behavior.
- `examples.html` &mdash; a dense element gallery for spot-checking raw semantic HTML.

> `vitre-js` merged into `vitre-css` in 1.6.0. All pages load
> `unpkg.com/vitre-css/vitre.js`.

## Development

```sh
http-server .
```

Any static file server can be used from the repository root.

## Deployment

GitHub Pages serves the repository root from `main`.

- Pages URL: `https://docs.vitre-ui.com/`
