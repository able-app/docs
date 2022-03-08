# Themes

This is a good introduction to themes in a design system like we're creating here. [https://bradfrost.com/blog/post/creating-themeable-design-systems/](https://bradfrost.com/blog/post/creating-themeable-design-systems/)

Fundamentally, theming is used to modify "skin" existing elements and components to apply a visual style to an application. However, themes can control far more than a change in the colors. The theme in the ABLE design system consists of the following style, dictionary and library files:

- Color Styles
- Text Styles
- Effect Styles (Shadows & Treatments)
- Icon Library
- Illustration Library
- Brand Library
- Spacing Dictionary
- Size Dictionary
- Time, Interaction, Motion, Audio, Haptic Dictionaries

Each of these files is referenced in the Theme file and can be swapped out for other like-kinds to get a different experience. The easiest example of this is with Color Styles, where the visual colors of the app can be swapped out for a different look. Using this structure eliminates the need to modify each individual element and component to achieve the desired style. Themes control the design across all delivery platforms from a central set of theme files.

## Modes

Theme's have modes for lighter colors that create a sense of open space, and dark or black colored backgrounds that tend to jump out at you. These modes are set within the Styles, Dictionaries, and Libraries, and the theme controls which mode is displayed.

The base "default" theme comes in light and dark variations for use in different environments. Dark mode provides added visible contrast for low-light conditions. Light mode is often used in apps that are focused on productivity with easy to read text for extended work streams. However, there may be the desire for high contrast modes for those with visual disabilities. This choice of theme "mode" will provide for those added abilities.

* Light \(default\)
* Dark
* Light - High Contrast
* Dark - High Contrast

### Properties

**Name**: \[textField\] This is the human readable name for the theme.

**Description**: \[textArea] A description of the theme.  For example, a brand could have different theme's based on the season (holiday season). Where the illustrations and icons could change in appearance from their base state.

**Color Style:** [selectList(colorStyle:List)] the colors used throughout all design systems objects

**Text Style:** [selectList(textStyle:List)] the fonts, sizes, and line heights used throughout all design system objects

**Effect Style:** [selectList(effectStyle:List)] the visual effects applied to different objects on the screen, the best example being drop shadows to show elevation

**Icon Library:** [selectList(iconLib:List)] the visual metaphors used in the application to give guidance on an objects purpose.

**Illustration Library:** [selectList(illustLib:List)] visuals to tell a story that add to the purpose of the screen or the message we want the user to understand.

**Brand Library:** [selectList(brandLib:List)] Those assets that are brand specific, logos, wordmarks, letter mark, pictorial mark, mascots, etc. in set demensions (1:1, 4:3, etc.) for use in Iconography, Illustrations and Graphics.

**Spacing Dictionary:** [selectList(spaceDic:List)] the distance between objects (elements and components) in the layout.  This follows the 8 point grid system.

**Size Dictionary:** [selectList(sizeDic:List)] the standardized sizing for set groups of elements and components.  This keeps like-objects (those that can be substituted for one another) of the same size, to not break the parent object (element or component)

**Time Dictionary:** [selectList(timeDic:List)] the duration something will last. For example, a "Delay" for when an event is triggered after a certain amount of time the activity will take place.  This could also be the amount of time the activity takes to complete as well.

**Interaction Dictionary:** [selectList(interactDic:List)] the methods that a user can interact with the application. Tap, swipe left, swipe right, long press

**Motion Dictionary:** [selectList(motionDic:List)] a set of standardized visual activities that can be used to add motion to an element, component, sheet, screen etc. As an example, an error on a incorrectly entered password field, where the field could do a "Head Shake" motion.

**Audio Dictionary:** [selectList(audioDic:List)] sounds used to communicate with the user with sensory feedback.

**Haptic Dictionary:** [selectList(hapticDic:List)] the use of touch feedback to communicate with the user.  It's the vibration of your phone when you get a new email or the rumble in the controller when a hit happens in a game.



### Creating a New Theme

The base "default" theme files (styles & dictionaries, icons, illustrations, brand assets) are meant to act as a starting point \(aka template\) for the design of a new theme. Theme designers can define the aspects of a new theme that deviate from the base. That new theme is then packaged up with the new values under a new name for the theme.

