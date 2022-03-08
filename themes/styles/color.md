# Ω Color Style

Within the design system we have a base color style based off of Google's material design palette with ten different weights for each hue, ranging from 50 \(lightest\) to 900 \(darkest\). When using these colors we suggest that you start with the 500 weight color and move up \(Shade\) and down \(Tint\) in numeric weight. Each of these colors carries it's design token for reference within the code.

To set the properties for color in a Theme, we use Color Style's. This is our base level color style for a theme but we could also have multiple color styles that follow their own color schemes. For example, a color picker available to app users may have a limited number of colors, which would be defined in a "Picker Palette" color styles file. These separate color style files help us to organize our color palettes into logical families, which can then be references from a theme.

## Mode

Every Color Style file has at least two modes, Light (default) and Dark. With the ability to add additional modes if needed, for example High Contracts - Light, Mode.  All designs are done in the Light mode.

## Properties

The fields that are needed to describe the color, its tint or shade and any other properties carried with the color.

**Name**: \[textField\] This is the human readable name for the color. In the case of the material design system we have nine "parent" primary colors with different tints and shades "children" which we follow a systematic naming convention for. For example, we have a "parent" primary color of Purple with "child" tints and shades running from 050 to 900. So as a name we would use "purple500" as a name when referring to that color.

**Value**: \[textField w/ colorSelect icon\] This is the HEX value for the color with the alpha at the end \(\#RRGGBBAA\). In our \#purple500 from above example, the value would be \#3F51B5FF. NOTE: There's only one value that a color carries, however it could be a gradient which would be a number of different colors that fade from one color to the next.

**Token**: \[textField\] The design token is our machine readable way of linking from the element or component back to the theme and style dictionaries. For example with Purple we have a design token of \#purple500.

**Referenced By**: \[textArea.ReadOnlyCsvList\] The list of elements and components that are referencing this style

## Attributes

This is where we will attach any meta data we'd like the object to carry. One example of this is how text should be treated when this color is the background behind that text \(so it can be read\).

**Font**: \[selectList\(base,inverse;base\)\] We have an attribute for color when it comes to fonts that would overlay a color. For those colors that should use the "base" Neutral color \(with a Light Mode, that would be Black\). For those listed as "inverse" the opposite Neutral color would be used \(ie. White\). These values are later used as default text colors for fonts that are overlaid on top of a background color, ie. Button with a background design token of @purple500 would use an "inverse" overlay color \(white\) as its default. This is to ensure that wording on top of a color is readable.

## JSON

The file for color can be found in the style dictionary under the folder properties &gt; styles &gt; color. In that folder you'll see a few json files: base, which is our base color palette \(used to change the color of basic shapes, lines and even svg icons\), our font colors \(available in the GUI when you want to change the color of a font\) and our theme colors \(available in the GUI when altering the theme properties\). If a color is represented in the design it will have a reference in one of the files in this folder.

