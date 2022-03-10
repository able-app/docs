# Ω Effect Library

## Type - Shadow

Shadows give objects on the screen depth, elevation, and define the edges of an object. The shadow is set based on its elevation and relationship to the surfaces of other objects. With any application there will be the need for some level of shadow to show elevation. To provide a scalable, consistent, and an easy way to manage shadow across the app we use Effect Styles for shadows. Most won't find the need to customize the defaults set in the "Base" shadows but the ability exists to over-ride those at the theme layer. Also, we can build additional shadow dictionaries for specific elements and components to keep the design consistent. For example, if we wanted to limit the shadow options available to a Card component we could create a shadow dictionary for cards and reference those in the shadow styling options of a card rather than the Base shadow.

## Type - Treatment

These are the treatments that are applied to screen objects. The best example of this is a Frosted Glass appearance that can be applied to a photo.

### Properties

**Name**: \[textField] The human readable dictionary name for this "Shadow" option. (i.e. Base, Card)

**Thumbnail**: \[fileAdd - optional] The visual to represent this object

**Description**: \[textArea - optional] Context to understand what the object is

**Token**: \[textField] The short-code we use to refer to this dictionary (i.e.. #shadBase, #shadCard etc.)

**Referenced By**: \[textArea.ReadOnlyCsvList] The list of elements and components that are referencing this dictionary

A single dictionary "source of truth" is referenced across multiple elements, components and screens to provide the shadow properties for that object in the design system.

## Add Entry

These are the individual "entries" added to this shadow style. As an example we have a Base shadow "Effect Style" which is referenced from all visible screen objects in the design system. That style has options from None to Huge. Now when we are building a component with an object in it, we have those options available to us. If we want to go into greater detail for a particular element or component on the screen we can create a new shadow family to represent that element or component, in essence, overriding the Base shadow family.

### Properties

**Name**: \[textField] The human readable way we refer to this "Shadow" option in the Effect Style. (i.e. XS, M, L)

**Blur**: \[slider-tick(0-25;0)] This is the digital pixel size

**Spread**: \[slider-tick(0-25;0)] This is the digital pixel size

**Color**: \[selectList(ColorStyle.Shadow)] This pulled from a color style, created for shadow which has a base of Black and three alpha levels (.2, .14, .12)

**Horizontal Offset**: \[slider-tick(-100 - +100;0)] This is the digital pixel size

**Vertical Offset**: \[slider-tick(-100 - +100;0)] This is the digital pixel size

**Token**: \[textField(#)] The short-code we use to refer to this shadow type in the Effect Style (i.e.. #shadBaseS, #shadCardM etc.)

## Base Style Entries

We will use the material design shadows as our base, mapping each of the base shadow tokens to its equivalent value that can be found here.

[https://github.com/flutter/flutter/blob/master/packages/flutter/lib/src/material/shadows.dart](https://github.com/flutter/flutter/blob/master/packages/flutter/lib/src/material/shadows.dart)

| Name | Size | Token         |
| ---- | ---- | ------------- |
| None | 0    | #shadBaseN    |
| XXXS | 1    | #shadBaseXxxs |
| XXS  | 2    | #shadBaseXxs  |
| XS   | 3    | #shadBaseXs   |
| S    | 4    | #shadBaseS    |
| M    | 6    | #shadBaseM    |
| L    | 8    | #shadBaseL    |
| XL   | 9    | #shadBaseXl   |
| XXL  | 12   | #shadBaseXxl  |
| XXXL | 16   | #shadBaseXxxl |
| Huge | 24   | #shadBaseH    |

NOTE: Any dictionaries or styles designated as a Base, can not be deleted. They act as the defaults for other elements and components up the line.
