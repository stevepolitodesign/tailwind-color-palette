# Description

Utility classes for assigning background color or text color based on the TailwindCSS [color palette](https://tailwindcss.com/docs/customizing-colors/#default-color-palette).

# Installation

1. Run `npm i tailwind-color-palette` or `yarn add tailwind-color-palette`.
2. Add `@import "~tailwind-color-palette/scss/tailwind-color-palette"` to any `.scss` file.

# Utility Class Structure

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

## Background Color Utility Class Structure

`.tw-bg-$tw_color_pallet-$tw_color_pallet_number`

### Example

`<div class="tw-bg-gray-100 "></div>`;

## Text Color Utility Class Structure

`.tw-text-$tw_color_pallet-$tw_color_pallet_number`

### Example

`<p class="tw-text-gray-100">Hello World!</p>`;

# Development

1. `npm i` or `yarn`
2. `npm run sass` or `yarn run sass`
