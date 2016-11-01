# css-filter-blur 1.0.6

Css module of single purpose classes for filter blur

#### Stats

246 | 20 | 40
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-filter-blur
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/css-filter-blur
```

ssh:
```
git clone git@github.com:tachyons-css/css-filter-blur.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-filter-blur";
```

Then process the css using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons path/to/css-file.css > dist/t.css
```

#### Using the css

##### CDN
The easiest and most simple way to use the css is to use the cdn hosted version. Include it in the head of your html with:

```
<link rel="stylesheet" href="http://unpkg.com/css-filter-blur@1.0.6/css/css-filter-blur.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-filter-blur">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/*
   FILTER BLUR
*/
.blur1 { -webkit-filter: blur( 1px ); filter: blur( 1px ); }
.blur2 { -webkit-filter: blur( .125rem ); filter: blur( .125rem ); }
.blur3 { -webkit-filter: blur( .25rem ); filter: blur( .25rem ); }
.blur4 { -webkit-filter: blur( .5rem ); filter: blur( .5rem ); }
.blur5 { -webkit-filter: blur( 1rem ); filter: blur( 1rem ); }
@media screen and (min-width: 48em) {
 .blur1-ns { -webkit-filter: blur( 1px ); filter: blur( 1px ); }
 .blur2-ns { -webkit-filter: blur( .125rem ); filter: blur( .125rem ); }
 .blur3-ns { -webkit-filter: blur( .25rem ); filter: blur( .25rem ); }
 .blur4-ns { -webkit-filter: blur( .5rem ); filter: blur( .5rem ); }
 .blur5-ns { -webkit-filter: blur( 1rem ); filter: blur( 1rem ); }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .blur1-m { -webkit-filter: blur( 1px ); filter: blur( 1px ); }
 .blur2-m { -webkit-filter: blur( .125rem ); filter: blur( .125rem ); }
 .blur3-m { -webkit-filter: blur( .25rem ); filter: blur( .25rem ); }
 .blur4-m { -webkit-filter: blur( .5rem ); filter: blur( .5rem ); }
 .blur5-m { -webkit-filter: blur( 1rem ); filter: blur( 1rem ); }
}
@media screen and (min-width: 64em) {
 .blur1-l { -webkit-filter: blur( 1px ); filter: blur( 1px ); }
 .blur2-l { -webkit-filter: blur( .125rem ); filter: blur( .125rem ); }
 .blur3-l { -webkit-filter: blur( .25rem ); filter: blur( .25rem ); }
 .blur4-l { -webkit-filter: blur( .5rem ); filter: blur( .5rem ); }
 .blur5-l { -webkit-filter: blur( 1rem ); filter: blur( 1rem ); }
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

