# Demo starter template (with Sass)

My starter template for larger demos on [my YouTube channel](https://youtube.com/kevinpowell) where I am using Sass.

## Development Scripts

**`npm start`**

> Will watch Sass files and hot reload using BrowserSync on localhost:3000

**`npm run build`**

> Production build includes minified, auto-prefixed CSS

## Using this template

Most theming and customization is handled in the `src/sass/abstracts` folder. 

### Colors

The `_colors.scss` file has a Sass map. You can add/remove/modify the colors there and a function will automatically output them as custom properties, as well as a full set of utility classes for both `color` and `background-color`.

### Type scale

The `_type.scss` contains a Sass map with type scales for different screen sizes. If you wish to add a new scale, the name of the screen size must match a size found in `_breakpoints.scss`.

