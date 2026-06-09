# TI-84 Plus CE Calculator

A lightweight, self-hostable TI-84 Plus CE graphing calculator for local development and personal use.

![TI-84 Calculator](https://img.shields.io/badge/TI--84-Online-blue) ![License](https://img.shields.io/badge/license-MIT-green)

## Features

- Full TI-84 Plus CE graphing calculator
- Graphing: functions, parametric, polar, sequences
- Statistics: regression, normal distributions, hypothesis testing
- Algebra: equation solver, matrices, polynomial roots
- Calculus: numerical derivatives, definite integrals
- Finance: TVM solver, amortization tables
- SAT / ACT / AP / IB exam approved calculator

## Quick Start

### Run locally with Python

```bash
git clone https://github.com/txsmxv/Ti84calculator.git
cd Ti84calculator
python3 -m http.server 8080
```

Open **http://localhost:8080** in your browser.

### Run with Node.js

```bash
npx serve .
```

### Or just open the file

Double-click `index.html` — it opens directly in any browser (requires internet connection).

## Embed in Your Project

Add this to any HTML page:

```html
<iframe
  src="https://freeti84.com/calc.html"
  width="320"
  height="620"
  frameborder="0"
  scrolling="no"
  allow="fullscreen"
  title="TI-84 Calculator">
</iframe>
```

## Use Cases

| Who | How |
|-----|-----|
| **Students** | Quick access for homework, SAT/ACT prep |
| **Teachers** | Embed in class sites, Google Classroom, LMS |
| **Developers** | Add calculator widget to education apps |
| **Schools** | Free calculator access without hardware |

## Keyboard Guide

| Button | Function |
|--------|----------|
| Y= | Enter functions to graph |
| GRAPH | Display the graph |
| 2nd | Access secondary functions |
| STAT | Statistical tools |
| MATH | Equation solver, calculus |
| TRACE | Trace values on a curve |
| ZOOM | Adjust graph window |
| TABLE | View function tables |
| MODE | Change calculator modes |
| CATALOG | Browse all built-in functions |

## Online Version

For the full experience with multi-language support, fullscreen mode, offline PWA, and more:

👉 **[freeti84.com](https://freeti84.com)** — Free TI-84 Plus CE Online Calculator

## Requirements

- Any modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection (calculator loads from freeti84.com)

## License

[MIT](./LICENSE)

TI-84 Plus CE is a trademark of Texas Instruments Incorporated. This project is not affiliated with Texas Instruments.

---

⭐ **Star this repo** if it helped you!
