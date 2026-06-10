# Trevor Reed — Professional Website

Source code for the professional website hosted at `https://tgreed86.github.io`.

## Technology

- [Astro](https://astro.build/)
- GitHub Pages
- GitHub Actions

## Local development

Astro requires Node.js 22.12.0 or newer.

```bash
npm install
npm run dev
```

The local development server will be available at `http://localhost:4321`.

## Production build

```bash
npm run build
npm run preview
```

The generated static site is written to `dist/`.

## Deployment

Every push to the `main` branch triggers `.github/workflows/deploy.yml`. The workflow builds the Astro project and deploys the generated site to GitHub Pages.

In the GitHub repository settings, configure **Pages → Build and deployment → Source** to use **GitHub Actions**.

## Current status

The repository and deployment foundation are established. Visual design and full content integration will be completed in later phases.
