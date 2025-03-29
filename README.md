# Marko.js with Bun.sh

## Overview

This project is:
- Powered by [@marko/run](https://github.com/marko-js/run)
- Build by [Bun.sh](https://bun.sh)
- Deployed by [GitHub Actions](.github/workflows/publish_pages.yaml)
- Hosted on [GitHub Pages](https://rdhar.github.io/bun-marko/)

## Getting Started

- Run `npm run dev` to start the development server
- Run `npm run build` to build a production-ready node.js server
- Run `npm run preview` to run the production server

## Adding Pages

Pages map to the directory structure. You can add additional pages by creating files/directories under `src/routes` with `+page.marko` files.  Learn more in the [`@marko/run` docs](https://github.com/marko-js/run/#file-based-routing).
