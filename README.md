# jCSSRule

 Manipulate CSS style sheet and set dynamic rules. 

## How it runs?

The code insert a new style sheet element on the page. It will be inserted where the js code is placed and will override other css style sheets placed before.

## Usage

- Use `jCSSRule(selector,property,value)` or `jCSSRule(selector, { property:value })` to add new rules for the selector.
- 1jCSSRule(selector,property)` to get the value for that key.
- 1jCSSRule(selector,property, null)` will remove the rule and use the default one defined in the css.
- `jCSSRule("*", null)` will remove all previous rules.

If you better like the jQuery syntaxe, use the [jQuery plugin](https://viglino.github.io/jCSSRule/jqindex.html).

[See it in action](https://viglino.github.io/jCSSRule/)

## License

MIT License
