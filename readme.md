# Neufork

----
## Neufork
Neufork is a fork of [Neumorph.scss](https://github.com/ChemaAlfonso/neumorph.scss/tree/master), providing a few extra features and a couple of small style tweaks.

> You can check out the list of changes [here](changes.md).

----
## what is Neumorph.scss?
Check out the Neufork [demo page](https://omer-sm.github.io/neumorph.scss/)

> Neumorph.scss is a bundle of bootstrap 4 styles integrated with neumorphism.scss clases to make a simple soft design.

----
## Getting started
Neumorphed.scss brings you a layer you can use between bootstrap and your styles.

You only need to **import one of the variations** stylesheets on your project or **compile your own** and start writting clases at html elements, like you usually do with bootstrap.

Alternatively, you may use [jsDeliver](https://cdn.jsdelivr.net/gh/omer-sm/neumorph.scss@master/dist/css/) to import without downloading:

```html
<!-- Dark (Full) -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/omer-sm/neumorph.scss@master/dist/css/dark/neumorph-full-dark.min.css">
<!-- Dark (Basic) -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/omer-sm/neumorph.scss@master/dist/css/dark/neumorph-dark.min.css">
<!-- Light (Full) -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/omer-sm/neumorph.scss@master/dist/css/light/neumorph-full.min.css">
<!-- Light (Basic) -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/omer-sm/neumorph.scss@master/dist/css/light/neumorph.min.css">
```

----
## Variations
Check **Dark and Light** themes and choose what you need, Neumorph.scss with bootstrap _utilities & grid only or with full bootstrap styles.

### Light themed
* neumorph.css
* neumorph.min.css
* neumorph-full.css
* neumorph-full.min.css

### Dark themed
* neumorph-dark.css
* neumorph-dark.min.css
* neumorph-dark-full.css
* neumorph-dark-full.min.css


## Custom styles
Check ./src/themes/np-theme.scss, you can edit theme vars to **set your own theme** vars, including colors, sizing, radius and transition time.

Then just run a compile command to get your own themed neumorph.

## Compile commands
Run following commands to compile your custom neumorph.scss version into ./dist/css/custom/.

##### Output
--

```sh
$ npm run sass-custom 
```
- **Output:** ./dist/css/custom/neumorph-custom.css

```sh
$ npm run sass-custom-min
```
- **Output:** ./dist/css/custom/neumorph-custom.min.css

You can import this file to your project and start working with it.

## ATENTION - Pre-release, use with caution.
There will probably be bugs.
