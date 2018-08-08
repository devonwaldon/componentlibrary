# Button Atom

## HTML

### Semantic Button HTML
`<button>Click Me</button>`

### Input with the `submit` type
`<input type="submit" value="Click Me">`

### Class of `.button`
`<a href="#" class="button">Click Me</a>`


## SCSS

### Variables (optional)
```
$__button__text-color
$__button__text-color--hover
$__button__background-color
$__button__background-color--hover
$__button__padding
$__button__font
```

### SCSS
```
%button {

}

.button,
button,
input[type="submit"] {
    @extend %button;
}
```