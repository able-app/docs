# Field

Element: A form field that can accept text, a selection from a list of choices (SelectList) or the adding of objects (Chips) to a collection.

This is where we combine all of the feeder primitive and base level pieces to form the field element.

[Styleguide Link](https://zpl.io/boA1gkW)

- Parent: [Textfield](https://github.com/able-app/docs/blob/7bb2457d172a78e9e6528e086a642c45224c701f/controls/components/form/textfield.md), [Selectlist](https://github.com/able-app/docs/blob/7bb2457d172a78e9e6528e086a642c45224c701f/controls/components/form/selectlist.md), [Textarea](https://github.com/able-app/docs/blob/7bb2457d172a78e9e6528e086a642c45224c701f/controls/components/form/textarea.md)
- Child: [Field - Content](https://github.com/able-app/docs/blob/78b7d0a469492d69eba8f33ae838468642242f52/controls/%CE%B5%20elements/field/field-content.md), [Field - Helper](https://github.com/able-app/docs/blob/78b7d0a469492d69eba8f33ae838468642242f52/controls/%CE%B5%20elements/field/field-helper.md), [Field - Container](https://github.com/able-app/docs/blob/78b7d0a469492d69eba8f33ae838468642242f52/controls/%CE%B5%20elements/field/field-container.md), [Field - Shape](https://github.com/able-app/docs/blob/7bb2457d172a78e9e6528e086a642c45224c701f/controls/%CE%B5%20elements/field/field-shape.md)

### Types

- Textfield - The field type used in the Textfield Form component for free-form text input
- SelectList - A field type used in the Selectlist Form component for selecting from a defined collection of choices.
- ChipList - A Field with chips contained inside of it, with a side-scroll to reveal additional chips.  This field can have chips added to or removed from, using controls outside of the field. Ex. GA - Assign to where avatars are added to a collection field from a list of users.

### Validation

For the most part all validation should be handled inline. Meaning as soon as you've finished filling in a field, an indicator should appear in the field if there's an error. This makes fixing the error easy to identify and allows you to fix it immediately after the field has been completed.

Of course, there are some situations where inline validation won’t be possible and data entered will need to be sent to a server for verification.

Note: Do not validate the field until it is completed.  We can give a positive feedback of real-time validation of say an email address once we detect the dot extension but don't give negative feedback along the way as they are typing in the value.

A good source of proper field/error handling is the NN/g, [here's a good starting point](https://www.nngroup.com/articles/errors-forms-design-guidelines/).
