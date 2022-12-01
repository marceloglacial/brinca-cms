# Brinca CMS

Content Management System for [Brinca.ca](https://brinca.ca) based on [Stapi](https://strapi.io) and hosted on [Fly.io](https://fly.io).

## 🚀 Getting started

### `develop`

Start your Strapi application with autoReload enabled. [Learn more](https://docs.strapi.io/developer-docs/latest/developer-resources/cli/CLI.html#strapi-develop)

```shell
yarn develop
```

### `start`

Start your Strapi application with autoReload disabled. [Learn more](https://docs.strapi.io/developer-docs/latest/developer-resources/cli/CLI.html#strapi-start)

```shell
yarn start
```

### `build`

Build your admin panel. [Learn more](https://docs.strapi.io/developer-docs/latest/developer-resources/cli/CLI.html#strapi-build)

```shell
yarn build
```

## ⚙️ Deployment

Follow [Fly.io](https://documentation-git-fork-bogdaaamn-docs-fly-deplo-460c6b-strapijs.vercel.app/developer-docs/latest/setup-deployment-guides/deployment/hosting-guides/fly.html) instructions.

```shell
yarn deploy
```

## Secrets

Add you [ENV keys to Fly.io](https://fly.io/docs/reference/secrets/) using the following command:

```shell
flyctl secrets set SECRET_NAME=value
```

Check the changes on:

https://brinca-cms.fly.dev/admin/
