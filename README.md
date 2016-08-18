# css-filter-blur 0.0.7

Css module of single purpose classes for filter blur

#### Stats

213 | 20 | 20
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-filter-blur
```

#### With Git

```
git clone https://github.com/tachyons-css/css-filter-blur
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-filter-blur";
```

Then process the CSS using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons-cli path/to/css-file.css > dist/t.css
```

#### Using the CSS

The built CSS is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-filter-blur">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   FILTER BLUR
*/
.blur1 { filter: blur( 1px ); }
.blur2 { filter: blur( .125rem ); }
.blur3 { filter: blur( .25rem ); }
.blur4 { filter: blur( .5rem ); }
.blur5 { filter: blur( 1rem ); }
@media screen and (min-width: 48em) {
 .blur1-ns { filter: blur( 1px ); }
 .blur2-ns { filter: blur( .125rem ); }
 .blur3-ns { filter: blur( .25rem ); }
 .blur4-ns { filter: blur( .5rem ); }
 .blur5-ns { filter: blur( 1rem ); }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .blur1-m { filter: blur( 1px ); }
 .blur2-m { filter: blur( .125rem ); }
 .blur3-m { filter: blur( .25rem ); }
 .blur4-m { filter: blur( .5rem ); }
 .blur5-m { filter: blur( 1rem ); }
}
@media screen and (min-width: 64em) {
 .blur1-l { filter: blur( 1px ); }
 .blur2-l { filter: blur( .125rem ); }
 .blur3-l { filter: blur( .25rem ); }
 .blur4-l { filter: blur( .5rem ); }
 .blur5-l { filter: blur( 1rem ); }
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

ISC
