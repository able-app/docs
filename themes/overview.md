# Themes

This is a good introduction to themes in a design system like we're creating here. [https://bradfrost.com/blog/post/creating-themeable-design-systems/](https://bradfrost.com/blog/post/creating-themeable-design-systems/)

Fundamentally, theming is used to modify "skin" existing elements and components to apply a visual style to an application. However, themes can control far more than a change in the colors. It’s a way of modifying the way a screen is displayed or a series of screens flow, without changing the underlying application. This eliminates the need to modify each individual element and component to achieve the desired style. Themes control the design across all delivery platforms from a central set of theme files.

## Modes

Lighter colors create a sense of open space. Users typically don’t notice a light or white background; however, a dark or black background will tend to jump out at them. This is because of the visual weight that dark colors carry.

The base "default" theme comes in light and dark variations for use in different environments. Dark mode provides added visible contrast for low-light conditions. Light mode is often used in apps that are focused on productivity with easy to read text for extended work streams. However, there may be the desire for high contrast modes for those with visual disabilities. This choice of theme "mode" will provide for those added abilities.

* Light \(default\)
* Dark
* Light - High Contrast
* Dark - High Contrast

### Properties

**Name**: \[textField\] This is the human readable name for the theme.

**Values**: \[textField w/ colorSelect icon\] These are the HEX, Font, numeric values for this theme

**Token**: \[textField\] The design token is our machine readable way of linking from these theme to the elements and components it is adjusting.

**Purpose\(s\)**: \[selectList-Multi\(\)\] How the token is used in the design system. It's which elements and components are a part of this theme and how they are used. A purpose is linked with an element or component, along with its properties and is consistent between themes.

### Creating a New Theme

The base "default" theme is meant to act as a starting point \(aka template\) for the design of a new theme. Theme designers can define the aspects of a new theme that deviate from the base. That new theme is then packaged up with the new values under a new name and design token for the theme.

