# Switch

Primitive: A singular switch with its possible status (on/off) and states.

[Styleguide Link](https://zpl.io/bLvqy06)

### Structure -The "Properties" of the object.

**Status** - The value given to the screen object, in this case a switch with possibilities of On or Off.

**Style** - Supplied by the child level (Base - Shape) this is the general appearance of the screen object.  For now we only have the base style you'd normally see a switch, and a rectangular option which is our customized appearance for a switch.  Note: Additional appearance can be added to the Base - Shape file to extend the styles at this level.

**State** - The different appearances of the screen object based on interaction and the status of the screen object.  Possible states are Enabled, Disabled, Focus, Hover, Pressed.



### Interaction

**Hitarea** - It's important to understand that the tappable/clickable area of the screen object being displayed may be small in appearance than the actual area you can interact with.  This hitarea will normally be based off the parents container for this primitive.
