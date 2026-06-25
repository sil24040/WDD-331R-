# WDD 331R Practice Site

**Student:** Sophie Da Silveira  
**Semester:** Spring 2026  
**Live Site:** https://sil24040.github.io/WDD-331R-/

## About

This repository is my Practice Site for WDD 331R: Advanced CSS.

Each week I add new pages and styles as I work through the course assignments.

The site deploys automatically to GitHub Pages on every push to main.

## Pages

* [Home](https://sil24040.github.io/WDD-331R-/)
* [Custom Properties and Nesting](https://sil24040.github.io/WDD-331R-/unit-1/custom-properties/)
* [Layered Components](https://sil24040.github.io/WDD-331R-/unit-2/layered-components/)
* [Visual Effects](https://sil24040.github.io/WDD-331R-/unit-3/visual-effects/)
* [Editorial Layout](https://sil24040.github.io/WDD-331R-/unit-4/grid-layouts/editorial.html)
* [Card Grid](https://sil24040.github.io/WDD-331R-/unit-4/grid-layouts/cards.html)
* [Container Query Demo](https://sil24040.github.io/WDD-331R-/unit-4/advanced/container-demo.html)
* [Sticky Demo](https://sil24040.github.io/WDD-331R-/unit-4/advanced/sticky-demo.html)
* [Resume](https://sil24040.github.io/WDD-331R-/resume.html)
* [Contact](https://sil24040.github.io/WDD-331R-/contact.html)

## Typography System

Typography tokens are stored in `css/tokens/variables.css`.

The site uses:
* Inter for body text
* Fraunces for headings

A modular type scale with fluid `clamp()` values controls font sizing across different viewport widths.

## CSS Architecture

The project uses a layered CSS architecture with:

* Tokens
* Base styles
* Layout styles
* Components
* Utilities

## Folder Structure

```text
css/
├── base/
├── components/
├── layout/
├── tokens/
├── utilities/
└── main.css