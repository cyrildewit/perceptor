# Perceptor

> Modern Sass starter kit that requires you to keep your CSS organized and clean.

## Overview

Perceptor is my personal SCSS boilerplate. It's the result of 4 years of finding the right structure that I can use for my personal projects.

Need an compiler? See [Perceptor Studio](https://github.com/cyrildewit/perceptor-studio)!

### Features

* Organized component structure
* Bootstrap 4 grid included
* Sanitize included
* BEM helper mixins (element & modifier)

**Note:** This project is currently under development. If you have any ideas or tips, please feel free to report that at the issue tracker.

### Rules / Conventions

- Follow the rules of MaintainableCSS
- Don't use Sass placeholders (https://www.sitepoint.com/avoid-sass-extend/)

## Example SCSS structure

```tree
.
├── 00_settings
|   ├── _colors.scss
|   ├── _spacing.scss
|   ├── _variables.scss
├── 01_tools
|   ├── mixins
|       ├── _bem.scss
|       ├── _clearfix.scss
|       ├── _hover.scss
|   ├── _functions.scss
├── 02_base
|   ├── _fonts.scss
|   ├── _generic.scss
|   ├── _sanitize.scss
├── 03_atoms
|   ├── _button.scss
|   ├── _card.scss
|   ├── _panel.scss
├── 04_molecules
|   ├── _typography.scss
|   ├── _lists.scss
|   ├── _image.scss
├── 05_organisms
|   ├── _bootstrap-grid.scss
|   ├── _site-header.scss
|   ├── _section.scss
|   ├── _site-footer.scss
├── 06_templates
|   ├── _home.scss
|   ├── _week-action.scss
├── 07_pages
|   ├── _home.scss
|   ├── _week-action.scss
├── 08_utilities
|   ├── _clearfix.scss
├── 09_vendor
|   ├── _clearfix.scss
```

## Credits

* **Cyril de Wit** - _Initial work_ - [cyrildewit](https://github.com/cyrildewit)

See also the list of [contributors](https://github.com/cyrildewit/perceptor/graphs/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
