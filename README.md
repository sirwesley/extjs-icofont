# extjs-icofont
EXTJS 6.0.2 IcoFont Package

Source for IcoFont Downloads: http://icofont.com/

## Description
My attempt to add more icons that are easy to deploy to any ExtJS project. This project is a merge from the ExtJS FontAwesome package.
All Icons are included as of 9/13/2016

## Installation
* Simply download the 'package'
* Place the "icofont" in your *packages/local/* folder  (example: *packages/local/icofont*)
* Add "icofont" to your *app.json* file. 
Example: 
```json
    "requires": [
        "font-awesome",
        "ext-ux",
        "icofont"
    ],
```

### Example *sass\etc\\_variables.scss*
```css
$icofont-var-angry-monster: "\e901";
$icofont-var-bathtub: "\e902";
```

### Example *sass\etc\\_icons.scss*
```css
.#{$icofont-css-prefix}-angry-monster:before { content: $icofont-var-angry-monster !important; }
.#{$icofont-css-prefix}-bathtub:before { content: $icofont-var-bathtub !important; }
```
