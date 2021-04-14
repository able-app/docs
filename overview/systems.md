# systems

The design system is made up of multiple “UI Kits” aka files, that collectively make up a multi-tiered design system. This is often referred to as the "System of Systems". Best practices built into our design tools allow the use of shared design libraries, with role based access control. These files and asset libraries along with the [atomic design principles](https://bradfrost.com/blog/post/atomic-web-design/), are at the core of the design system.

For example, managing icons in a different file than the components, separated from a data visualization module that inherits colors from a brand theme.

This compartmentalizes the features and functionality of the design system, allowing for easier updates \(Ex. Swapping out all icons for a different style as tastes change\), and governance to keep things consistent at a high level.

### Kit Structure

| **Level 00 - Design System** | **Level 01 - Brand** | **Level 02 - Product** |
| :--- | :--- | :--- |
| - Screen Templates - Elements & Components - Theme \(Base\) - Libraries \(Brand, Icon, Ill, etc.\) - Color Palettes - Flow Kits | - Brand Themes - Brand Libraries - Icon Libraries - Illustration Libraries - Animation Libraries | - Product 01 \(Customer\) - Product 02 \(Employee\) - Product 03 \(Admin\)  |

![ds-architecture](../.gitbook/assets/ds-architecture.png)

**The diagram above is covered in greater detail below**

## Level 00 - Design System Kits

These kits make up our Design System \(DS\) that acts as the foundation of everything we build. These core kits, aka "files" are shared with the other levels in a cascading format. Meaning that objects and tokens at a higher level can over-ride those below them. These reusable pieces of the design system follow an atomic design architecture which is mirrored at each level. We break that atomic structure into the following layers.

### Particles Layer

Particle kits contains the lowest level objects of the “atomic design” system. These kits are:

* Themes
* Brand Library
* Icon Library
* Illustration Library
* Color Palettes
* Flow Kits \(helper files\)

_Note: As the design system expands we will add new kits to the particle layer, for example an animations library._

#### Themes

Themes provide the ability to stylize color, sizes, surfaces, interactions and effects that can be used across a single product, multiple products, or across the entire brand. Themes keep things consistent with the style "form" of an object, while the intent "function" is handled in other kits. Themes are valuable when we work with multiple products \(apps\) that may have slightly different stylings. An example of this being the difference between the Shipper and the Service Provider apps. Both have Sign-In screens and each have the same intent for a CTA button, but the styling may change from a primary blue with the Shippers CTA button to a primary of brown for the SP's CTA button.

So in Level 00 we establish base \(placeholder\) styles and at Level 01 & 02, over-ride those with our brand and product specific choices. This allows us to decouple all branding choices from the core design objects and their intent, while still providing the ability to customize styling with themes.

**Design Tokens**

Design Tokens are key-value pairs that represent the specs of the design system. They are the atomic, reusable building blocks of a design system, such as colors, typography, spacing, motion, and even sounds and haptic feedback.

In design systems, tokens are used in place of hard-coded values of visual primitives to ensure flexibility and cohesiveness across all products.

Design tokens allow teams to better collaborate and ensure brand consistency across multiple products, platforms, and media. A theme is a collection of tokens, each with a defined role. For example, a token for a color may be \#primary and is used in all instances that a primary color is used. For colors the token simply stores the RGBA value. For typography tokens work the same way, assigning type styles based on the token role. For example, H1 is used for prominent typography like headlines. Type tokens store the full range of type settings including: font-size, line-height, letter-spacing, as well as breakpoint sizing changes.

In addition to color and type tokens we also have tokens for:

* Shadows \(AKA, Effects in Figma\)
* Surface & Text Styles
* Interaction Styles \(Ex. Focus State\)
* Objects Sizes & Radius
* Breakpoints \(Screen Sizes\)

#### Semantic Token Aliases

Token aliases let you relate a semantic token to a base "primitive" token for a specific context to get a level of abstraction. This helps us communicate the intended purpose of a token, independent of the actual/primitive value of the token.

Think of semantic tokens as design decisions on style primitives.

As an example of this, when creating a semantic tokens for the light and dark modes of a theme we have primitive color style tokens for "White" and "Black" that store the actual color values and that's the same for all themes. On a second level, the semantic level, we have tokens for "Background Color" and "Text Color". In the light mode, the Background Color semantic token is defined as an alias of White, and Text Color's semantic token is an alias of the Black primitive token.

For the dark mode of the theme, instead of changing the actual values of our primitive tokens \(the Black & White tokens\), we'd edit our semantic tokens and switch the aliased tokens.

To learn more about semantic tokens, this is a good series of articles. [https://dev.to/ynab/a-semantic-color-system-the-theory-hk7](https://dev.to/ynab/a-semantic-color-system-the-theory-hk7)

#### Libraries

We refer to assets that primarily exist as external files as libraries. There are multiple libraries that we will pull assets from.

* Iconography
* Illustration
* Animation
* Audio

By establishing libraries we can swap out one library for another easily. For example, let's say at Christmas time we want to have customized Illustrations to reflect the season. Simply swap the reference to the "Illustrations - Thanksgiving" library for the "Illustrations - Christmas" library and it's ready to go. Another byproduct of this is that it provides a compartmentalized work area for the Illustrator to work and store like objects, that carries a consistent structure.

#### Style Dictionary

From the developers point of view a theme and all of these libraries and color palettes are built as "style dictionaries" and referenced in their code. [Style Dictionary](https://amzn.github.io/style-dictionary/#/) is a build system that allows us to define styles and assets once, in a way for any platform or language to consume. This is a simple JSON file championed by the talented designer/developers over at Amazon. Read more about Style Dictionary in their [GitHub documentation](https://amzn.github.io/style-dictionary/#/).

### Core

The next layer up in the Design System is our "core" file containing Elements and Components, which are the equivalent to Atoms and Molecules in the [Atomic Design](https://bradfrost.com/blog/post/atomic-web-design/) structure. _Note, we've added our own lower level of "Particles" to add a much needed layer to the Atomic Design structure._

#### Primitives

At both the Element and Component level we have the need to separate out parts of the object \(element or component\) into even more simplistic objects before combining them as an element or component. Primitives are how we classify these simple objects.

#### Elements

The individual primitive interface building blocks used to build components in the design system. These objects typically don't have much use on their own, but when combined with other elements to form a component serve a defined purpose. A few of the more common elements are:

* Checkbox
* Radio Button
* Switch
* Slider
* Label

#### Components

A component is an interface object built out of elements or by nesting other components, with a background surface and spacing, to serve as a reusable object in building interfaces. They’re the Lego pieces we stack together in a ScrollView to design experiences that are consistent. Components provide focus to the screen designer by solving user need when designing screens. This is the concept of an abstract component, where the focus is on the intent, as opposed to the interface. Think of an abstract component as the skeleton. And the manifestation at each breakpoint \(phone, tablet, desktop, web, etc.\), as the skin of the component handled by the Theme. A few of the more common components are:

* AppBar
* TabBar
* Headline
* ListItem
* GridView
* TextField

### Screens

This is where the elements and components from the Core layer are combined to form reusable modules and patterns at each breakpoint \(phone, tablet, web/desktop\). A few common modules and patterns are:

* Sign-In
* Profile
* User-ListView
* Object-ListView
* Image-GridView

In the design system at Level 00 these serve as templates to use when building screens, to avoid reinventing the wheel, and at the Brand and Product levels to customize those DS screens to the desired use case.

## Level 01 - Brand Kits

In the Brand level we use over-rides to alter the default design system Theme, Libraries, Palettes, and any other design system files to fit the styling of the brand. This brand level can have further over-rides at the product level for those changes between the different products, but the majority of the branding is done at this level.

#### Over-rides

Anything that exists at the design system layer can have an over-ride applied. The reasoning for having brand over-rides is to provide a mechanism for modular testing and granular change between segments of the audience. For example, let's say we're launching a product in a new city \(New York City\) and we'd like to swap out our city specific photos and illustrations. Those city specific libraries can be created and programmatically swapped out. Another scenario could be for testing out font changes for readability within a warehouse, swapping one file for another for a test group while keeping others on the main theme is a breeze.

## Level 02 - Product Kits

These kits are for specific products \(app, software, site, design etc.\) that we’re building. In here, we’ll store product-specific templates, patterns, modules, basically any customizations of level 00 design system layers, or level 01 branding. This keeps our design system focused on core concept and all customizations at a brand or product level.

### Other Products

We won’t go into level 02 kits outside of applications here. However, planning for future marketing kits for print and web pieces will help govern brand stylings between business groups \(Ex. Marketing\) within the organization.

