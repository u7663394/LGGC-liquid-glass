# LGGC: Liquid Glass by GuoChen

> Turn DOM element into a liquid glass UI with a single class.

## 1. Features

- Liquid glass visual effect
- Single-class usage with `class="lggc"`
- CSS-only and open-source
- Super lightweight

## 2. 🚀 Installation

### Local / direct browser usage

```html
<link rel="stylesheet" href="./dist/lggc.css" /> 
 <!-- or  -->
<link rel="stylesheet" href="./dist/lggc.min.css" />
```

### CDN

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/lggc@0.1.0/dist/lggc.css" />
<!-- or -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/lggc@0.1.0/dist/lggc.min.css" />
```

### NPM

```bash
npm install lggc

# test how to import
```

## 3. 🚀 Usage

### CSS only

```html
<div class="lggc">Hello Liquid Glass</div>
```

## Or you want to fine-tuning

The following variables are stable public interfaces:

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
    --lggc-bg: rgba(255,255,255,0.18);
  "
>
  Customized glass
</div>
```

## 4. Demo

Open [index.html](./index.html) to preview the welcome page locally.

![demo](assets/demo.png)

## 5. Inspiration

Inspired by ...

## 6. License

[MIT](./LICENSE)
