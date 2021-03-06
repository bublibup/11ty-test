---
subtitle: Haml
layout: layouts/langs.njk
---
| Eleventy Short Name | File Extension | NPM Package    |
| ------------------- | -------------- | -------------- |
| `haml`              | `.haml`        | [`haml.js`](c) |

You can override a `.haml` file’s template engine. Read more at [Changing a Template’s Rendering Engine](/docs/languages/).

## Set your own Library instance

_New in Eleventy `v0.3.0`:_ As an escape mechanism for advanced usage, pass in your own instance of the HAML library using the Configuration API.

```js
module.exports = function(eleventyConfig) {
  let haml = require("hamljs");
  eleventyConfig.setLibrary("haml", haml);
};
```

## Supported Features

| Feature                                                                             | Syntax                                                                 |
| ----------------------------------------------------------------------------------- | ---------------------------------------------------------------------- |
| 🚫 _TODO_ Filters                                                                   | `:filterName some text` Read more about [Filters](/docs/filters/).                                                |
| 🚫 _TODO_ [Eleventy Universal Filters](/docs/filters/#universal-filters) | `:filterName some text` Read more about [Filters](/docs/filters/). |
