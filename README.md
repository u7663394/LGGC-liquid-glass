# LGGC: Liquid Glass by GuoChen

[![Author](https://img.shields.io/badge/Author-Guochen%20Wang-blue)](https://github.com/u7663394)
[![GitHub](https://img.shields.io/badge/GitHub-u7663394%20(Guochen%20Wang)-black?logo=github)](https://github.com/u7663394)
[![Email](https://img.shields.io/badge/Email-guochenwang710%40gmail.com-red)](mailto:guochenwang710@gmail.com)

<p align="right">
  🌐 Language: English | <a href="./README.zh-CN.md">Chinese</a>
</p>

https://github.com/user-attachments/assets/b3110481-47c6-414f-a1dc-8e12a1b62483

> Turn DOM element into a liquid glass UI with a single class `class="lggc"`.

## 1. 🚀 Installation

### Local / direct usage

```html
<link rel="stylesheet" href="./dist/lggc.css" /> 
 <!-- or  -->
<link rel="stylesheet" href="./dist/lggc.min.css" />
```

### CDN

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@guochenwang/lggc@0.1.0/dist/lggc.css" />
<!-- or -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@guochenwang/lggc@0.1.0/dist/lggc.min.css" />
```

### NPM

```bash
npm install @guochenwang/lggc
```
Then you can find css files in `./node_modules/@guochenwang/lggc/dist/lggc.min.css`
```bash
import '@guochenwang/lggc/dist/lggc.min.css'
```

## 2. 🚀 Usage

### CSS

```html
<div class="lggc">Hello Liquid Glass</div>
```

### Or you want to fine-tuning

The following variables are public interfaces:

- `--lggc-radius`
- `--lggc-padding`
- `--lggc-bg`
- `--lggc-border`
- `--lggc-blur`
- `--lggc-highlight`

Example:

```html
<div
  class="lggc"
  style="
    --lggc-radius: 28px;
    --lggc-padding: 1.25rem 1.5rem;
    --lggc-bg: rgba(255,255,255,0.18);">
  Customized glass
</div>
```

## 3. Demo

Open [welcome page](https://u7663394.github.io/LGGC-liquid-glass/) to preview the effect.

![demo](assets/demo.png)

![effect](assets/effect.png)

## 4. Features

- Liquid glass visual effect
- Single-class usage with `class="lggc"`
- CSS-only and open-source
- Super lightweight

## 5. Inspiration

This work draws inspiration from [a video on Bilibili](https://www.bilibili.com/video/BV1J8QSBqEpy/?spm_id_from=333.337.search-card.all.click). Special thanks to the [creator of the video](https://space.bilibili.com/91370417?spm_id_from=333.788.upinfo.detail.click) for sharing such inspiring content and ideas.
