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

- Don't use Sass placeholders (https://www.sitepoint.com/avoid-sass-extend/)

## Example SCSS structure

```tree
.
├── abstracts
|   ├── mixins
|       ├── _bem.scss
|       ├── _clearfix.scss
|       ├── _hover.scss
|   ├── _functions.scss
|   ├── _variables.scss
├── base
|   ├── _fonts.scss
|   ├── _generic.scss
|   ├── _sanitize.scss
├── components
|   ├── _button.scss
|   ├── _card.scss
|   ├── _panel.scss
├── elements
|   ├── _typography.scss
|   ├── _lists.scss
|   ├── _image.scss
├── layout
|   ├── _bootstrap-grid.scss
|   ├── _site-header.scss
|   ├── _section.scss
|   ├── _site-footer.scss
├── pages
|   ├── _home.scss
|   ├── _week-action.scss
├── utilities
|   ├── _clearfix.scss
```

## Credits

* **Cyril de Wit** - _Initial work_ - [cyrildewit](https://github.com/cyrildewit)

See also the list of [contributors](https://github.com/cyrildewit/perceptor/graphs/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
