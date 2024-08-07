# Toggle - Pieces

Element: A single on/off toggle button with the appearance of the button.  Toggles can be set to act the same as a radio button (one selection at a time), or checkboxes (multiple selections).  Most often seen in a group of toggle buttons (Toggle - Group), they can however exist as a single button toggle on/off as well.

[Styleguide Link](https://zpl.io/bJLOyxr)

- Parent: [Toggle - Ctrl](https://github.com/able-app/docs/blob/7fce4c938ec276d881761d80876efe894b9b88e1/controls/%CE%B5%20elements/toggle/toggle.md)
- Child: [Label](https://github.com/able-app/docs/blob/5a96c205429d6f9ca9bcbfa998a17c2596ca4a32/controls/%CE%B5%20elements/label.md)

## Properties

### Type

**Text:** The text and text with icon either left or right.

**Icon:** The icon only appearance to a toggle button. This is used in many toolbar situations like with a text editor toolbar.

### Style

The same styles that are possible in the Button element are available here.

- Primary
- Secondary
- Light
- Neutral
- Dark

### Status

This property defines if the toggle is set to the "On" or "Off" version. Buttons that have a status of "on" show as fills and those that are "off" have a line outlining the button shape.

**NOTE:** The intent is to NOT have double lines between each toggle-pieces (as is shown in the design file) when they are grouped together. However, this would complicate the design file more than we'd like, so understand that the right side "lines" of the Left and Center "Locations" should be removed to achieve the desired effect of a single 1 dp line between each piece.

### Location

This is primarily for the multi-toggle option to define the left, center, and right toggles, but we also include the appearance of the toggle when a single toggle button is present.

### Size

We have the need for two sizes in the Toggle, the first **Base** (default) size for most use cases and a shorter one "**Tiny**" for those situations where the Toggle shows up in other fixed height components like in the App Bar.

### State

- Enabled
- Disabled
- Hover
- Pressed
- Focus