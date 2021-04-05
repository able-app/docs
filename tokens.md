# Tokens

Design tokens are named entities \(hooks\), that store design attributes in a simple key-value store. They are the link between the "Design System" and the coded application. We use them in place of hard-coded values \(such as font sizes for type, hex values for color, or pixel values for spacing\). This provides us with a scalable and consistent visual system for the user interface.

## Types of Design Tokens

* Font weight, size, line-height
* Colors of backgrounds, text, and borders
* Shadows
* Iconography \(Metaphor Library\)
* Spacing & Sizing Scales
* Animation durations
* Z-layers
* Breakpoints

With "Design Tokens" you can store these values in a central location our "Token Library" and distribute them to all of the various display platforms \(watch, phone, tablet, web, desktop, tv\) in a consistent way and have the design react as it should.

## Breakpoints

To make our components usable and react to the size of the display they are on, we use standard breakpoints. These are natural digital pixel breakpoints between each of the platforms. Here, Google explains there Material Design breakpoints. [https://material.io/design/layout/responsive-layout-grid.html\#breakpoints](https://material.io/design/layout/responsive-layout-grid.html#breakpoints)

| watch | &lt;359 |
| :--- | :--- |
| handset | 360-599 |
| tablet | 600-1439 |
| Web/desktop | 1440+ |

## Metaphor Library

The objects stored in the metaphor library are icons that act as the visual queues to activities. These icons are assigned a design token in the metaphor library and then referenced in screens, components, elements ect. throughout the application. By creating a metaphor library for these visual queues we provide the ability to swap an icon out globally, without going into every single instance where it is used in elements, components, and screens throughout an application.

