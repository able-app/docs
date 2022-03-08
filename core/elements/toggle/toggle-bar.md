# Toggle Bar

Element: A collection of toggles with layout padding and behaviors.  The bar component can have different background surfaces (colors) so we don't include a surface here.

[Styleguide Link](https://zpl.io/adyA535)

- Parent: [App Bar - Ext.](https://github.com/able-app/docs/blob/d689178b930c7095c750671b112985ac09eccd08/controls/components/appbar/app-bar-ext.md),  [Form > Toggle Button](https://github.com/able-app/docs/blob/d689178b930c7095c750671b112985ac09eccd08/controls/components/form/togglebutton.md)
- Child: [Toggle - Ctrl](https://github.com/able-app/docs/blob/7fce4c938ec276d881761d80876efe894b9b88e1/controls/%CE%B5%20elements/toggle/toggle.md)

## Properties

### Layout Types

The options available in the "Toggle" element are capable here.

**Solo** - A grouping of solo toggles. An example of this could be different filters on a search, where each toggle is a different filter type (price, weight, rating, etc.) 

**Group** (default)- When the toggle buttons are pushed together and are presented as a grouping of buttons.  By default, this type exists as a singular choice (toggle on) from the group, but can function as a multi-select button as well.  An example of this would be with a text editor grouping with bold, italic, underline where none or all of the groups options can be selected. 

### Style

- Text (default)
- Icon

### Behavior

- **Fixed** (default)- New toggles that don't fit within the fixed width, wrap to the next row, growing the height of the bar - toggle.
- **Scroll** - Toggles that don't fit within the defined width of the parent container scroll off the side of the bar - toggle (screen).

