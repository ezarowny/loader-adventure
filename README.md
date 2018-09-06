# loader-adventure

This is a minimum reproducible test for:

https://github.com/webpack-contrib/mini-css-extract-plugin/issues/123

## Install

```
npm install
npm run build
```

On build, view index.html and inspect the h1, it should link to a stylesheet that is a concatenated file of all other stylesheets.
