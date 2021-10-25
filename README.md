# demo-restaurant-astro-json

 An example which uses structure content in JSON files to generate an archetypal restaurant site using [Astro](https://astro.build).

 👉 https://demo-restaurant-astro-json.netlify.app/


This example is useful for exploring how Astro can generate a site from structured data. You can also use a [decoupled CMS](https://jamstack.org/glossary/decoupling/) to power such a site, either by consuming the CMS data directly from its API, or by adding a small layer of abstraction which populates the site's data files from the CMS ahead of each build.

For an illustration of using Astro with a Netlify Build Plugin to pull content from a decoupled CMS, you can [explore this example](https://github.com/netlify/demo-restaurant-astro-contentful), and [read about this pattern in this blog post](https://www.netlify.com/blog/2021/10/25/learning-to-future-proof-sites-using-headless-cms-and-different-ssgs/). 

## Usage for Development and Deployment

Clone this repo and then in your working directory:

```bash
# install the dependencies including Astro
npm i

# run the local development server
npm run dev

```

## Speedy start

To clone this repo and instantly generate and deploy it for free on Netlify, click the Deploy To Netlify button below.


[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/philhawksworth/demo-restaurant-astro-json&campaign=devex-ph")



## For deployment to Netlify

```bash
# Install the Netlify CLI globally
npm i -g netlify-cli

# create a Netlify site as a deployment target
netlify create

# deploy the latest local build to production
npm run build
netlify deploy --prod
```




