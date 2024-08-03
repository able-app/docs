# ε Field

Element: A form field that can accept text, a selection from a list of choices (SelectList) or the adding of objects (Chips) to a collection.

This is where we combine all of the feeder primitive and base level pieces to form the field element.

[Styleguide Link](https://zpl.io/boA1gkW)

* Parent: [Textfield](../../components/form/textfield-1.md), [Selectlist](../../components/form/selectlist.md), [Textarea](../../components/form/textarea.md) (All Form Components)
* Child: [Field - Content](field-content.md), [Field - Helper](field-helper.md), [Field - Container](field-container.md), [FieldShape](field-shape.md)

## Properties

### Types

* Textfield - The field type used in the Textfield Form component for free-form text input
* SelectList - A field type used in the Selectlist Form component for selecting from a defined collection of choices.
* ChipList - A Field with chips contained inside of it, with a side-scroll to reveal additional chips. This field can have chips added to or removed from, using controls outside of the field. Ex. GA - Assign to where avatars are added to a collection field from a list of users.

<figure><img src="../../../.gitbook/assets/Type (4) (1).png" alt=""><figcaption></figcaption></figure>

### Validation

For the most part all validation should be handled inline. Meaning as soon as you've finished filling in a field, an indicator should appear in the field if there's an error. This makes fixing the error easy to identify and allows you to fix it immediately after the field has been completed.

Of course, there are some situations where inline validation won’t be possible and data entered will need to be sent to a server for verification.

Note: Do not validate the field until it is completed. We can give a positive feedback of real-time validation of say an email address once we detect the dot extension but don't give negative feedback along the way as they are typing in the value.

A good source of proper field/error handling is the NN/g, [here's a good starting point](https://www.nngroup.com/articles/errors-forms-design-guidelines/).
