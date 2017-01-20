# US Ignite Website

## Getting Started

1. `$ bundle install`
2. `$ jekyll serve`

## Rebuilding Tachyons

This site uses [Tachyons](http://tachyons.io) via [tachyons-custom](https://github.com/tachyons-css/tachyons-custom). Custom variables are defined in [css/tachyons.css](css/tachyons.css).

1. `$ npm install`
2. `$ npm run build`

## Using browser-sync

1. `$ npm install -g browser-sync`
2. While running `$ jekyll serve`:

    `$ browser-sync start --proxy "localhost:4000" --files "_site/index.html,css/*"`
