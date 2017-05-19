---
title: Configuration
description: The Nuxt.js default configuration covers most usages. However, the nuxt.config.js file lets you overwrite it.
---

> The Nuxt.js default configuration covers most usages. However, the nuxt.config.js file lets you overwrite it.

### build

This option lets you add modules inside the vendor.bundle.js file generated to reduce the size of the app bundle. It's really useful when using external modules.

[Documentation about build integration](/api/configuration-build)

### cache

This option lets you enable cached components for better render performances.

[Documentation about cache integration](/api/configuration-cache)

### css

This option lets you define the CSS files/modules/libraries you want to set as globals (included in every page).

[Documentation about css integration](/api/configuration-css)

### dev

This option lets you define the development or production mode of nuxt.js.

[Documentation about dev integration](/api/configuration-dev)

### env

This option lets you define environment variables available on both the client side and the server side.

[Documentation about env integration](/api/configuration-env)

### generate

This option lets you to define the parameters for each dynamic route in your application that Nuxt.js transforms into HTML files.

[Documentation about generate integration](/api/configuration-generate)

### head

This option lets you to define the default meta tags for your application.

[Documentation about head integration](/api/configuration-head)

### loading

This option lets you customize the loading component that Nuxt.js uses when loading routes.

[Documentation about loading integration](/api/configuration-loading)

### plugins

This option lets you define Javascript plugins for Nuxt.js to run before instantiating the root vue.js application.

[Documentation about plugins integration](/api/configuration-plugins)

### rootDir

This option lets you define the workspace of your Nuxt.js application.

[Documentation about rootDir integration](/api/configuration-rootdir)

### router

This option lets you overwrite the default Nuxt.js configuration of the vue-router.

[Documentation about router integration](/api/configuration-router)

### srcDir

This option lets you define the source directory of your Nuxt.js application.

[Documentation about srcDir integration](/api/configuration-srcdir)

### transition

This option lets you define the default properties of the pages transitions.

[Documentation about transition integration](/api/configuration-transition)
