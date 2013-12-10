# hut-base

Base styles for HTML UI Toolkit projects.

Check out the [documentation and examples](http://conradz.github.io/hut-base/)!

This project defines basic styles. These styles are designed to be overriden by
your project if you do not want the default styles.

This project is designed to be used in conjunction with
[rework-vars](https://github.com/visionmedia/rework-vars) and
[rework-npm](https://github.com/conradz/rework-npm). For development use
[hut-build](https://github.com/conradz/hut-build).

When using [rework-npm](https://github.com/conradz/rework-npm) simple install
the package with `npm install hut-base` and reference it from your stylesheet
with `@import "hut-base";`.

## Customizing

This is meant to be used as a baseline style, not as a complete styling
framework. You should create your own styling by overriding the styles for your
own use. You can also change much of the styling by overriding the variables
defined in the
[`styles/variables.css`](https://github.com/conradz/hut-base/blob/master/styles/variables.css)
file.
