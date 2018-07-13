# tachyons 5.0.0-1

Functional CSS for humans

### Stats

655 | 80 | 80
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev tachyons
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/tachyons
```

ssh:
```
git clone git@github.com:tachyons-css/tachyons.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "tachyons";
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
<link rel="stylesheet" href="http://unpkg.com/tachyons@5.0.0-1/css/tachyons.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/tachyons">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/*!!!

# [ADDON] NUDGE

Nudge the position of an element by a pixel or two

### Docs

http://tachyons.io/docs/layout/nudge/

### Base

- nudge

### Modifiers

- t = top
- r = right
- b = bottom
- l = left

- `1`  = literal value 1px
- `2`  = literal value 2px
- `3`  = literal value 3px
- `4`  = literal value 4px
- `5`  = literal value 5px

### Media Query Extensions

- `-s` = small
- `-m` = medium
- `-l` = large
*/
.nudge-top-1 { top: 1px; }
.nudge-top-2 { top: 2px; }
.nudge-top-3 { top: 3px; }
.nudge-top-4 { top: 4px; }
.nudge-top-5 { top: 5px; }
.nudge-right-1 { right: 1px; }
.nudge-right-2 { right: 2px; }
.nudge-right-3 { right: 3px; }
.nudge-right-4 { right: 4px; }
.nudge-right-5 { right: 5px; }
.nudge-bottom-1 { bottom: 1px; }
.nudge-bottom-2 { bottom: 2px; }
.nudge-bottom-3 { bottom: 3px; }
.nudge-bottom-4 { bottom: 4px; }
.nudge-bottom-5 { bottom: 5px; }
.nudge-left-1 { left: 1px; }
.nudge-left-2 { left: 2px; }
.nudge-left-3 { left: 3px; }
.nudge-left-4 { left: 4px; }
.nudge-left-5 { left: 5px; }
@media screen and (min-width: 30em) {
 .nudge-top-1-s { top: 1px; }
 .nudge-top-2-s { top: 2px; }
 .nudge-top-3-s { top: 3px; }
 .nudge-top-4-s { top: 4px; }
 .nudge-top-5-s { top: 5px; }
 .nudge-right-1-s { right: 1px; }
 .nudge-right-2-s { right: 2px; }
 .nudge-right-3-s { right: 3px; }
 .nudge-right-4-s { right: 4px; }
 .nudge-right-5-s { right: 5px; }
 .nudge-bottom-1-s { bottom: 1px; }
 .nudge-bottom-2-s { bottom: 2px; }
 .nudge-bottom-3-s { bottom: 3px; }
 .nudge-bottom-4-s { bottom: 4px; }
 .nudge-bottom-5-s { bottom: 5px; }
 .nudge-left-1-s { left: 1px; }
 .nudge-left-2-s { left: 2px; }
 .nudge-left-3-s { left: 3px; }
 .nudge-left-4-s { left: 4px; }
 .nudge-left-5-s { left: 5px; }
}
@media screen and (min-width: 48em) {
 .nudge-top-1-m { top: 1px; }
 .nudge-top-2-m { top: 2px; }
 .nudge-top-3-m { top: 3px; }
 .nudge-top-4-m { top: 4px; }
 .nudge-top-5-m { top: 5px; }
 .nudge-right-1-m { right: 1px; }
 .nudge-right-2-m { right: 2px; }
 .nudge-right-3-m { right: 3px; }
 .nudge-right-4-m { right: 4px; }
 .nudge-right-5-m { right: 5px; }
 .nudge-bottom-1-m { bottom: 1px; }
 .nudge-bottom-2-m { bottom: 2px; }
 .nudge-bottom-3-m { bottom: 3px; }
 .nudge-bottom-4-m { bottom: 4px; }
 .nudge-bottom-5-m { bottom: 5px; }
 .nudge-left-1-m { left: 1px; }
 .nudge-left-2-m { left: 2px; }
 .nudge-left-3-m { left: 3px; }
 .nudge-left-4-m { left: 4px; }
 .nudge-left-5-m { left: 5px; }
}
@media screen and (min-width: 60em) {
 .nudge-top-1-l { top: 1px; }
 .nudge-top-2-l { top: 2px; }
 .nudge-top-3-l { top: 3px; }
 .nudge-top-4-l { top: 4px; }
 .nudge-top-5-l { top: 5px; }
 .nudge-right-1-l { right: 1px; }
 .nudge-right-2-l { right: 2px; }
 .nudge-right-3-l { right: 3px; }
 .nudge-right-4-l { right: 4px; }
 .nudge-right-5-l { right: 5px; }
 .nudge-bottom-1-l { bottom: 1px; }
 .nudge-bottom-2-l { bottom: 2px; }
 .nudge-bottom-3-l { bottom: 3px; }
 .nudge-bottom-4-l { bottom: 4px; }
 .nudge-bottom-5-l { bottom: 5px; }
 .nudge-left-1-l { left: 1px; }
 .nudge-left-2-l { left: 2px; }
 .nudge-left-3-l { left: 3px; }
 .nudge-left-4-l { left: 4px; }
 .nudge-left-5-l { left: 5px; }
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
