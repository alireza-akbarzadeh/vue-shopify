# Vue Storefron Shopify Template

### Stay connected

[![GitHub Repo stars](https://img.shields.io/github/stars/vuestorefront/vue-storefront?style=social)](https://github.com/vuestorefront/vue-storefront)
[![Twitter Follow](https://img.shields.io/twitter/follow/vuestorefront?style=social)](https://twitter.com/vuestorefront)
[![YouTube Channel Subscribers](https://img.shields.io/youtube/channel/subscribers/UCkm1F3Cglty3CE1QwKQUhhg?style=social)](https://www.youtube.com/c/VueStorefront)
[![Discord](https://img.shields.io/discord/770285988244750366?label=join%20discord&logo=Discord&logoColor=white)](https://discord.vuestorefront.io)

Vue Storefront 2 template for Shopify.

## Setup

1. Create a `.env` inline with `middleware.config.js` file and fill the following required variables

```bash
SHOPIFY_STOREFRONT_TOKEN=<SHOPIFY_ACCESS_TOKEN>
SHOPIFY_DOMAIN=<SHOPIFY_DOMAIN> # example: vsf-next-pwa.myshopify.com
BASE_URL=<API_DOMAIN> # example: localhost:3001
```

2. Run the project

``` bash
# install dependencies
$ yarn install

# serve with hot reload at localhost:3000
$ yarn dev

# build for production and launch server
$ yarn build
$ yarn start

# generate static project
$ yarn generate
```

For detailed explanation on how things work, check out [Nuxt.js docs](https://nuxtjs.org) / [Vue Storefront Docs](https://docs.vuestorefront.io/v2/).

## Contributing

This repository is autogenerated. If you want to contribute to Shopify integration please use https://github.com/vuestorefront/shopify.