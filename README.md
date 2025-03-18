# Jekyll Tailwind Starter

A starter kit for using [Tailwind](https://tailwindcss.com) with [Jekyll](https://jekyllrb.com/) based on [jekyll-starter-tailwind](https://github.com/taylorbryant/jekyll-starter-tailwind). The documentation below is an excerpt from the originl's.

The starter kit includes:
* A barebones Jekyll starter theme
* A Gulpfile that does the following:

    * Compiles Tailwind
    * Strips out unused CSS using Tailwind's `purge` option
    * Runs [Autoprefixer](https://github.com/postcss/autoprefixer)
    * Minifies your CSS
    * Compiles Jekyll
    * Runs [Browsersync](https://www.browsersync.io/) for local development

## Requirements
* [Bundler](http://bundler.io/)
* [Jekyll](https://jekyllrb.com/)
* [Node.js](https://nodejs.org/en/)
* [npm](https://www.npmjs.com/)
* [Ruby](https://www.ruby-lang.org/en/)

## Get started
* `bundle install` to install Ruby gems
* `npm ci` to install npm packages listed in `package-lock.json`
* `npm run start` or `npm run dev` to compile the site with development settings and run BrowserSync

## Build your site
* `npm run build:dev` to compile the site with development settings
* `npm run build:production` or `npm run build` to compile the site for production


## Deploy
[![Netlify Status](https://api.netlify.com/api/v1/badges/374a7331-4924-4667-affe-33280701a30f/deploy-status)](https://app.netlify.com/sites/jekyll-tailwind-starter/deploys)

Note: By default, Netlify uses `jekyll build` as the build command. The included `netlify.toml` file will override it to use `npm run build`.

## License
[MIT](https://github.com/galearii/jekyll-tailwind-starter/blob/master/LICENSE.md)
