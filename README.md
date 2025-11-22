# Hugo sample project to demostrate issue with PurgeCSS

This repository demostrates an issue with how PurgeCSS works with the [Luna theme](https://github.com/Ice-Hazymoon/hugo-theme-luna/). See the [discussion on the Hugo Discourse here](https://discourse.gohugo.io/t/purgecss-ignores-layout-customizations/56274/).

## How to reproduce

- Clone the repository: `git clone https://github.com/scorchio/hugo-purgecss-sample.git`
- Get the git submodule of the theme:
- Get the theme dependencies
  - `cd themes/hugo-theme-luna`
  - `npm install`
- Start the hugo dev server: `hugo serve --disableFastRender`
- Open the about page: http://localhost:1313/about/
