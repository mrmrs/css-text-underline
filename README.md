# css-text-underline 0.0.6

Css module of single purpose classes for text underline

#### Stats

278 | 28 | 28
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-text-underline
```

#### With Git

```
git clone https://github.com/tachyons-css/css-text-underline
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-text-underline";
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
<link rel="stylesheet" href="path/to/module/css/css-text-underline">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   TEXT UNDERLINE
*/
.tup-auto { text-underline-position: auto; }
.tup-u { text-underline-position: under; }
.tup-l { text-underline-position: left; }
.tup-r { text-underline-position: right; }
.tup-ul { text-underline-position: under left; }
.tup-ru { text-underline-position: right under; }
.tup-i { text-underline-position: inherit; }
@media screen and (min-width: 48em) {
 .tup-auto-ns { text-underline-position: auto; }
 .tup-u-ns { text-underline-position: under; }
 .tup-l-ns { text-underline-position: left; }
 .tup-r-ns { text-underline-position: right; }
 .tup-ul-ns { text-underline-position: under left; }
 .tup-ru-ns { text-underline-position: right under; }
 .tup-i-ns { text-underline-position: inherit; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .tup-auto-m { text-underline-position: auto; }
 .tup-u-m { text-underline-position: under; }
 .tup-l-m { text-underline-position: left; }
 .tup-r-m { text-underline-position: right; }
 .tup-ul-m { text-underline-position: under left; }
 .tup-ru-m { text-underline-position: right under; }
 .tup-i-m { text-underline-position: inherit; }
}
@media screen and (min-width: 64em) {
 .tup-auto-l { text-underline-position: auto; }
 .tup-u-l { text-underline-position: under; }
 .tup-l-l { text-underline-position: left; }
 .tup-r-l { text-underline-position: right; }
 .tup-ul-l { text-underline-position: under left; }
 .tup-ru-l { text-underline-position: right under; }
 .tup-i-l { text-underline-position: inherit; }
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
