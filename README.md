# extjs-icofont
EXTJS 6.0.2 IcoFont Package

Source for IcoFont Downloads: http://icofont.com/

## Description
My attempt to add more icons that is easy to deploy to any ExtJS project. This project is a merge from the ExtJS FontAwesome package.
Right now, only two icons in this iconset are fully integrated, but should be very easy to add more.  

### Example sass\etc\_variables.scss
```css
$if-var-angry-monster: "\e901";
$if-var-bathtub: "\e902";
```

### Example sass\etc\_icons.scss
```css
.#{$if-css-prefix}-angry-monster:before { content: $if-var-angry-monster !important; }
.#{$if-css-prefix}-bathtub:before { content: $if-var-bathtub !important; }
```

*Note: 'if' stands for 'IcoFont' and should not be confused with the conditional statement 'if'*
