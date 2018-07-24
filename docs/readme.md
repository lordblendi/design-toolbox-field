# Design Toolbox Fields and inputs

Fields and inputs component of the TenForce design toolbox.

## CSS

This component is using [one](https://github.com/tenforce/design-toolbox-field/blob/master/docs/sass/toolbox-field.scss) CSS file.

## HTML structure

The Design documentation was built in Jekyll using SASS and Liquid.

```html
<div class="toolbox-field">
  <div class="toolbox-field__label">Label</div>
  <div class="toolbox-field__data">
    <div class="toolbox-field__error"></div>
    <div class="toolbox-field__value">
      <input class="toolbox-field__input" type="text" value="">
    </div>
  </div>
</div>
```

Options:
- `toolbox-field--not-empty`
- `toolbox-field--error`


## Usage
### Links to CSS files
- main CSS
  - [built](https://tenforce.github.io/design-toolbox-field/sass/toolbox-field.css)
  - [raw](https://github.com/tenforce/design-toolbox-field/blob/master/docs/sass/toolbox-field.scss)

### Jekyll
Add [the content of this file](https://github.com/tenforce/design-toolbox-field/tree/master/docs/import/include-field.html) to the another Jekyll project to include files from this project.

## Dependencies
- [Tailwind v0.6.4](https://tailwindcss.com)
- [TenForce default CSS](https://github.com/tenforce/design-toolbox-default-css)
- [jQuery (for javascript)](https://jquery.com)
