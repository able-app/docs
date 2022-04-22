# ε NavToggle

Element: A specialized toggle grouping intended for use within the NavTab - Bar to both navigate back in the history stack (left toggle button) and if enabled, expand horizontally to reveal additional tools.

[Styleguide Link](https://zpl.io/adyAvPn)

* Parent: [NavTab - Bar](../../components/app-bar/navtab-bar.md)
* Child: [Toggle - Pieces](toggle-pieces.md)

## Properties

### Style

* Neutral (default)

### Quantity

The number of Toggle button pieces to include in the design. Each of these segments is meant to represent an activity that the user can take on the screens content. This might be to Add, Delete, Move, Assign, Print, Scan, Copy, etc. which are each represented in a toggle segment as an icon. Of course the far left segment is always reserved for the nav back.

## Interaction

In its resting state the NavToggle is either showing one Toggle (default) or two toggle segments. When two segments are displayed the intent is that the right side segment (with the more icon) can be tapped to expand the hidden segments. This action pushes other content (tabs) to the right. Upon taking any action other than in the Toggle, the NavToggle will collapse back to its resting state. The user can also press the more icon to collapse the NavToggle as well.

### Metaphors

We use the metaphors (aka Icon Library) to standardize on the meaning of icons used in the application. In the NavToggle element we have two metaphors.

**Arrow Left**: Icon-Library > Base > Navigation > Nav - Back (Left)

**More:** Icon-Library > Base > Actions > Act - More (Horz)
