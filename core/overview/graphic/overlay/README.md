# ε Overlay

Element: Used as a placeholder container on top of a Graphic to give additional functionality (icon, banner, sash, adoption). There are three overlay locations within a Graphic: Top, Center, Bottom each with their own unique display types.

[Styleguide Link](./)

* Parent: [Graphic](../)
* Child: Overlay - [Icon](ol-icon.md), [Banner](ol-banner.md), [Sash](ol-sash.md), [AdaptIcon](ol-adapticon.md), [Button](ol-button.md)

## Properties

### Location

We break the overlay into seven distinct areas of the graphic and organize the possibilities within each of those collections.

<figure><img src="../../../../.gitbook/assets/Location (1).png" alt=""><figcaption></figcaption></figure>

* **Top Left:** Docked to the top left corner of the Graphic
* **Top Center:** Docked to the top left & right corners of the Graphic
* **Top Right:** Docked to the top right corner of the Graphic
* **Center-Center:** Floating in the vertical & horizontal center of the Graphic
* **Bottom Left:** Docked to the bottom left corner of the Graphic
* **Bottom Center:** Docked to the bottom left & right corners of the Graphic
* **Bottom Right:** Docked to the bottom right corner of the Graphic

### Type

Each of the types is further broken down into their like collections at the Primitive level where we control the horizontal location of the objects contained within the Overlay.

<figure><img src="../../../../.gitbook/assets/Type.png" alt=""><figcaption></figcaption></figure>

* **Icon:** Normally used as actionable or informational areas that overlay (float above) the Graphic. A good example of an actionable icon would be the activity of Favoriting or Liking an image.
* **Button:** Used as the primary CTA "Call to Action" for the Graphic/Illustration it is overlaying.
* **Headline:** Used to provide words on top of a graphic or illustration.
* **Banner:** Primarily for information a banner can stretch the width of the Graphic or be a notch in the Graphic.
* **Sash:** A sash is a triangular piece that drapes across the corner of the graphic. This draws a bit more attention to the visual being displayed inside of the sash.
* **AdaptIcon:** Used to give context to a Graphic, possibly attributing it to a location represented by the AdaptIcon.
* **Avatar:** Used to attribute a Graphic to a person, pictured in the Avatar with an optional name beside it.
* **Stepper:** When multiple graphics/illustrations are represented in a single Graphic instance we show the content stepper indicator.

{% embed url="https://www.figma.com/proto/VN320MmRlLNR0UmdFula6N/Kitchen-Sink?node-id=2%3A23880&page-id=0%3A1&scaling=min-zoom&show-proto-sidebar=1&starting-point-node-id=2%3A24853&viewport=377%2C48%2C0.14" %}
