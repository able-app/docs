# Radio Button - Control

Primitive: A singular radio button control with its possible styling, status (on/off) and states.

[Styleguide Link](https://zpl.io/aw5761J)

- Parent: [Radio Button](https://github.com/able-app/docs/blob/8cd03de6556a6ec1dcd98dc8c2230863c5dba43c/controls/components/form/radiobutton.md) (Form Component), Multiple others
- Child: [Radio Button - Shape](https://github.com/able-app/docs/blob/b10f6d1205bbfb1cddfd150d1390ba848812d9d0/controls/%CE%B5%20elements/radiobutton/radiobutton-shape.md)

### Properties

**Status** - The value given to the screen object, in this case a radio button with possibilities of On or Off.

**Style** - Supplied by the child level (Base - Shape) this is the general appearance of the screen object.  For now we have two styles, the normal appearance of the rounded radio button which is the default, and a circular checkbox which is our customized appearance for a radio button.  Note: Additional appearance can be added to the Base - Shape file to extend the styles at this level.

**State** - The different appearances of the screen object based on interaction and the status of the screen object.  Possible states are Enabled, Disabled, Focus, Hover, Pressed.



### Interaction

**Hitarea** - It's important to understand that the tappable/clickable area of the screen object being displayed may be small in appearance than the actual area you can interact with.  This hitarea will normally be based off of the parents container for this primitive.