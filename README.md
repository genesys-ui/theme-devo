# Theme Devo

![license](https://img.shields.io/github/license/genesys-ui/theme-devo)
![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/genesys-ui/theme-devo/ci.yml)
[![npm version](https://img.shields.io/npm/v/@genesys-ui/theme-devo?label=%40genesys-ui%2Ftheme-devo)](https://www.npmjs.com/package/@genesys-ui/theme-devo)

_Devo_'s main brand schemes of design tokens defined by _Genesys Design System_.

This package contains the brand schemes as `json` files, required to generate
Devo's **light** and **dark** brands.

A preview of the generated tokens can be found in
[this page](https://genesys-ui.github.io/theme-devo/).

## Usage

```typescript
import { dark, light } from "@genesys-ui/theme-devo";

console.log(light.cmp.appBar);
console.log(dark.cmp.appBar);
```

## Quick start

To generate the brands from the available schemas, this project uses the `gyt`
CLI from [@genesys-ui/theme-generator](https://github.com/genesys-ui/theme-generator/tree/master/cli).
Please refer to the `gyt` package [documentation](https://github.com/genesys-ui/theme-generator/blob/master/cli/README.md)
for further information.

```sh
npm ci
npm run dist
```

The brands are now available in  the `dist/` folder.
