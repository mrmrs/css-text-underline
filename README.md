# css-text-underline

Functional CSS for text-underline

## Filesize

| File | Size |
|------|------|
| `dist/text-underline.css` | 1633 bytes |
| `dist/text-underline.min.css` | 1241 bytes (232 Gzipped) |

## Install

```sh
npm install css-text-underline
```

## Usage

### Import

```css
@import "css-text-underline";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-text-underline/dist/text-underline.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-text-underline/dist/text-underline.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.tup-auto` | `text-underline-position: auto;` |
| `.tup-u` | `text-underline-position: under;` |
| `.tup-l` | `text-underline-position: left;` |
| `.tup-r` | `text-underline-position: right;` |
| `.tup-ul` | `text-underline-position: under left;` |
| `.tup-ru` | `text-underline-position: right under;` |
| `.tup-i` | `text-underline-position: inherit;` |
| `.tup-auto-s` | `text-underline-position: auto;` |
| `.tup-u-s` | `text-underline-position: under;` |
| `.tup-l-s` | `text-underline-position: left;` |
| `.tup-r-s` | `text-underline-position: right;` |
| `.tup-ul-s` | `text-underline-position: under left;` |
| `.tup-ru-s` | `text-underline-position: right under;` |
| `.tup-i-s` | `text-underline-position: inherit;` |
| `.tup-auto-m` | `text-underline-position: auto;` |
| `.tup-u-m` | `text-underline-position: under;` |
| `.tup-l-m` | `text-underline-position: left;` |
| `.tup-r-m` | `text-underline-position: right;` |
| `.tup-ul-m` | `text-underline-position: under left;` |
| `.tup-ru-m` | `text-underline-position: right under;` |
| `.tup-i-m` | `text-underline-position: inherit;` |
| `.tup-auto-l` | `text-underline-position: auto;` |
| `.tup-u-l` | `text-underline-position: under;` |
| `.tup-l-l` | `text-underline-position: left;` |
| `.tup-r-l` | `text-underline-position: right;` |
| `.tup-ul-l` | `text-underline-position: under left;` |
| `.tup-ru-l` | `text-underline-position: right under;` |
| `.tup-i-l` | `text-underline-position: inherit;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.tup-auto-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/text-underline.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/text-underline.css` — formatted
- `dist/text-underline.min.css` — minified

## License

MIT
