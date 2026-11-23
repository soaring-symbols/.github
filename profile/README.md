<p align="center">
  <a href="https://soaringsymbols.org">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/soaring-symbols/brand/main/marks/logo-dark.svg">
      <img src="https://raw.githubusercontent.com/soaring-symbols/brand/main/marks/logo.svg" alt="Soaring Symbols" height="64">
    </picture>
  </a>
</p>

<p align="center">
  Airline logos, icons and tail designs in SVG, drawn to one set of rules, with brand colors and airline data.<br>
  For travelers, aviation enthusiasts, designers and developers.
</p>

<p align="center">
  <a href="https://soaringsymbols.org">Website</a> ·
  <a href="https://soaringsymbols.org/ecosystem">Ecosystem</a> ·
  <a href="https://github.com/soaring-symbols/soaring-symbols/blob/main/API.md">API</a> ·
  <a href="https://github.com/soaring-symbols/soaring-symbols/blob/main/CONTRIBUTING.md">Contributing</a>
</p>

<p align="center">
  <a href="https://www.npmjs.com/package/soaring-symbols"><img src="https://img.shields.io/npm/v/soaring-symbols?color=ffc20e&labelColor=1f242b" alt="npm version"></a>
  <a href="https://www.jsdelivr.com/package/npm/soaring-symbols"><img src="https://img.shields.io/jsdelivr/npm/hm/soaring-symbols?color=ffc20e&labelColor=1f242b" alt="jsDelivr hits"></a>
</p>

## What's here

- **Logos, icons and tails** for airlines around the world, with stacked lockups, monochrome versions in `currentColor` and versions for dark backgrounds.
- **Airline data**: IATA and ICAO codes, callsign, country, hubs, alliance, founding year and brand color, with renames, mergers and earlier logos kept.
- **Alliance marks** for oneworld, SkyTeam and Star Alliance.
- **A JSON and image API**, no key needed: [`/api/airlines/VN`](https://soaringsymbols.org/api/airlines/VN) for an airline's data, [`/api/airlines/VN/icon.png`](https://soaringsymbols.org/api/airlines/VN/icon.png) for a mark as SVG or PNG.

## Repositories

| Repository                                                                  | What it is                                                                                                  |
| :-------------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------------- |
| [soaring-symbols](https://github.com/soaring-symbols/soaring-symbols)       | The collection: SVGs, airline data and the JS API, published on [npm] and served by jsDelivr and unpkg      |
| [website](https://github.com/soaring-symbols/website)                       | [soaringsymbols.org](https://soaringsymbols.org): browse and download marks, validate SVGs, the API         |
| [raycast](https://github.com/soaring-symbols/raycast)                       | [Raycast extension](https://www.raycast.com/anhthang/soaring-symbols) to look airlines up and grab marks    |
| [figma](https://github.com/soaring-symbols/figma)                           | [Figma and FigJam plugin](https://www.figma.com/community/plugin/1701522206126108009) to drop marks in      |
| [drawio](https://github.com/soaring-symbols/drawio)                         | draw.io (diagrams.net) libraries, searchable by name or code                                                |
| [brand](https://github.com/soaring-symbols/brand)                           | The project's own mark: two split-flap tiles, like a departure board                                        |

## Quick start

```bash
npm install soaring-symbols
```

```js
import { getAirline, getAssetPath } from 'soaring-symbols'

getAirline('VN') // by IATA or ICAO code, slug or name
getAssetPath('VN', 'logo') // 'soaring-symbols/airlines/vietnam-airlines/logo.svg'
```

Or link a mark straight from the CDN, with nothing to install:

```text
https://cdn.jsdelivr.net/npm/soaring-symbols/dist/airlines/vietnam-airlines/logo.svg
```

## Contributing

Missing an airline, or spotted a mark that's out of date? Read the [contribution guidelines](https://github.com/soaring-symbols/soaring-symbols/blob/main/CONTRIBUTING.md), check your SVG on the [validate page](https://soaringsymbols.org/validate), and open a pull request.

---

<sub>The code and the airline data are MIT licensed. The logos, icons and tail designs belong to their airlines and alliances and are not covered by that license: read the <a href="https://github.com/soaring-symbols/soaring-symbols/blob/main/DISCLAIMER.md">disclaimer</a> before using them.</sub>

[npm]: https://www.npmjs.com/package/soaring-symbols
