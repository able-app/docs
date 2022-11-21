# ε ToggleBar

Element: A collection of toggles with layout padding and behaviors. The bar component can have different background surfaces (colors) so we don't include a surface here.

[Styleguide Link](https://zpl.io/adyA535)

* Parent: [App Bar - Ext.](../../components/app-bar/app-bar-ext.md), [Form > Toggle Button](../../components/form/togglebutton.md)
* Child: [Toggle - Ctrl](./)

## Properties

### Layout Types

The options available in the "Toggle" element are capable here.

**Solo** - A grouping of solo toggles. An example of this could be different filters on a search, where each toggle is a different filter type (price, weight, rating, etc.)

**Group** (default)- When the toggle buttons are pushed together and are presented as a grouping of buttons. By default, this type exists as a singular choice (toggle on) from the group, but can function as a multi-select button as well. An example of this would be with a text editor grouping with bold, italic, underline where none or all of the groups options can be selected.

<figure><img src="../../../.gitbook/assets/Toggle Bar.png" alt=""><figcaption></figcaption></figure>

### Style

* Text (default)
* Icon

### Behavior

* **Fixed** (default)- New toggles that don't fit within the fixed width, wrap to the next row, growing the height of the bar - toggle.
* **Scroll** - Toggles that don't fit within the defined width of the parent container scroll off the side of the bar - toggle (screen).
