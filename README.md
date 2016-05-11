# What is _responsive_
_responsive_ is my answer to feeling creatively restricted by Bootstrap. I often find myself using Bootstrap in its entirety when all that I want is the ability to create a responsive design. Bootstrap does this well but also comes with a lot of other styles that encourage me to design my sites a certain way.

## How to use responsive
_responsive_ is a collection of styled divs used to help align websites

### Containers
`.container-extended` is a full-width container taking up 100% of the screen

`.container` is a responsive container. `.container` takes up 96% of the screen on phones and 80% of the screen on all other devices

### Row
`.row` is just a type of container that takes up 100% of its parent's width, but is more semantic

### Columns
There are 4 types of columns: _phone_, _tablet_, _desktop_, and _wide_. Each have specific widths ranging from 10-100% of the parent width.
The column class names follow the style `.[device]-col-[size]`. [device] is phone, tablet, desktop or wide. [size] is a number 1-10 representing 10-100% of width.

## Example Usage
```html
<!-- container-extended takes up the full width of the screen -->
<div class="container-extended">
  <div class="row">
    <div class="phone-col-10 tablet-col-4 desktop-col-3 wide-col-2">
      <!--
      This column will be:
        100% width on phones
        40% width on tablets
        30% width on desktops
        20% width on widescreens
      -->
    </div>
    <div class="phone-col-10 tablet-col-6 desktop-col-7 wide-col-8">
    <!--
      This column will be:
        100% width on phones
        60% width on tablets
        70% width on desktops
        80% width on widescreens
      -->
    </div>
  </div>
</div>

```
