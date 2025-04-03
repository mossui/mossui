# Moss UI - Colors

A comprehensive CSS color palette library with semantic naming and easy-to-use CSS variables.

[![NPM Version](https://img.shields.io/npm/v/@mossui/colors?color=blue)](https://www.npmjs.com/package/@mossui/colors)
[![jsDelivr CDN](https://data.jsdelivr.com/v1/package/npm/@mossui/colors/badge)](https://www.jsdelivr.com/package/npm/@mossui/colors)

## Features

- 🎨 18 color families
- 🖌️ CSS variables for easy theming
- 📦 Lightweight (~6KB minified)
- 🌍 Available via NPM and CDN
- 🏗️ Framework agnostic

## Installation

### NPM

```bash
# npm
npm i @mossui/colors
```

Then import in your CSS:

```css
@import '@mossui/colors';
```

### CDN

```html
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/npm/@mossui/colors/dist/colors.min.css"
/>
```

### Usage

```html
<h1>Hello World</h1>
```

```css
h1 {
  color: var(--color-red-500)
}
```

### Color pallete

Moss UI provides a complete color system with 18 color families:

| Variable | Value | Color Preview |
|----------|-------|---------------|
| `--color-white` | `#fff` | ![#fff](https://placehold.co/15x15/fff/fff.webp) |
| `--color-black` | `#000` | ![#000](https://placehold.co/15x15/000/000.webp) |
| `--color-red-50` | `#fff` | ![#fff](https://placehold.co/15x15/fff/fff.webp) |
| `--color-red-100` | `#fedcde` | ![#fedcde](https://placehold.co/15x15/fedcde/fedcde.webp) |
| `--color-red-200` | `#fdaaae` | ![#fdaaae](https://placehold.co/15x15/fdaaae/fdaaae.webp) |
| `--color-red-300` | `#fc787f` | ![#fc787f](https://placehold.co/15x15/fc787f/fc787f.webp) |
| `--color-red-400` | `#fb464f` | ![#fb464f](https://placehold.co/15x15/fb464f/fb464f.webp) |
| `--color-red-500` | `#fb2d38` | ![#fb2d38](https://placehold.co/15x15/fb2d38/fb2d38.webp) |
| `--color-red-600` | `#f00511` | ![#f00511](https://placehold.co/15x15/f00511/f00511.webp) |
| `--color-red-700` | `#be040d` | ![#be040d](https://placehold.co/15x15/be040d/be040d.webp) |
| `--color-red-800` | `#8c030a` | ![#8c030a](https://placehold.co/15x15/8c030a/8c030a.webp) |
| `--color-red-900` | `#5a0206` | ![#5a0206](https://placehold.co/15x15/5a0206/5a0206.webp) |
| `--color-red-950` | `#410105` | ![#410105](https://placehold.co/15x15/410105/410105.webp) |
| `--color-red` | `#fb2d38` | ![#fb2d38](https://placehold.co/15x15/fb2d38/fb2d38.webp) |
| `--color-orange-50` | `#fff0e6` | ![#fff0e6](https://placehold.co/15x15/fff0e6/fff0e6.webp) |
| `--color-orange-100` | `#ffd2b3` | ![#ffd2b3](https://placehold.co/15x15/ffd2b3/ffd2b3.webp) |
| `--color-orange-200` | `#ffb480` | ![#ffb480](https://placehold.co/15x15/ffb480/ffb480.webp) |
| `--color-orange-300` | `#ff964d` | ![#ff964d](https://placehold.co/15x15/ff964d/ff964d.webp) |
| `--color-orange-400` | `#ff781a` | ![#ff781a](https://placehold.co/15x15/ff781a/ff781a.webp) |
| `--color-orange-500` | `#ff6900` | ![#ff6900](https://placehold.co/15x15/ff6900/ff6900.webp) |
| `--color-orange-600` | `#cc5400` | ![#cc5400](https://placehold.co/15x15/cc5400/cc5400.webp) |
| `--color-orange-700` | `#993f00` | ![#993f00](https://placehold.co/15x15/993f00/993f00.webp) |
| `--color-orange-800` | `#662a00` | ![#662a00](https://placehold.co/15x15/662a00/662a00.webp) |
| `--color-orange-900` | `#331500` | ![#331500](https://placehold.co/15x15/331500/331500.webp) |
| `--color-orange-950` | `#1a0a00` | ![#1a0a00](https://placehold.co/15x15/1a0a00/1a0a00.webp) |
| `--color-orange` | `#ff6900` | ![#ff6900](https://placehold.co/15x15/ff6900/ff6900.webp) |
| `--color-amber-50` | `#fff5e6` | ![#fff5e6](https://placehold.co/15x15/fff5e6/fff5e6.webp) |
| `--color-amber-100` | `#ffe1b3` | ![#ffe1b3](https://placehold.co/15x15/ffe1b3/ffe1b3.webp) |
| `--color-amber-200` | `#ffcd80` | ![#ffcd80](https://placehold.co/15x15/ffcd80/ffcd80.webp) |
| `--color-amber-300` | `#ffb94d` | ![#ffb94d](https://placehold.co/15x15/ffb94d/ffb94d.webp) |
| `--color-amber-400` | `#ffa51a` | ![#ffa51a](https://placehold.co/15x15/ffa51a/ffa51a.webp) |
| `--color-amber-500` | `#ff9b00` | ![#ff9b00](https://placehold.co/15x15/ff9b00/ff9b00.webp) |
| `--color-amber-600` | `#cc7c00` | ![#cc7c00](https://placehold.co/15x15/cc7c00/cc7c00.webp) |
| `--color-amber-700` | `#995d00` | ![#995d00](https://placehold.co/15x15/995d00/995d00.webp) |
| `--color-amber-800` | `#663e00` | ![#663e00](https://placehold.co/15x15/663e00/663e00.webp) |
| `--color-amber-900` | `#331f00` | ![#331f00](https://placehold.co/15x15/331f00/331f00.webp) |
| `--color-amber-950` | `#1a1000` | ![#1a1000](https://placehold.co/15x15/1a1000/1a1000.webp) |
| `--color-amber` | `#ff9b00` | ![#ff9b00](https://placehold.co/15x15/ff9b00/ff9b00.webp) |
| `--color-yellow-50` | `#fff4d6` | ![#fff4d6](https://placehold.co/15x15/fff4d6/fff4d6.webp) |
| `--color-yellow-100` | `#ffe7a3` | ![#ffe7a3](https://placehold.co/15x15/ffe7a3/ffe7a3.webp) |
| `--color-yellow-200` | `#ffda70` | ![#ffda70](https://placehold.co/15x15/ffda70/ffda70.webp) |
| `--color-yellow-300` | `#ffcd3d` | ![#ffcd3d](https://placehold.co/15x15/ffcd3d/ffcd3d.webp) |
| `--color-yellow-400` | `#ffbf0a` | ![#ffbf0a](https://placehold.co/15x15/ffbf0a/ffbf0a.webp) |
| `--color-yellow-500` | `#f0b100` | ![#f0b100](https://placehold.co/15x15/f0b100/f0b100.webp) |
| `--color-yellow-600` | `#bd8c00` | ![#bd8c00](https://placehold.co/15x15/bd8c00/bd8c00.webp) |
| `--color-yellow-700` | `#8a6600` | ![#8a6600](https://placehold.co/15x15/8a6600/8a6600.webp) |
| `--color-yellow-800` | `#574000` | ![#574000](https://placehold.co/15x15/574000/574000.webp) |
| `--color-yellow-900` | `#241a00` | ![#241a00](https://placehold.co/15x15/241a00/241a00.webp) |
| `--color-yellow-950` | `#0a0800` | ![#0a0800](https://placehold.co/15x15/0a0800/0a0800.webp) |
| `--color-yellow` | `#f0b100` | ![#f0b100](https://placehold.co/15x15/f0b100/f0b100.webp) |
| `--color-lime-50` | `#e1ffb3` | ![#e1ffb3](https://placehold.co/15x15/e1ffb3/e1ffb3.webp) |
| `--color-lime-100` | `#ccff80` | ![#ccff80](https://placehold.co/15x15/ccff80/ccff80.webp) |
| `--color-lime-200` | `#b8ff4d` | ![#b8ff4d](https://placehold.co/15x15/b8ff4d/b8ff4d.webp) |
| `--color-lime-300` | `#a4ff1a` | ![#a4ff1a](https://placehold.co/15x15/a4ff1a/a4ff1a.webp) |
| `--color-lime-400` | `#8ae600` | ![#8ae600](https://placehold.co/15x15/8ae600/8ae600.webp) |
| `--color-lime-500` | `#7bcc00` | ![#7bcc00](https://placehold.co/15x15/7bcc00/7bcc00.webp) |
| `--color-lime-600` | `#5c9900` | ![#5c9900](https://placehold.co/15x15/5c9900/5c9900.webp) |
| `--color-lime-700` | `#3d6600` | ![#3d6600](https://placehold.co/15x15/3d6600/3d6600.webp) |
| `--color-lime-800` | `#1f3300` | ![#1f3300](https://placehold.co/15x15/1f3300/1f3300.webp) |
| `--color-lime-900` | `#000` | ![#000](https://placehold.co/15x15/000/000.webp) |
| `--color-lime-950` | `#000` | ![#000](https://placehold.co/15x15/000/000.webp) |
| `--color-lime` | `#7bcc00` | ![#7bcc00](https://placehold.co/15x15/7bcc00/7bcc00.webp) |
| `--color-green-50` | `#adffce` | ![#adffce](https://placehold.co/15x15/adffce/adffce.webp) |
| `--color-green-100` | `#7affb0` | ![#7affb0](https://placehold.co/15x15/7affb0/7affb0.webp) |
| `--color-green-200` | `#47ff91` | ![#47ff91](https://placehold.co/15x15/47ff91/47ff91.webp) |
| `--color-green-300` | `#14ff73` | ![#14ff73](https://placehold.co/15x15/14ff73/14ff73.webp) |
| `--color-green-400` | `#00e05a` | ![#00e05a](https://placehold.co/15x15/00e05a/00e05a.webp) |
| `--color-green-500` | `#00c750` | ![#00c750](https://placehold.co/15x15/00c750/00c750.webp) |
| `--color-green-600` | `#00943b` | ![#00943b](https://placehold.co/15x15/00943b/00943b.webp) |
| `--color-green-700` | `#006127` | ![#006127](https://placehold.co/15x15/006127/006127.webp) |
| `--color-green-800` | `#002e12` | ![#002e12](https://placehold.co/15x15/002e12/002e12.webp) |
| `--color-green-900` | `#000` | ![#000](https://placehold.co/15x15/000/000.webp) |
| `--color-green-950` | `#000` | ![#000](https://placehold.co/15x15/000/000.webp) |
| `--color-green` | `#00c750` | ![#00c750](https://placehold.co/15x15/00c750/00c750.webp) |
| `--color-emerald-50` | `#a3ffe0` | ![#a3ffe0](https://placehold.co/15x15/a3ffe0/a3ffe0.webp) |
| `--color-emerald-100` | `#70ffcf` | ![#70ffcf](https://placehold.co/15x15/70ffcf/70ffcf.webp) |
| `--color-emerald-200` | `#3dffbe` | ![#3dffbe](https://placehold.co/15x15/3dffbe/3dffbe.webp) |
| `--color-emerald-300` | `#0affac` | ![#0affac](https://placehold.co/15x15/0affac/0affac.webp) |
| `--color-emerald-400` | `#00d68e` | ![#00d68e](https://placehold.co/15x15/00d68e/00d68e.webp) |
| `--color-emerald-500` | `#00bd7d` | ![#00bd7d](https://placehold.co/15x15/00bd7d/00bd7d.webp) |
| `--color-emerald-600` | `#008a5b` | ![#008a5b](https://placehold.co/15x15/008a5b/008a5b.webp) |
| `--color-emerald-700` | `#005739` | ![#005739](https://placehold.co/15x15/005739/005739.webp) |
| `--color-emerald-800` | `#002418` | ![#002418](https://placehold.co/15x15/002418/002418.webp) |
| `--color-emerald-900` | `#000` | ![#000](https://placehold.co/15x15/000/000.webp) |
| `--color-emerald-950` | `#000` | ![#000](https://placehold.co/15x15/000/000.webp) |
| `--color-emerald` | `#00bd7d` | ![#00bd7d](https://placehold.co/15x15/00bd7d/00bd7d.webp) |
| `--color-teal-50` | `#a3fff5` | ![#a3fff5](https://placehold.co/15x15/a3fff5/a3fff5.webp) |
| `--color-teal-100` | `#70fff0` | ![#70fff0](https://placehold.co/15x15/70fff0/70fff0.webp) |
| `--color-teal-200` | `#3dffea` | ![#3dffea](https://placehold.co/15x15/3dffea/3dffea.webp) |
| `--color-teal-300` | `#0affe5` | ![#0affe5](https://placehold.co/15x15/0affe5/0affe5.webp) |
| `--color-teal-400` | `#00d6bf` | ![#00d6bf](https://placehold.co/15x15/00d6bf/00d6bf.webp) |
| `--color-teal-500` | `#00bda9` | ![#00bda9](https://placehold.co/15x15/00bda9/00bda9.webp) |
| `--color-teal-600` | `#008a7b` | ![#008a7b](https://placehold.co/15x15/008a7b/008a7b.webp) |
| `--color-teal-700` | `#00574d` | ![#00574d](https://placehold.co/15x15/00574d/00574d.webp) |
| `--color-teal-800` | `#002420` | ![#002420](https://placehold.co/15x15/002420/002420.webp) |
| `--color-teal-900` | `#000` | ![#000](https://placehold.co/15x15/000/000.webp) |
| `--color-teal-950` | `#000` | ![#000](https://placehold.co/15x15/000/000.webp) |
| `--color-teal` | `#00bda9` | ![#00bda9](https://placehold.co/15x15/00bda9/00bda9.webp) |
| `--color-cyan-50` | `#c2f5ff` | ![#c2f5ff](https://placehold.co/15x15/c2f5ff/c2f5ff.webp) |
| `--color-cyan-100` | `#8fedff` | ![#8fedff](https://placehold.co/15x15/8fedff/8fedff.webp) |
| `--color-cyan-200` | `#5ce5ff` | ![#5ce5ff](https://placehold.co/15x15/5ce5ff/5ce5ff.webp) |
| `--color-cyan-300` | `#29ddff` | ![#29ddff](https://placehold.co/15x15/29ddff/29ddff.webp) |
| `--color-cyan-400` | `#00cef5` | ![#00cef5](https://placehold.co/15x15/00cef5/00cef5.webp) |
| `--color-cyan-500` | `#00b9db` | ![#00b9db](https://placehold.co/15x15/00b9db/00b9db.webp) |
| `--color-cyan-600` | `#008ea8` | ![#008ea8](https://placehold.co/15x15/008ea8/008ea8.webp) |
| `--color-cyan-700` | `#006375` | ![#006375](https://placehold.co/15x15/006375/006375.webp) |
| `--color-cyan-800` | `#003842` | ![#003842](https://placehold.co/15x15/003842/003842.webp) |
| `--color-cyan-900` | `#000d0f` | ![#000d0f](https://placehold.co/15x15/000d0f/000d0f.webp) |
| `--color-cyan-950` | `#000` | ![#000](https://placehold.co/15x15/000/000.webp) |
| `--color-cyan` | `#00b9db` | ![#00b9db](https://placehold.co/15x15/00b9db/00b9db.webp) |
| `--color-sky-50` | `#dbf4ff` | ![#dbf4ff](https://placehold.co/15x15/dbf4ff/dbf4ff.webp) |
| `--color-sky-100` | `#a8e3ff` | ![#a8e3ff](https://placehold.co/15x15/a8e3ff/a8e3ff.webp) |
| `--color-sky-200` | `#75d3ff` | ![#75d3ff](https://placehold.co/15x15/75d3ff/75d3ff.webp) |
| `--color-sky-300` | `#42c2ff` | ![#42c2ff](https://placehold.co/15x15/42c2ff/42c2ff.webp) |
| `--color-sky-400` | `#0fb2ff` | ![#0fb2ff](https://placehold.co/15x15/0fb2ff/0fb2ff.webp) |
| `--color-sky-500` | `#00a6f5` | ![#00a6f5](https://placehold.co/15x15/00a6f5/00a6f5.webp) |
| `--color-sky-600` | `#0084c2` | ![#0084c2](https://placehold.co/15x15/0084c2/0084c2.webp) |
| `--color-sky-700` | `#00618f` | ![#00618f](https://placehold.co/15x15/00618f/00618f.webp) |
| `--color-sky-800` | `#003e5c` | ![#003e5c](https://placehold.co/15x15/003e5c/003e5c.webp) |
| `--color-sky-900` | `#001c29` | ![#001c29](https://placehold.co/15x15/001c29/001c29.webp) |
| `--color-sky-950` | `#000a0f` | ![#000a0f](https://placehold.co/15x15/000a0f/000a0f.webp) |
| `--color-sky` | `#00a6f5` | ![#00a6f5](https://placehold.co/15x15/00a6f5/00a6f5.webp) |
| `--color-blue-50` | `#fff` | ![#fff](https://placehold.co/15x15/fff/fff.webp) |
| `--color-blue-100` | `#dbe9ff` | ![#dbe9ff](https://placehold.co/15x15/dbe9ff/dbe9ff.webp) |
| `--color-blue-200` | `#a8cbff` | ![#a8cbff](https://placehold.co/15x15/a8cbff/a8cbff.webp) |
| `--color-blue-300` | `#75acff` | ![#75acff](https://placehold.co/15x15/75acff/75acff.webp) |
| `--color-blue-400` | `#428dff` | ![#428dff](https://placehold.co/15x15/428dff/428dff.webp) |
| `--color-blue-500` | `#297eff` | ![#297eff](https://placehold.co/15x15/297eff/297eff.webp) |
| `--color-blue-600` | `#0061f5` | ![#0061f5](https://placehold.co/15x15/0061f5/0061f5.webp) |
| `--color-blue-700` | `#004dc2` | ![#004dc2](https://placehold.co/15x15/004dc2/004dc2.webp) |
| `--color-blue-800` | `#00398f` | ![#00398f](https://placehold.co/15x15/00398f/00398f.webp) |
| `--color-blue-900` | `#00245c` | ![#00245c](https://placehold.co/15x15/00245c/00245c.webp) |
| `--color-blue-950` | `#001a42` | ![#001a42](https://placehold.co/15x15/001a42/001a42.webp) |
| `--color-blue` | `#297eff` | ![#297eff](https://placehold.co/15x15/297eff/297eff.webp) |
| `--color-indigo-50` | `#fff` | ![#fff](https://placehold.co/15x15/fff/fff.webp) |
| `--color-indigo-100` | `#fff` | ![#fff](https://placehold.co/15x15/fff/fff.webp) |
| `--color-indigo-200` | `#e1e0ff` | ![#e1e0ff](https://placehold.co/15x15/e1e0ff/e1e0ff.webp) |
| `--color-indigo-300` | `#afadff` | ![#afadff](https://placehold.co/15x15/afadff/afadff.webp) |
| `--color-indigo-400` | `#7d7aff` | ![#7d7aff](https://placehold.co/15x15/7d7aff/7d7aff.webp) |
| `--color-indigo-500` | `#6361ff` | ![#6361ff](https://placehold.co/15x15/6361ff/6361ff.webp) |
| `--color-indigo-600` | `#312eff` | ![#312eff](https://placehold.co/15x15/312eff/312eff.webp) |
| `--color-indigo-700` | `#0400fa` | ![#0400fa](https://placehold.co/15x15/0400fa/0400fa.webp) |
| `--color-indigo-800` | `#0300c7` | ![#0300c7](https://placehold.co/15x15/0300c7/0300c7.webp) |
| `--color-indigo-900` | `#020094` | ![#020094](https://placehold.co/15x15/020094/020094.webp) |
| `--color-indigo-950` | `#02007a` | ![#02007a](https://placehold.co/15x15/02007a/02007a.webp) |
| `--color-indigo` | `#6361ff` | ![#6361ff](https://placehold.co/15x15/6361ff/6361ff.webp) |
| `--color-violet-50` | `#fff` | ![#fff](https://placehold.co/15x15/fff/fff.webp) |
| `--color-violet-100` | `#fff` | ![#fff](https://placehold.co/15x15/fff/fff.webp) |
| `--color-violet-200` | `#e1d1ff` | ![#e1d1ff](https://placehold.co/15x15/e1d1ff/e1d1ff.webp) |
| `--color-violet-300` | `#c09eff` | ![#c09eff](https://placehold.co/15x15/c09eff/c09eff.webp) |
| `--color-violet-400` | `#9f6bff` | ![#9f6bff](https://placehold.co/15x15/9f6bff/9f6bff.webp) |
| `--color-violet-500` | `#8e52ff` | ![#8e52ff](https://placehold.co/15x15/8e52ff/8e52ff.webp) |
| `--color-violet-600` | `#6d1fff` | ![#6d1fff](https://placehold.co/15x15/6d1fff/6d1fff.webp) |
| `--color-violet-700` | `#5200eb` | ![#5200eb](https://placehold.co/15x15/5200eb/5200eb.webp) |
| `--color-violet-800` | `#4000b8` | ![#4000b8](https://placehold.co/15x15/4000b8/4000b8.webp) |
| `--color-violet-900` | `#2e0085` | ![#2e0085](https://placehold.co/15x15/2e0085/2e0085.webp) |
| `--color-violet-950` | `#25006b` | ![#25006b](https://placehold.co/15x15/25006b/25006b.webp) |
| `--color-violet` | `#8e52ff` | ![#8e52ff](https://placehold.co/15x15/8e52ff/8e52ff.webp) |
| `--color-purple-50` | `#fff` | ![#fff](https://placehold.co/15x15/fff/fff.webp) |
| `--color-purple-100` | `#fdfaff` | ![#fdfaff](https://placehold.co/15x15/fdfaff/fdfaff.webp) |
| `--color-purple-200` | `#e6c7ff` | ![#e6c7ff](https://placehold.co/15x15/e6c7ff/e6c7ff.webp) |
| `--color-purple-300` | `#cf94ff` | ![#cf94ff](https://placehold.co/15x15/cf94ff/cf94ff.webp) |
| `--color-purple-400` | `#b961ff` | ![#b961ff](https://placehold.co/15x15/b961ff/b961ff.webp) |
| `--color-purple-500` | `#ad47ff` | ![#ad47ff](https://placehold.co/15x15/ad47ff/ad47ff.webp) |
| `--color-purple-600` | `#9714ff` | ![#9714ff](https://placehold.co/15x15/9714ff/9714ff.webp) |
| `--color-purple-700` | `#7d00e0` | ![#7d00e0](https://placehold.co/15x15/7d00e0/7d00e0.webp) |
| `--color-purple-800` | `#6000ad` | ![#6000ad](https://placehold.co/15x15/6000ad/6000ad.webp) |
| `--color-purple-900` | `#44007a` | ![#44007a](https://placehold.co/15x15/44007a/44007a.webp) |
| `--color-purple-950` | `#360061` | ![#360061](https://placehold.co/15x15/360061/360061.webp) |
| `--color-purple` | `#ad47ff` | ![#ad47ff](https://placehold.co/15x15/ad47ff/ad47ff.webp) |
| `--color-fuchsia-50` | `#fff` | ![#fff](https://placehold.co/15x15/fff/fff.webp) |
| `--color-fuchsia-100` | `#fadcfe` | ![#fadcfe](https://placehold.co/15x15/fadcfe/fadcfe.webp) |
| `--color-fuchsia-200` | `#f3aafd` | ![#f3aafd](https://placehold.co/15x15/f3aafd/f3aafd.webp) |
| `--color-fuchsia-300` | `#ec78fc` | ![#ec78fc](https://placehold.co/15x15/ec78fc/ec78fc.webp) |
| `--color-fuchsia-400` | `#e546fb` | ![#e546fb](https://placehold.co/15x15/e546fb/e546fb.webp) |
| `--color-fuchsia-500` | `#e12dfb` | ![#e12dfb](https://placehold.co/15x15/e12dfb/e12dfb.webp) |
| `--color-fuchsia-600` | `#d305f0` | ![#d305f0](https://placehold.co/15x15/d305f0/d305f0.webp) |
| `--color-fuchsia-700` | `#a704be` | ![#a704be](https://placehold.co/15x15/a704be/a704be.webp) |
| `--color-fuchsia-800` | `#7b038c` | ![#7b038c](https://placehold.co/15x15/7b038c/7b038c.webp) |
| `--color-fuchsia-900` | `#4f025a` | ![#4f025a](https://placehold.co/15x15/4f025a/4f025a.webp) |
| `--color-fuchsia-950` | `#390141` | ![#390141](https://placehold.co/15x15/390141/390141.webp) |
| `--color-fuchsia` | `#e12dfb` | ![#e12dfb](https://placehold.co/15x15/e12dfb/e12dfb.webp) |
| `--color-pink-50` | `#fff` | ![#fff](https://placehold.co/15x15/fff/fff.webp) |
| `--color-pink-100` | `#feddee` | ![#feddee](https://placehold.co/15x15/feddee/feddee.webp) |
| `--color-pink-200` | `#fcacd6` | ![#fcacd6](https://placehold.co/15x15/fcacd6/fcacd6.webp) |
| `--color-pink-300` | `#f97abe` | ![#f97abe](https://placehold.co/15x15/f97abe/f97abe.webp) |
| `--color-pink-400` | `#f74aa6` | ![#f74aa6](https://placehold.co/15x15/f74aa6/f74aa6.webp) |
| `--color-pink-500` | `#f6319a` | ![#f6319a](https://placehold.co/15x15/f6319a/f6319a.webp) |
| `--color-pink-600` | `#eb0a81` | ![#eb0a81](https://placehold.co/15x15/eb0a81/eb0a81.webp) |
| `--color-pink-700` | `#ba0866` | ![#ba0866](https://placehold.co/15x15/ba0866/ba0866.webp) |
| `--color-pink-800` | `#89064b` | ![#89064b](https://placehold.co/15x15/89064b/89064b.webp) |
| `--color-pink-900` | `#580430` | ![#580430](https://placehold.co/15x15/580430/580430.webp) |
| `--color-pink-950` | `#400323` | ![#400323](https://placehold.co/15x15/400323/400323.webp) |
| `--color-pink` | `#f6319a` | ![#f6319a](https://placehold.co/15x15/f6319a/f6319a.webp) |
| `--color-rose-50` | `#fff` | ![#fff](https://placehold.co/15x15/fff/fff.webp) |
| `--color-rose-100` | `#ffd1dc` | ![#ffd1dc](https://placehold.co/15x15/ffd1dc/ffd1dc.webp) |
| `--color-rose-200` | `#ff9eb6` | ![#ff9eb6](https://placehold.co/15x15/ff9eb6/ff9eb6.webp) |
| `--color-rose-300` | `#ff6b8f` | ![#ff6b8f](https://placehold.co/15x15/ff6b8f/ff6b8f.webp) |
| `--color-rose-400` | `#ff3869` | ![#ff3869](https://placehold.co/15x15/ff3869/ff3869.webp) |
| `--color-rose-500` | `#ff1f56` | ![#ff1f56](https://placehold.co/15x15/ff1f56/ff1f56.webp) |
| `--color-rose-600` | `#eb0039` | ![#eb0039](https://placehold.co/15x15/eb0039/eb0039.webp) |
| `--color-rose-700` | `#b8002d` | ![#b8002d](https://placehold.co/15x15/b8002d/b8002d.webp) |
| `--color-rose-800` | `#850020` | ![#850020](https://placehold.co/15x15/850020/850020.webp) |
| `--color-rose-900` | `#520014` | ![#520014](https://placehold.co/15x15/520014/520014.webp) |
| `--color-rose-950` | `#38000e` | ![#38000e](https://placehold.co/15x15/38000e/38000e.webp) |
| `--color-rose` | `#ff1f56` | ![#ff1f56](https://placehold.co/15x15/ff1f56/ff1f56.webp) |
| `--color-slate-50` | `#e7eaee` | ![#e7eaee](https://placehold.co/15x15/e7eaee/e7eaee.webp) |
| `--color-slate-100` | `#c9d0d9` | ![#c9d0d9](https://placehold.co/15x15/c9d0d9/c9d0d9.webp) |
| `--color-slate-200` | `#abb5c4` | ![#abb5c4](https://placehold.co/15x15/abb5c4/abb5c4.webp) |
| `--color-slate-300` | `#8d9bb0` | ![#8d9bb0](https://placehold.co/15x15/8d9bb0/8d9bb0.webp) |
| `--color-slate-400` | `#6f819b` | ![#6f819b](https://placehold.co/15x15/6f819b/6f819b.webp) |
| `--color-slate-500` | `#62748d` | ![#62748d](https://placehold.co/15x15/62748d/62748d.webp) |
| `--color-slate-600` | `#4d5b6f` | ![#4d5b6f](https://placehold.co/15x15/4d5b6f/4d5b6f.webp) |
| `--color-slate-700` | `#384351` | ![#384351](https://placehold.co/15x15/384351/384351.webp) |
| `--color-slate-800` | `#242a33` | ![#242a33](https://placehold.co/15x15/242a33/242a33.webp) |
| `--color-slate-900` | `#0f1115` | ![#0f1115](https://placehold.co/15x15/0f1115/0f1115.webp) |
| `--color-slate-950` | `#040506` | ![#040506](https://placehold.co/15x15/040506/040506.webp) |
| `--color-slate` | `#62748d` | ![#62748d](https://placehold.co/15x15/62748d/62748d.webp) |
| `--color-gray-50` | `#e6e7ea` | ![#e6e7ea](https://placehold.co/15x15/e6e7ea/e6e7ea.webp) |
| `--color-gray-100` | `#cacdd3` | ![#cacdd3](https://placehold.co/15x15/cacdd3/cacdd3.webp) |
| `--color-gray-200` | `#aeb3bc` | ![#aeb3bc](https://placehold.co/15x15/aeb3bc/aeb3bc.webp) |
| `--color-gray-300` | `#9298a5` | ![#9298a5](https://placehold.co/15x15/9298a5/9298a5.webp) |
| `--color-gray-400` | `#767e8f` | ![#767e8f](https://placehold.co/15x15/767e8f/767e8f.webp) |
| `--color-gray-500` | `#6a7181` | ![#6a7181](https://placehold.co/15x15/6a7181/6a7181.webp) |
| `--color-gray-600` | `#535965` | ![#535965](https://placehold.co/15x15/535965/535965.webp) |
| `--color-gray-700` | `#3c4049` | ![#3c4049](https://placehold.co/15x15/3c4049/3c4049.webp) |
| `--color-gray-800` | `#25272d` | ![#25272d](https://placehold.co/15x15/25272d/25272d.webp) |
| `--color-gray-900` | `#0e0f11` | ![#0e0f11](https://placehold.co/15x15/0e0f11/0e0f11.webp) |
| `--color-gray-950` | `#020203` | ![#020203](https://placehold.co/15x15/020203/020203.webp) |
| `--color-gray` | `#6a7181` | ![#6a7181](https://placehold.co/15x15/6a7181/6a7181.webp) |
| `--color-zinc-50` | `#e7e7e9` | ![#e7e7e9](https://placehold.co/15x15/e7e7e9/e7e7e9.webp) |
| `--color-zinc-100` | `#cdcdd0` | ![#cdcdd0](https://placehold.co/15x15/cdcdd0/cdcdd0.webp) |
| `--color-zinc-200` | `#b2b2b8` | ![#b2b2b8](https://placehold.co/15x15/b2b2b8/b2b2b8.webp) |
| `--color-zinc-300` | `#9898a0` | ![#9898a0](https://placehold.co/15x15/9898a0/9898a0.webp) |
| `--color-zinc-400` | `#7d7d87` | ![#7d7d87](https://placehold.co/15x15/7d7d87/7d7d87.webp) |
| `--color-zinc-500` | `#71717a` | ![#71717a](https://placehold.co/15x15/71717a/71717a.webp) |
| `--color-zinc-600` | `#58585f` | ![#58585f](https://placehold.co/15x15/58585f/58585f.webp) |
| `--color-zinc-700` | `#404045` | ![#404045](https://placehold.co/15x15/404045/404045.webp) |
| `--color-zinc-800` | `#27272a` | ![#27272a](https://placehold.co/15x15/27272a/27272a.webp) |
| `--color-zinc-900` | `#0f0f10` | ![#0f0f10](https://placehold.co/15x15/0f0f10/0f0f10.webp) |
| `--color-zinc-950` | `#020203` | ![#020203](https://placehold.co/15x15/020203/020203.webp) |
| `--color-zinc` | `#71717a` | ![#71717a](https://placehold.co/15x15/71717a/71717a.webp) |
| `--color-neutral-50` | `#e6e6e6` | ![#e6e6e6](https://placehold.co/15x15/e6e6e6/e6e6e6.webp) |
| `--color-neutral-100` | `#ccc` | ![#ccc](https://placehold.co/15x15/ccc/ccc.webp) |
| `--color-neutral-200` | `#b3b3b3` | ![#b3b3b3](https://placehold.co/15x15/b3b3b3/b3b3b3.webp) |
| `--color-neutral-300` | `#999` | ![#999](https://placehold.co/15x15/999/999.webp) |
| `--color-neutral-400` | `grey` | ![grey](https://placehold.co/15x15/grey/grey.webp) |
| `--color-neutral-500` | `#737373` | ![#737373](https://placehold.co/15x15/737373/737373.webp) |
| `--color-neutral-600` | `#595959` | ![#595959](https://placehold.co/15x15/595959/595959.webp) |
| `--color-neutral-700` | `#404040` | ![#404040](https://placehold.co/15x15/404040/404040.webp) |
| `--color-neutral-800` | `#262626` | ![#262626](https://placehold.co/15x15/262626/262626.webp) |
| `--color-neutral-900` | `#0d0d0d` | ![#0d0d0d](https://placehold.co/15x15/0d0d0d/0d0d0d.webp) |
| `--color-neutral-950` | `#000` | ![#000](https://placehold.co/15x15/000/000.webp) |
| `--color-neutral` | `#737373` | ![#737373](https://placehold.co/15x15/737373/737373.webp) |
| `--color-stone-50` | `#e7e5e4` | ![#e7e5e4](https://placehold.co/15x15/e7e5e4/e7e5e4.webp) |
| `--color-stone-100` | `#cfcbc9` | ![#cfcbc9](https://placehold.co/15x15/cfcbc9/cfcbc9.webp) |
| `--color-stone-200` | `#b7b2ae` | ![#b7b2ae](https://placehold.co/15x15/b7b2ae/b7b2ae.webp) |
| `--color-stone-300` | `#9f9893` | ![#9f9893](https://placehold.co/15x15/9f9893/9f9893.webp) |
| `--color-stone-400` | `#877e78` | ![#877e78](https://placehold.co/15x15/877e78/877e78.webp) |
| `--color-stone-500` | `#7a726c` | ![#7a726c](https://placehold.co/15x15/7a726c/7a726c.webp) |
| `--color-stone-600` | `#5f5854` | ![#5f5854](https://placehold.co/15x15/5f5854/5f5854.webp) |
| `--color-stone-700` | `#443f3c` | ![#443f3c](https://placehold.co/15x15/443f3c/443f3c.webp) |
| `--color-stone-800` | `#292624` | ![#292624](https://placehold.co/15x15/292624/292624.webp) |
| `--color-stone-900` | `#0e0d0c` | ![#0e0d0c](https://placehold.co/15x15/0e0d0c/0e0d0c.webp) |
| `--color-stone-950` | `#000` | ![#000](https://placehold.co/15x15/000/000.webp) |
| `--color-stone` | `#7a726c` | ![#7a726c](https://placehold.co/15x15/7a726c/7a726c.webp) |
## License

Licensed under the [MIT license](https://github.com/mossui/mossui/blob/main/LICENSE.md).

## Contributors

Contributions are welcome! Please feel free to submit a Pull Request.

<a href="https://github.com/mossui/mossui/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=mossui/mossui" />
</a>
