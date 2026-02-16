# css-filter-blur

Functional CSS for filter-blur

## Filesize

| File | Size |
|------|------|
| `dist/filter-blur.css` | 5225 bytes |
| `dist/filter-blur.min.css` | 3753 bytes (473 Gzipped) |

## Install

```sh
npm install css-filter-blur
```

## Usage

### Import

```css
@import "css-filter-blur";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-filter-blur/dist/filter-blur.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-filter-blur/dist/filter-blur.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.blur0` | `filter: blur();` |
| `.blur1` | `filter: blur(1px);` |
| `.blur2` | `filter: blur(4px);` |
| `.blur3` | `filter: blur(8px);` |
| `.blur4` | `filter: blur(16px);` |
| `.blur5` | `filter: blur(32px);` |
| `.blur6` | `filter: blur(64px);` |
| `.blur7` | `filter: blur(96px);` |
| `.blur8` | `filter: blur(128px);` |
| `.blur0-s` | `filter: blur();` |
| `.blur1-s` | `filter: blur(1px);` |
| `.blur2-s` | `filter: blur(4px);` |
| `.blur3-s` | `filter: blur(8px);` |
| `.blur4-s` | `filter: blur(16px);` |
| `.blur5-s` | `filter: blur(32px);` |
| `.blur6-s` | `filter: blur(64px);` |
| `.blur7-s` | `filter: blur(96px);` |
| `.blur8-s` | `filter: blur(128px);` |
| `.blur0-m` | `filter: blur();` |
| `.blur1-m` | `filter: blur(1px);` |
| `.blur2-m` | `filter: blur(4px);` |
| `.blur3-m` | `filter: blur(8px);` |
| `.blur4-m` | `filter: blur(16px);` |
| `.blur5-m` | `filter: blur(32px);` |
| `.blur6-m` | `filter: blur(64px);` |
| `.blur7-m` | `filter: blur(96px);` |
| `.blur8-m` | `filter: blur(128px);` |
| `.blur0-l` | `filter: blur();` |
| `.blur1-l` | `filter: blur(1px);` |
| `.blur2-l` | `filter: blur(4px);` |
| `.blur3-l` | `filter: blur(8px);` |
| `.blur4-l` | `filter: blur(16px);` |
| `.blur5-l` | `filter: blur(32px);` |
| `.blur6-l` | `filter: blur(64px);` |
| `.blur7-l` | `filter: blur(96px);` |
| `.blur8-l` | `filter: blur(128px);` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.blur0-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/filter-blur.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/filter-blur.css` — formatted
- `dist/filter-blur.min.css` — minified

## License

MIT
