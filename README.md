# Doro :3

## Demo
https://xypher7.github.io/doro-js

## Usage
Add the script:
```html
<script src="doro.js"></script>
```
 And the custom HTML tag:
 ```html
<doro-doro></doro-doro>
```
That's it

## Customization Options
The following properties may be used to customize the behavior of the doro.

Usage example:
```html
<doro-doro doro-speed='5' doro-scream='DORORO :3' doro-restore='false' doro-kill-chance='1'></doro-doro>
```

Option|Description|Default
---|---|---
doro-speed|Doro movement speed|10
doro-scream|Words on trail left behind doro|DORO!
doro-scream-max|Maximum amount of words left on doro's trail. Reduce this value if performance is an issue. Set to 0 to disable.|1000
doro-eat-max|Maximum amount of eaten out sections left on doro's trail. Reduce this value if performance is an issue. Set to 0 to disable.|2500
doro-eat-color|CSS color of the eaten out sections left on doro's trail|white
doro-boom-chance|Probability of an HTML element exploding when colliding|0.05
doro-boom-selector|CSS selector for HTML elements that may explode on collison|.boom,input,textarea,select,button,a,hr,label,td,pre,h1,h2,h3,h4,h5,h6,li,svg
doro-restore|Restore the page after all doros have been exterminated|true
doro-kill-chance|Probability of exterminating a doro upon clicking|0.5
doro-multiply-chance|Probability of a doro multiplying upon clicking|0.4
doro-multiply-max|Maximum amount of new doros that may appear upon a single click|5
