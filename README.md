# Figsvelte
A boilerplate for creating Figma plugins using Svelte.

This starter project has everything you need to start developing a Figma plugin usign Svelte. Your JS, CSS, SVG and image assets can be bundled on build. The package will take care of compiling your typescript + app on save during development, and also minify on build. 

Additionally, this package comes preconfigured with [Figma Plugin DS Svelte](https://github.com/thomas-lowry/figma-plugin-ds-svelte) where you have access to a large range of components and icons that match the Figma UI, to get you up and running quickly. Note: installing this boilerplate will install the component library as a dependency.

Any components, icons or CSS that you don't use won't be included in your final build.


## To get started
```bash
npx degit thomas-lowry/figsvelte figma-plugin
cd figma-plugin
npm install
```

_Note that you will need to have [Node.js](https://nodejs.org/) installed._

## Development
During development, watch your project for changes with the following command.

```bash
npm run dev
```

_Livereload will be enabled for scaffolding out your UI locally, but you will still need to refresh your plugin when testing in Figma._

## Build
When ready to package up your final Figma Plugin:
```bash
npm run build
```
