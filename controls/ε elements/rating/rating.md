# Rating

Element: A collection of rate points (primitive) to form a scaled rating value for both interaction and visual representation.

[Styleguide Link](https://zpl.io/29GBKQy)

- Parent: Multiple
- Child: [Rate Point](https://github.com/able-app/docs/blob/b10f6d1205bbfb1cddfd150d1390ba848812d9d0/controls/%CE%B5%20elements/rating/ratepoint.md)

### Structure -The "Properties" of the object.

**Size** - The general size of the element as a whole.

**Style** - Supplied by the child level (Base - Shape) this is the general appearance of the screen object.  Note: Additional appearance can be added to the Base - Shape file to extend the styles at this level.

**State** - The different appearances of the screen object based on interaction and the status of the screen object.  Possible states are Enabled, Disabled.



### Interaction

**Hitarea** - It's important to understand that the tappable/clickable area of the screen object being displayed may be small in appearance than the actual area you can interact with.  This hitarea will normally be based off the parents container for this element. [Here's an example](https://codepen.io/ashdurham/pen/HBxLK) of what we're looking for.

