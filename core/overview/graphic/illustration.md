# ε Illustration (Canvas)

Element: The shape and size of the Illustration canvas. The canvas has the same aspect ratios and rules as the Graphic element. We separate illustrations from graphics because they are usually sectioned off in their own file and provided to an illustrator. This allows the team to stay organized.

[Styleguide Link](https://zpl.io/brGvn4X)

* Parent: [ListItem](../../components/list-item/), [CardItem](../../ks-modules/card-view/card-item.md), GridItem, Multiple
* Sister: [Graphic](./)
* Child: [Overlay - Top, Center, Bottom](overlay/)

## Properties

**Aspect Ratio** - The design system has standardized the the sizes of illustration canvas' to follow a set of consistent aspect ratios. The following ratios are the only ones used throughout the system. Each of these are listed in their Landscape orientation, but can also exist in Portrait format as well.

<figure><img src="../../../.gitbook/assets/Aspect Ratio.png" alt=""><figcaption></figcaption></figure>

* 1:1 (Square)
* 5:4
* 4:3
* 3:2
* 16:10
* 1.618:1 (The Golden Ratio)
* 16:9 (Video Size)
* 2:1
* 21:9 (Movie Theater Screen Size)

Note: Each of the placeholder images for these aspect ratios have a different appearance and have the ratio number in the lower right corner of the image to help in understanding the ratios at a glance.

**Overlay** - Provides the ability to include a layer of content over top of the illustration canvas. This lets us text content, banners, buttons on top of an illustration. There are three areas for overlays...

* **Top** - Docked to the top of the graphic.
* **Center** - Floating at the vertical center of the graphic
* **Bottom** - Docked to the bottom of the graphic

These overlays can be On/Off independent of one another.

**NOTE:** This is the same functionality found in the [Graphic](./) element.

{% embed url="https://www.figma.com/proto/VN320MmRlLNR0UmdFula6N/Kitchen-Sink?node-id=2%3A24485&page-id=0%3A1&scaling=min-zoom&show-proto-sidebar=1&starting-point-node-id=2%3A24853&viewport=377%2C48%2C0.14" %}
