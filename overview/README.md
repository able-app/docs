---
description: How applications get there look and feel
---

# Themes

This is a good introduction to themes in a design system like we're creating here. [https://bradfrost.com/blog/post/creating-themeable-design-systems/](https://bradfrost.com/blog/post/creating-themeable-design-systems/)

Fundamentally, theming is used to modify "skin" existing elements and components to apply a visual style to an application. However, themes can control far more than a change in the colors. The theme in the ABLE design system consists of the following style, dictionary and library files:

* [Color Styles](styles/color.md)
* [Text Styles](styles/typography.md)
* [Effect Styles](styles/effect.md) (Shadows & Treatments)
* [Icon Library](iconography.md)
* [Illustration Library](illustration.md)
* [Brand Library](o-brand-library.md)
* [Spacing Dictionary](styles/spacing.md)
* [Size Dictionary](styles/size.md)
* [Time](styles/o-time-dictionary.md), [Interaction](styles/o-interaction-dictionary.md), [Motion](styles/motion.md), [Audio](styles/audio.md), [Haptic Dictionaries](styles/haptic.md)

Each of these files is referenced in the Theme file and can be swapped out for other like-kinds to get a different experience. The easiest example of this is with Color Styles, where the visual colors of the app can be swapped out for a different look. Using this structure eliminates the need to modify each individual element and component to achieve the desired style. Themes control the design across all delivery platforms from a central set of theme files.

## Style Dictionary

From the developers point of view a theme and all of these libraries and color palettes are built as "style dictionaries" and referenced in their code. [Style Dictionary](https://amzn.github.io/style-dictionary/#/) is a build system that allows us to define styles and assets once, in a way for any platform or language to consume. This is a simple JSON file championed by the talented designer/developers over at Amazon. Read more about Style Dictionary in their [GitHub documentation](https://amzn.github.io/style-dictionary/#/). We build with Style Dictionaries to allow the Design System to grow beyond it's initial single platform (React Native), to others (Flutter, Native iOS & Android, etc.)

**Libraries**

We refer to assets that exist as external files (photos, graphics, audio/video, etc.) as libraries. By establishing libraries for these things we can swap out one library for another easily. For example, let's say at Christmas time we want to have customized Illustrations to reflect the season. Simply swap the reference to the "Illustrations - Thanksgiving" library for the "Illustrations - Christmas" library and it's ready to go. Another byproduct of this is that it provides a compartmentalized work area for the Illustrator to work and store like objects, that carries a consistent structure.

## Dessign Tokens

Design Tokens are key-value pairs that represent the specs of the design system. They are the atomic, reusable building blocks of a design system, such as colors, typography, spacing, motion, and even sounds and haptic feedback. In code these are referred to as constants.

In design systems, tokens are used in place of hard-coded values of visual primitives to ensure flexibility and cohesiveness across all products.

Design tokens allow teams to better collaborate and ensure brand consistency across multiple products, platforms, and media. A theme is a collection of tokens, each with a defined role. For example, a token for a color may be #primary and is used in all instances that a primary color is used. For colors the token simply stores the RGBA value. For typography tokens work the same way, assigning type styles based on the token role. For example, H1 is used for prominent typography like headlines. Type tokens store the full range of type settings including: font-size, line-height, letter-spacing, as well as breakpoint sizing changes.

## Semantic Token Aliases

Token aliases let you relate a semantic token to a base "primitive" token for a specific context to get a level of abstraction. This helps us communicate the intended purpose of a token, independent of the actual/primitive value of the token. Think of semantic tokens as design decisions on style primitives.

As an example of this, when creating a semantic tokens for the light and dark modes of a theme we have primitive color style tokens for "White" and "Black" that store the actual color values and that's the same for all themes. On a second level, the semantic level, we have tokens for "Background Color" and "Text Color". In the light mode, the Background Color semantic token is defined as an alias of White, and Text Color's semantic token is an alias of the Black primitive token.

For the dark mode of the theme, instead of changing the actual values of our primitive tokens (the Black & White tokens), we'd edit our semantic tokens and switch the aliased tokens. To learn more about semantic tokens, this is a good series of articles. [https://dev.to/ynab/a-semantic-color-system-the-theory-hk7](https://dev.to/ynab/a-semantic-color-system-the-theory-hk7)

## Modes

Theme's have modes for lighter colors that create a sense of open space, and dark or black colored backgrounds that tend to jump out at you. These modes are set within the Styles, Dictionaries, and Libraries, and the theme controls which mode is displayed.

The base "default" theme comes in light and dark variations for use in different environments. Dark mode provides added visible contrast for low-light conditions. Light mode is often used in apps that are focused on productivity with easy to read text for extended work streams. However, there may be the desire for high contrast modes for those with visual disabilities. This choice of theme "mode" will provide for those added abilities.

* Light (default)
* Dark
* Light - High Contrast
* Dark - High Contrast

### Properties

**Name**: \[textField] This is the human readable name for the theme.

**Description**: \[textArea] A description of the theme. For example, a brand could have different theme's based on the season (holiday season). Where the illustrations and icons could change in appearance from their base state.

**Color Style:** \[selectList(colorStyle:List)] the colors used throughout all design systems objects

**Text Style:** \[selectList(textStyle:List)] the fonts, sizes, and line heights used throughout all design system objects

**Effect Style:** \[selectList(effectStyle:List)] the visual effects applied to different objects on the screen, the best example being drop shadows to show elevation

**Icon Library:** \[selectList(iconLib:List)] the visual metaphors used in the application to give guidance on an objects purpose.

**Illustration Library:** \[selectList(illustLib:List)] visuals to tell a story that add to the purpose of the screen or the message we want the user to understand.

**Brand Library:** \[selectList(brandLib:List)] Those assets that are brand specific, logos, wordmarks, letter mark, pictorial mark, mascots, etc. in set demensions (1:1, 4:3, etc.) for use in Iconography, Illustrations and Graphics.

**Spacing Dictionary:** \[selectList(spaceDic:List)] the distance between objects (elements and components) in the layout. This follows the 8 point grid system.

**Size Dictionary:** \[selectList(sizeDic:List)] the standardized sizing for set groups of elements and components. This keeps like-objects (those that can be substituted for one another) of the same size, to not break the parent object (element or component)

**Time Dictionary:** \[selectList(timeDic:List)] the duration something will last. For example, a "Delay" for when an event is triggered after a certain amount of time the activity will take place. This could also be the amount of time the activity takes to complete as well.

**Interaction Dictionary:** \[selectList(interactDic:List)] the methods that a user can interact with the application. Tap, swipe left, swipe right, long press

**Motion Dictionary:** \[selectList(motionDic:List)] a set of standardized visual activities that can be used to add motion to an element, component, sheet, screen etc. As an example, an error on a incorrectly entered password field, where the field could do a "Head Shake" motion.

**Audio Dictionary:** \[selectList(audioDic:List)] sounds used to communicate with the user with sensory feedback.

**Haptic Dictionary:** \[selectList(hapticDic:List)] the use of touch feedback to communicate with the user. It's the vibration of your phone when you get a new email or the rumble in the controller when a hit happens in a game.

### Creating a New Theme

The base "default" theme files (styles & dictionaries, icons, illustrations, brand assets) are meant to act as a starting point (aka template) for the design of a new theme. Theme designers can define the aspects of a new theme that deviate from the base. That new theme is then packaged up with the new values under a new name for the theme.
