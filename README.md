# OTR Ghost Theme

This is the Ghost theme for offtherailsradio.org. It is based on the stock Ghost theme Solo.

# Instructions

1. Download this theme
2. Log into Ghost, and go to the `Design` settings area to upload the zip file

# Development

Edition styles are compiled using Gulp/PostCSS to polyfill future CSS spec. You'll need [Node](https://nodejs.org/), [Yarn](https://yarnpkg.com/) and [Gulp](https://gulpjs.com) installed globally. After that, from the theme's root directory:

```bash
# Install
yarn

# Run build & watch for changes
yarn dev
```

Now you can edit `/assets/css/` files, which will be compiled to `/assets/built/` automatically.

The `zip` Gulp task packages the theme files into `dist/solo.zip`, which you can then upload to your site.

```bash
yarn zip
```

## Copyright & License

Copyright (c) 2013-2023 Ghost Foundation - Released under the [MIT license](LICENSE).