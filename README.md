<p align="center">
    <a href="https://www.beercss.com" target="_blank" rel="noopener noreferrer"><img src="https://www.beercss.com/logo.png" alt="Beercss logo"></a>
</p>
<p align="center">
    <a href="https://github.com/beercss/beercss/blob/main/LICENSE"><img src="https://img.shields.io/github/license/beercss/beercss" alt="License"></a>
    <a href="https://www.npmjs.com/package/beercss"><img src="https://img.shields.io/npm/dt/beercss" alt="Downloads"></a>
    <a href="https://bundlephobia.com/package/beercss"><img src="https://badgen.net/bundlephobia/minzip/beercss" alt="Size"></a>
    <a href="https://www.npmjs.com/package/beercss"><img src="https://img.shields.io/npm/v/beercss" alt="Version"></a>
    <a href="https://github.com/beercss/beercss/pulls"><img src="https://img.shields.io/github/issues-pr/beercss/beercss" alt="Pull Request"></a>
    <a href="https://github.com/beercss/beercss/issues"><img src="https://img.shields.io/github/issues/beercss/beercss" alt="Issues"></a>
</p>

# Beercss

Build material design interfaces in record time...

...without stress for devs 🍺💛

Cheers, www.beercss.com

## Why? ##

- It's based on latest material design patterns.
- It's themeable.
- **It has zero dependencies.**
- It does a lot of combinations.
- It's easy to work with Vue, React, Angular, Svelte and others.
- **It has about 10kb.**
- **It has the most simple html output around.**
- It does not need tons of documentation to explain it.
- It's fast to learn, read and write code.
- **It's like pure malt beer, only native and standard code.**
- No tricks, no build steps and no abstraction layers to try reduce your final code.
- It's well designed and we hope that you can do a lot with it.

## Applying "the beer way" in css?

This project was guided by the **"Germany Beer Purity Law"** or **"Reinheitsgebot"** created in 1516. This law states that beer should only be brewed with the following ingredients: **water**, **barley malt** and **hops**. Only 3 ingredients. Exciting, right? So we thinking about It and our 3 ingredients are: **settings**, **elements** and **helpers**. This sounds weird at first time, because It's not BEM, OOCSS, SMACSS, ITCSS, "Utility first" or any other approach. Our approach doesn't avoid some bad practices, but is lightweight, tasty and pure like a beer. Just try it and feel it! 😁

```
|  SETTINGS     |       // The settings affects all document
|---------------|----|
|               |    |
|  ELEMENTS     |    |  // The elements are the components, widgets or tags
|               |    |
|---------------|    |
|               |    |
|               |    |
|  HELPERS      |----|  // The common helpers makes the elements more scalable and customizable
|               |
|               |
|---------------|
```

### DO:

```
// 1 setting to 1 document
<html class="settings">...</html>

// 1 element to N helpers
<element class="helper helper">...</element>
<div class="element helper helper">...</div>

// apply css rules like this
.element.helper {...}
.element > .element {...}
.element > .helper {...}
```

### DON'T:

```
// N elements to 1 tag
<div class="element element helper">...</div>

// avoid dependencies
<div class="element">
  <div class="element-header">...</div>
  <div class="element-content">...</div>
  <div class="element-footer">...</div>
</div>

// apply css rules like this
.element.element {...}
.element .element {...}
.element .helper {...}
```

## Supporting Beercss

Beercss is an MIT-licensed open source project with its ongoing development made possible entirely by the support of these awesome backers. If you'd like to join them, please consider:

- [Become a backer or sponsor on Patreon](https://www.patreon.com/beercss).
- [Become a backer or sponsor on Open Collective](https://www.opencollective.com/beercss).

## Getting Started

### CDN

From jsdelivr.net.

```html
<link href="https://cdn.jsdelivr.net/npm/beercss@1.2.9/dist/cdn/beer.min.css" rel="stylesheet" />
<script src="https://cdn.jsdelivr.net/npm/beercss@1.2.9/dist/cdn/beer.min.js" type="text/javascript"></script>
```

### NPM

You can get the latest release using NPM. This release contains source files as well as the compiled CSS and JavaScript files.

```js
// installing
npm i beercss
```

```js
// importing
import "beercss";
```

## Documentation
Complete documentation and examples available at https://www.beercss.com/
- **[CodePen Template](https://codepen.io/collection/XydYMB)**

## Contributing Guide

Hi! We are really excited that you are interested in contributing to Beercss! Before submitting your contribution, please make sure to take a moment and read through the following guidelines:

https://github.com/beercss/beercss/blob/main/CONTRIBUTING.md

## License

[MIT](https://opensource.org/licenses/MIT)

## Cheers to all people here 🍻
[![Stargazers repo roster for @beercss/beercss](https://reporoster.com/stars/notext/beercss/beercss)](https://github.com/beercss/beercss/stargazers)
