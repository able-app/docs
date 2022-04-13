# Textfield

A form component that provide the ability to enter and edit text in a defined layout with inner element (Label, Field, Button) spacing for dynamic resizing.

[Styleguide Link](https://zpl.io/V1EdG6Q)

* Parent: Form (Container)
* Child: [Field](../../overview/field/), [Label](../../overview/label.md), [Button](../../overview/button/)

## Properties

**Label** - The component can be presented with a label to give context to the form control. This label can be positioned top (above the field), left, or not at all (none).

**Helper** - Does the component have helper text (On/Off). This is used to provide additional context for the component for examples, how the input will be used, or as further clarification to the label.

**Button** - In certain situations there may be the need to add a button next to the field (ex. upload of a file). This property turns that button on/off.

**Field: Type** - In some situations, like in a sheets search field, we may want to invert the appearance of the field to make it stand out a little better. This property makes that possible.

## Functionality

**Single-line fields**

In single-line fields, when the cursor reaches the right edge of the field, text longer than the field input automatically scrolls left.

Single-line fields are used to collect short input values, any scrolling of text beyond the view is for usability purposes and should not be used for longer form content. For those, use either the multi-line option for a textfield or the Textarea component.

**Multi-line fields**

Multi-line text fields provide an overflow text wrap to the next line when the cursor reaches the end of the field. This causes the text field to expand (growing the field down).

A multi-line field initially shows as a single-line fields, for a compact layout.

**Note:** The structure and spacing of this component is the same between Textfield, Textarea, Selectlist, Chiplist, Slider, Userlist, and Toggle Button.

**Note:** Each of the nested elements and primitives of this form component have properties that can be adjusted to customize the component.

{% embed url="https://www.figma.com/proto/VN320MmRlLNR0UmdFula6N/Kitchen-Sink?node-id=2%3A24702&page-id=0%3A1&scaling=min-zoom&starting-point-node-id=2%3A24884&viewport=377%2C48%2C0.14" %}
