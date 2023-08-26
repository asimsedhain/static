# Ashim's SvelteKit template

## How it differs from the basic SvelteKit starter project

This preconfigured this template with the following:

* It's set up to only output static files and not depend on any particular server.
* It assumes TypeScript everywhere.
* It enables ESLint and automatic code formatting.
* It enables SCSS.
* It enables Markdown (using MDsveX, which lets you mix Markdown and Svelte in the same file).
* It includes opinionated global styles to get beautiful text by default.
* It includes HTML minification.
* It includes a GitHub Actions publishing workflow to deploy Github Pages.

## Building and running

* `npm install`: Install dependencies
* `npm start`: Start dev server
* `npm run build`: Production build
* `npm run serve`: Serve production build for testing

## Customizing for your site

At minimum, do this to customize the site for your purposes:

1. Find and replace `SvelteKitTemplate` with the name of your site
1. Change the package.json project name to repository name. This is needed for properly deploying for Github pages.
1. Update the copyright information in [`src/routes/+layout.svelte`](src/routes/+layout.svelte)
1. Replace image assets in `static/images/app` with appropriate logos for your site
1. Give yourself credit in [`humans.txt`](static/humans.txt)

