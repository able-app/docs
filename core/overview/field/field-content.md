# Θ Field - Content

Container: A grouping for design convenience for display in a field. This base level collection feeds into the Field element.

[Styleguide Link](https://zpl.io/V0zMJMO)

* Parent: [Field](./)
* Child: [Label](../label.md), [Chip - Bar](../chip/chip-bar.md)

## Properties

### Types

* **Textfield** - For short form text content that can exist as a single-line field (no wrapping and growing of the field height) or as a multi-line field that grows as additional lines of content are added [See MD](https://material.io/components/text-fields#input-types)
* **Textarea** - For long form text content with a fixed height field
* **Selectlist** - For defined sets of selectable content
* **Chiplist** - objects (chips) added to a collection in the field. Note: This can exist as a single-line (default) or multi-line field, the same as with textfield above. Thus resulting in chips that side-scroll (single-line), or wrap to the next line (multi-line).

### Input Field - Ornamentation

**Leading Icon** - Either to signify the type of input a field uses (ex. Calendar, bringing up a calendar modal), or as an alternative to the text label for a more minimal look.

**Trailing Icon** - Used at the end of a field to visually describe input methods as a metaphor (ex. Microphone for audio). Where the microphone is a tappable area that will initiate the audio collection method of entering content into the field.

### Content

**Placeholder** - To provide the user with some helpful context to what should exist in the field, and the format that it should be. For example, a phone number (555) 555-5555 as a placeholder to gentally suggest the format.

**Input** - The content that the user is adding to the field

### Auto Formatting

In situations like the phone number example from above, we can establish auto formatting to automatically give the contents the proper format with the ()'s as the user types just numbers into the field.
