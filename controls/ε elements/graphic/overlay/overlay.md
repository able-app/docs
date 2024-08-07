# Overlay

Element: Used as a placeholder container on top of a Graphic to give additional functionality (icon, banner, sash, adoption). There are three overlay locations within a Graphic: Top, Center, Bottom each with their own unique display types.

[Styleguide Link]()

- Parent: [Graphic](https://github.com/able-app/docs/blob/8cd03de6556a6ec1dcd98dc8c2230863c5dba43c/controls/%CE%B5%20elements/graphic.md)
- Child: Overlay - [Icon](https://github.com/able-app/docs/blob/7486c8fa88811fddbd49b82001d919e42805712e/controls/%CE%B5%20elements/overlay/ol-icon.md), [Banner](https://github.com/able-app/docs/blob/7486c8fa88811fddbd49b82001d919e42805712e/controls/%CE%B5%20elements/overlay/ol-banner.md), [Sash](https://github.com/able-app/docs/blob/7486c8fa88811fddbd49b82001d919e42805712e/controls/%CE%B5%20elements/overlay/ol-sash.md), [AdaptIcon](https://github.com/able-app/docs/blob/7486c8fa88811fddbd49b82001d919e42805712e/controls/%CE%B5%20elements/overlay/ol-adapticon.md), [Button](https://github.com/able-app/docs/blob/6b264b6af626eecdfe550ed6f8b5884787b210bb/controls/%CE%B5%20elements/graphic/overlay/ol-button.md)

## Properties

### Location

We break the overlay into three distinct areas of the graphic and organize the possibilities within each of those collections.

- **Top:** Docked to the top of the Graphic
- **Center:** Floating in the vertical center of the Graphic
- **Bottom:** Docked to the bottom of the Graphic

### Type

Each of the types is further broken down into their like collections at the Primitive level where we control the horizontal location of the objects contained within the Overlay.

- **Icon:** Normally used as actionable or informational areas that overlay (float above) the Graphic. A good example of an actionable icon would be the activity of Favoriting or Liking an image.
- **Button:** Used as the primary CTA "Call to Action" for the Graphic/Illustration it is overlaying.
- **Headline:** Used to provide words on top of a graphic or illustration.
- **Banner:** Primarily for information a banner can stretch the width of the Graphic or be a notch in the Graphic.
- **Sash:** A sash is a triangular piece that drapes across the corner of the graphic.  This draws a bit more attention to the visual being displayed inside of the sash.
- **AdaptIcon:** Used to give context to a Graphic, possibly attributing it to a location represented by the AdaptIcon.
- **Avatar:** Used to attribute a Graphic to a person, pictured in the Avatar with an optional name beside it.
- **Stepper:** When multiple graphics/illustrations are represented in a single Graphic instance we show the content stepper indicator.

