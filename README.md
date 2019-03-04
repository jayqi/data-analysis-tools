# Overview of Data Analysis Tools README

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

"Overview of Data Analysis Tools" is a survey of general purpose data analysis tools accessible to non-experts.

- What are the common tools?
- When are they best suited?
- Emphasis on free or open-source

## How to Use

The slide deck can be viewed here: https://jayqi.github.io/data-analysis-tools

Additionally, the markdown document version containing the same content is easier to read through when using as a reference: [overview-of-data-analysis-tools.md](https://github.com/jayqi/civic-data-tutorials/blob/master/overview-of-data-analysis-tools/overview-of-data-analysis-tools.md)

## Generating the slides

Slides are rendered using [reveal.js](https://revealjs.com/#/) and generated from the markdown document using [pandoc](https://github.com/jgm/pandoc/wiki/Using-pandoc-to-produce-reveal.js-slides).

To generate slides from the markdown document, run in command line:

    pandoc -t revealjs -s -o index.html data-analysis-tools.md -V revealjs-url=https://revealjs.com --css=style.css

## Local serving

You can use a local webserver, e.g. `python3 -m http.server`, to serve the slides. Note that an internet connection is still required, as reveal.js is loaded from CDN.
