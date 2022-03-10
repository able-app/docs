# Ω Field - Shape (Surface)

Base: A collection for the styling (shape) of the Field Background Surface is set here. This base level feeds into the Field element where it is combined with the other field containers to form the Field element.

[Styleguide Link](https://zpl.io/ag18MJ9)

* Parent: [Field](https://github.com/able-app/docs/blob/78b7d0a469492d69eba8f33ae838468642242f52/controls/%CE%B5%20elements/field/field.md)

## Properties

### Style

* Line - A single under line.
* Rounded - Rounded corner box
* Square - Squared of box
* Pill - Pill shaped background surface

### Type

**Base** (default) - The primary (normal) appearance of the field surface.

**Inverted** - Used when the field is used on a component with a dark background (ex. Gridview Photo - search)

### State

* Enabled
* Disabled
* Hover
* Pressed
* Focus
* Error - When the field has invalid data in the field we visually display this using the Error state of the field background.
* Warning - When the field has data that is possibly invalid, or isn't valid yet (typing in a password at 2 characters where 9 are required)
* Success - To give positive feedback to the user upon fulfilling the requirement (typing in correct 9 characters of the password)
