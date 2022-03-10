# Ω Text Style

Every experience designed for a screen needs a well-designed visual hierarchy to its content. The goal of a typographic hierarchy is to present material so that the most important things are displayed with the highest visual impact. This helps the user in their quick scan for key information on a screen. This is achieved through the types size, weight, color, contrast, consistency of location, alignment, and spacing from other elements on the screen.

To set the properties for type, in a Theme we use the Text Style which establishes a typographic scale of sizes for use in the base application. The text style we create is then referenced by all elements and components for consistency in the design. Design Tokens are used with the styling in place of inline styling in ALL aspects of the application.

The Text Style is used to establish different sized and spaced text on a progressive scale. Color, shadowing and other treatments are **not** handled at the Type Style level but exist in their own styling library or dictionary and applied as a property to elements and components.

### Properties

These are the values that each font "type" carries as part of a grouping of "text" together as a "styling".

**Name**: \[textfield] The human readable way we refer to this "type" in the "type scale"

**Family**: \[selectList(Assets.Fonts)] The font family that is being used as the base. The list of available font families is pulled from the Assets > Fonts folder. Those fonts that have been uploaded into the system.

**Size**: \[slider-tick(1-99;12)] This is the digital pixel size of the font

**Weight**: \[selectList] This is the weights available for the font that is selected (i.e.. Normal, Bold, Medium, etc.)

**Transform**: \[selectList(Normal, Uppercase, Lowercase, Capitalized; Normal)] The ways that text should be changed in the end product, independent of how it was entered/read (i.e.. Normal, Uppercase, Lowercase, Capitalized)

**Style**: \[selectList(Normal, Underline, Italic, Line Through; Normal)] How the text should appear (i.e.. Normal, Underline, Italic, Line Through)

**Line Height**: \[slider-tick(0-99;150% of size above)] The height of text when line wraps are used. The rule of thumb for fonts is to set the line height at approximately 150% of the font size, as a starting point.

**Letter Spacing**: \[slider-tick(-50 to 50;0)] To alter the space between characters in logical pixels we use letter spacing. These can be positive and negative numbers with the default being zero or what the font otherwise carries for a value.

**Referenced By**: \[textArea.ReadOnlyCsvList] The list of elements and components that are referencing this dictionary

**Token**: \[textfield(#)] The short-code we use to refer to this type (i.e.. #H1, #H2, #R1, #R2 , #R4B etc.)

### Base Type Scale

| **Name**       | **Family** | **Size** | **Weight** | **Transform** | **Style** | **Line Height** | **Letter Spacing** | **Token** |
| -------------- | ---------- | -------- | ---------- | ------------- | --------- | --------------- | ------------------ | --------- |
| Header 1       | Lato       | 40       | Regular    | Normal        | Normal    | 48              | 0                  | #H1       |
| Header 2       | Lato       | 32       | Regular    | Normal        | Normal    | 40              | 0                  | #H2       |
| Header 3       | Lato       | 24       | Regular    | Normal        | Normal    | 32              | 0                  | #H3       |
| Regular 1      | Lato       | 20       | Regular    | Normal        | Normal    | 24              | 0                  | #R1       |
| Regular 1 Bold | Lato       | 20       | Bold       | Normal        | Normal    | 24              | 0                  | #R1B      |
| Regular 2      | Lato       | 16       | Regular    | Normal        | Normal    | 24              | 0                  | #R2       |
| Regular 2 Bold | Lato       | 16       | Bold       | Normal        | Normal    | 24              | 0                  | #R2B      |
| Regular 3      | Lato       | 14       | Regular    | Normal        | Normal    | 16              | 0                  | #R3       |
| Regular 3 Bold | Lato       | 14       | Bold       | Normal        | Normal    | 16              | 0                  | #R3B      |
| Regular 4      | Lato       | 12       | Regular    | Normal        | Normal    | 16              | 0                  | #R4       |
| Regular 4 Bold | Lato       | 12       | Bold       | Normal        | Normal    | 16              | 0                  | #R4B      |

### JSON

The file for the font we use in the base design system (Lato) can be found under the folder properties > styles > font.json. That file points to the location of that font asset in the style. It doesn't provide the sizing of the text to be used in the design system. The text size used in the design is referenced in the styles > size > font.json where you will see the sizes for other objects in the design system listed as their own json files.
