# WD4E_CSS

## Colors

RGBA or hexadecimal

## Text

Use sans-serif fonts whenever possible.

### font-style

Regular, italic, bold

### font-variant

normal
small-caps

### font-size

Can use words:  xx-small, x-small, small, smaller, medium, larger, x-large, xx large

Not a very good option. Instead, use pixels or percentages. Percentages are more responsive.

### color, background-color

RGBA or hexadecimal

### text-align

left, right, center, justify

### line-height

Affects space between lines.

## Tips

Plan projects on paper, first.

## display and visibility

Every element is a box.

### inline

Just enough width and height to sit next to each other. (span)

### block

Forces a line break.

default takes up all horizontal width and just enough height. Rules can set height and width. (div, p)

### inline-block

Can give height and width.

### none

Removed from page

### float and clear

float - repositions to right or left; won't overlap; reverses order if floating right

clear - used to keep floating elements away

### visible, hidden, scroll, and auto

visible - overflows onto other elements

hidden - restricts area so some stuff may be hidden

scroll - adds scroll bars

auto - adds scroll bars, if necessary

### table-cell

need display: table;

## Grid

https://www.w3schools.com/css/css_grid.asp
https://www.w3schools.com/css/css_grid_container.asp
https://www.w3schools.com/css/css_grid_item.asp

## Flex

parent and child element (div/img)

Set parent to flex.
Set flex-wrap to wrap or nowrap.
Set flex-direction to row or column.
Set justify-items and/or align-content.

```
    div {
        display: flex;
        flex-wrap: wrap;
        flex-direction: column;
        justify-content: center;
    }
```

    justify-items - only when direction is row
    align-content

https://www.w3schools.com/css/css3_flexbox.asp
https://www.w3schools.com/css/css3_flexbox_container.asp
https://www.w3schools.com/css/css3_flexbox_items.asp

## Links

Order of precedence:

a:link
a:visited
a:hover
a:active

## Advanced selectors

p.main = all paragraphs that have the class of "main"

## Attribute selectors

a[href='info.html'] all links where the href is "info.html"
^ a[href^="http://umich'] starts with
$ img[src$='.png] ends with
* a[href*='umich'] has "umich" in the href


PseudoClasses
Pseudo Elements

## Resources

chrispederick.com/work/web-developer
css3generator.com

