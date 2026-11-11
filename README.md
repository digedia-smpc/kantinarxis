# Kantinarxis (Καντινάρχης)

Website for Kantinarxis, a street-food sandwich shop in Athens, live at [kantinarxis.digedia.eu](https://kantinarxis.digedia.eu).

This private repository contains only the Kantinarxis site. The files at the repository root are a static snapshot of the production assets (HTML, CSS, images, fonts, and audio). The original front end was built with Astro, which is why compiled assets live under `_astro/`. There is no application source, build step, or environment file in this repository.

## Deployment

The site is deployed on Cloudflare Pages as the project **`kantinarxis-digedia`** (custom domain `kantinarxis.digedia.eu`).

To publish updates, deploy the repository root as a static site to that Cloudflare Pages project. This repository is not currently connected to Cloudflare as a Git source; do not change the live deployment unless you intend to.

## Scope

This repo is limited to Kantinarxis. It does not include other Digedia sites, database dumps, or secrets.
