# True grid

> A gritty ['isolation' float](http://palantir.net/blog/responsive-design-s-dirty-little-secret)
[Less](http://lesscss.org/) mixin for CSS hipsters who sport
[a mustache or eye patch](http://en.wikipedia.org/wiki/True_Grit_(1969_film)#Differences_from_the_novel).

## Yep

- Mobile First
- Progressive Enhancement
- Responsive Web Design
- Semantic Grid
- [YAGNI](http://en.wikipedia.org/wiki/You_aren't_gonna_need_it)

## Nope

- IE < 9 pretty-printing
- Pixel perfect percentage rounding (especially in Safari)
- Nested columns

## API

The API consists of a single global `.grid` mixin function with the following
parameters:

- `@min-width`: CSS media query length
- `@max-width`: CSS media query length (optional)
- `@columns` integer (optional, default: `12`)
- `@gutter`: CSS length (optional, default: `1.5em`)
- `@context-selector`: (optional, default: `.grid-context`;)
- `@column-selector`: (optional, default: `> *`;)
- `@parent-selector`: (optional)
- `@layout`: CSS rule sets<br>
   Provides a local `.column` mixin function with the following parameters:
    - `@from` integer
    - `@to` integer (optional, default: `@from`)

## Examples

[http://ebednarz.github.io/true-grid](http://ebednarz.github.io/true-grid)

## License

MIT
