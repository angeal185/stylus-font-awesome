# stylus-font-awesome
stylus port of font-awesome v4.7.0

### Installation

bower:
```sh
$ bower install stylus-font-awesome --save-dev
```

### Instructions

each individual font can be enabled or disabled simply by changing the true/false option in the config.styl file.

Build variables can be edited via the ./includes/variables.styl file.

Simply edit as you see fit, then compile.

compile

````
stylus font-awesome.styl -o ./dist/css/
````

compile .min

````

stylus font-awesome.styl -c -o ./dist/css/font-awesome.min.css
````

done.
