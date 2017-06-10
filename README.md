# jQuery-stylesheet

 A simple jQuery plugin to manipulate CSS styleSheet. 

## How it runs?

The plugin insert a new style sheet element on the page. It will be inserted where the js code is placed and will override other css style sheets placed before.

## Usage

Use `$(selector).stylesheet({ key:value })` to add new rules for the selector.    
Or `$(selector).stylesheet(key)` to get the value for that key.    
`$(selector).stylesheet(key,null)` will remove the rule and use the default one.   
`$(selector).stylesheet("*",null)` will remove all previous rules and use the default ones. 


## License

[MIT License]()
