# jQuery-stylesheet

 A simple jQuery plugin to manipulate CSS style sheet and set dynamic rules. 

## How it runs?

The plugin insert a new style sheet element on the page. It will be inserted where the js code is placed and will override other css style sheets placed before.

## Usage

- Use `$(selector).cssRule(property,value)` or `$(selector).cssRule({ property:value })` to add new rules for the selector.
- `$(selector).cssRule(property)` to get the value for that key.
- `$(selector).cssRule(property,null)` will remove the rule and use the default one.
- `$("*").cssRule(null)` will remove all previous rules.

[See it in action](https://viglino.github.io/jQuery-stylesheet/)

## License

MIT License
