# Description

Utility classes for assigning background color or text color based on the TailwindCSS [color palette](https://tailwindcss.com/docs/customizing-colors/#default-color-palette).

# Demo

[https://tailwind-color-palette-demo.netlify.app/](https://tailwind-color-palette-demo.netlify.app/)

# Installation

1. Run `npm i tailwind-color-palette` or `yarn add tailwind-color-palette`.
2. Add `@import "~tailwind-color-palette/scss/tailwind-color-palette"` to any `.scss` file.

# Utility Class Structure

## Background Color Utility Class Structure

`.tw-bg-$tw_color_pallet-$tw_color_pallet_number`

### Example

`<div class="tw-bg-gray-100"></div>`

## Text Color Utility Class Structure

`.tw-text-$tw_color_pallet-$tw_color_pallet_number`

### Example

`<p class="tw-text-gray-100">Hello World!</p>`

Available `$tw_color_pallet` values:

- `gray`
- `red`
- `orange`
- `yellow`
- `green`
- `teal`
- `blue`
- `indigo`
- `purple`
- `pink`

Available `$tw_color_pallet_number` values:

- `100`
- `200`
- `300`
- `400`
- `500`
- `600`
- `700`
- `800`
- `900`

## Sass Maps

### Available Keys

- `$tw_gray`
- `$tw_red`
- `$tw_orange`
- `$tw_yellow`
- `$tw_green`
- `$tw_teal`
- `$tw_blue`
- `$tw_indigo`
- `$tw_purple`
- `$tw_pink`

### Available Values

- `100`
- `200`
- `300`
- `400`
- `500`
- `600`
- `700`
- `800`
- `900`

### Example

`map-get($tw_indigo, 900);`

# Extending Bootstrap

```scss
// some-file.scss
@import "~tailwind-color-palette/scss/tailwind-color-palette";
$primary: map-get($tw_indigo, 900);
@import "~bootstrap/scss/bootstrap";
```

# Development

1. `npm i` or `yarn`
2. `npm run sass` or `yarn run sass`
