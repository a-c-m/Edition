# Fork details

* Customizations for my personal blog [acmConsulting.eu](https://www.acmconsulting.eu)
* Removal of subscription features, loosely based on https://forum.ghost.org/t/ghost-4-0-really-terrible-for-personal-blog/20811/9
* Added a few social icons (hard coded), loosely based on https://ghost.org/docs/tutorials/adding-social-network-links/
* Moved socials to its own partial, for easy editing
* Added improved sharing options
* Added better table support for posts, based on https://forum.ghost.org/t/ghost-4-0-how-markdown-table-looks/20993
* Modified author block on posts


# Edition

The newsletter theme for [Ghost](http://github.com/tryghost/ghost/). This is the latest development version of Edition! If you're just looking to download the latest release, head over to the [releases](https://github.com/TryGhost/Edition/releases) page.

&nbsp;

# Development

Edition styles are compiled using Gulp/PostCSS to polyfill future CSS spec. You'll need [Node](https://nodejs.org/), [Yarn](https://yarnpkg.com/) and [Gulp](https://gulpjs.com) installed globally. After that, from the theme's root directory:

```bash
# Install
yarn

# Run build & watch for changes
$ yarn dev
```

Now you can edit `/assets/css/` files, which will be compiled to `/assets/built/` automatically.

The `zip` Gulp task packages the theme files into `dist/<theme-name>.zip`, which you can then upload to your site.

```bash
# create .zip file
yarn zip
```

# PostCSS Features Used

- Autoprefixer - Don't worry about writing browser prefixes of any kind, it's all done automatically with support for the latest 2 major versions of every browser.

# Copyright & License

Copyright (c) 2013-2021 Ghost Foundation - Released under the [MIT license](LICENSE).
