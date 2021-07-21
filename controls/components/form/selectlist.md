# SelectList

A value display with a list of choices on a temporary menu surface when activated. A selectlist is also referred to as a dropdown by many people.

Inner element spacing is used for dynamic resizing along with a background surface. 

[Styleguide Link](https://zpl.io/b6nGoKW)

- Parent: Form (Container)
- Child: [Field](https://github.com/able-app/docs/blob/2956b7cd57098e9f2c27ad3cb3ae8da4842dc0c0/controls/%CE%B5%20elements/field/field.md), [Label](https://github.com/able-app/docs/blob/2956b7cd57098e9f2c27ad3cb3ae8da4842dc0c0/controls/%CE%B5%20elements/label.md), [Menu](https://github.com/able-app/docs/blob/2956b7cd57098e9f2c27ad3cb3ae8da4842dc0c0/controls/components/menu.md)

## Properties

**Label** - The component can be presented with a label to give context to the form control.  This label can be positioned top (above the field), left, or not at all (none).

**Helper** - Does the component have helper text (On/Off). This is used to provide additional context for the component for examples, how the input will be used, or as further clarification to the label.

**Choice Method** - There are a few options when working with the selectable choices of a SelectList. 

- **Standard Dropdown** -  A temporary modal Menu element that is displayed over top (elevated above) the visible SelectList - Field. This works great for shorter lists of content options (<10).
- **Autosuggest Dropdown** - When the list of options within the SelectList is longer or infinite and the user already knows the answer, the SelectList - Field acts as a field to collect, autocomplete (the typed word) and filter the results in the Dropdown (displayed directly below the SelectList - Field) of the typed characters.  This is similar to how the Google search box works.  Another good example of this in use is in choosing a country.
- **Sheet: Listview** - For lists that are a bit longer and will need scrolling within the ListView to account for all options we can use a standard sheet (with its three heights) that appears from the bottom of the screen.
- **Screen: Listview** - For very large lists and those that might need a graphic, adaptIcon, and/or additional context with a description, we can navigate directly to (as opposed to the sheet first) a new screen where the full screen is displaying the list, where a choice would navigate the user back to the original screen where the SelectList was first presented and now shows the choosen option in the Field.

**Note:** The structure and spacing of this component is the same between Textfield, Textarea, Selectlist, Chiplist, Slider, Userlist, and Toggle Button.

**Note:** Each of the nested elements and primitives of this form component have properties that can be adjusted to customize the component.
