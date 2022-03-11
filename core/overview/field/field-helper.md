# Θ Field - Helper

Container: A Primitive collection for helper text that makes up the Field (element). This collection feeds into field components (textfield, selectlist, textarea, etc.) as the consistent method for handling helper content for fields.

[Styleguide Link](https://zpl.io/2vD1X45)

* Parent: [Field](./)
* Child: [Label](../label.md)

## Properties

### Types

* Label left with text wrapping, for helper text that might need to wrap to a second line
  * Ex. Help: Choose a unique public @username
  * Ex Error: That username is already being used
  * Ex. Success: Your public profile: able.app/p/username
* Label right, often short and used for character counts on fields (no text wrapping)
* Label left & right (both the above)

### Interaction

Base on the input given to the field, this helper content may change to reveal additional contextual information, such as error, warning, success, or additional helper content. That content would return to its base state, when/if the contents of the input field are cleared (using the clear icon on the right side of the field or backing out the contents with the back arrow on the keyboard).
