# Basic template with Eleventy, LiquidJS & CSS

## Folder structure

- pages in /src
- CSS files in /assets/css
- layouts in /_layouts
- includes in /_components
- Json files in /_data
- images & JavaScripts in /assets

## Page layout

- _layouts/base.liquid
- _components/header.liquid
- _components/nav.liquid
- _components/footer.liquid

## Responsive navbar

- responsive mobile menu with CSS without JavaScript from [LogRocket](https://blog.logrocket.com/create-responsive-mobile-menu-with-css-no-javascript/), without classes
- add tags: primary in frontmatter

## Package.json scripts

- "start": "npx @11ty/eleventy --serve",
- "build": "npx @11ty/eleventy --serveeleventy",
- "debug": "DEBUG=* eleventy"

## Dependencies

- "@11ty/eleventy": "^2.0.1"
- ready for [Decap CMS](https://decapcms.org/) integration.