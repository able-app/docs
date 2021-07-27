# Illustration (Canvas)

Element: The shape and size of the Illustration canvas. The canvas has the same aspect ratios and rules as the Graphic element.  We separate illustrations from graphics because they are usually sectioned off in their own file and provided to an illustrator. This allows the team to stay organized.

[Styleguide Link](https://zpl.io/brGvn4X)

- Parent: [ListItem](https://github.com/able-app/docs/blob/11bba28ef1491560027e9f7e377c9a1bba80bf2e/controls/components/listitem/list-item.md), [CardItem](https://github.com/able-app/docs/blob/11bba28ef1491560027e9f7e377c9a1bba80bf2e/controls/components/card-item.md), GridItem, Multiple
- Child: [Overlay - Top, Center, Bottom](https://github.com/able-app/docs/blob/7486c8fa88811fddbd49b82001d919e42805712e/controls/%CE%B5%20elements/overlay/overlay.md)

## Properties

**Aspect Ratio** - The design system has standardized the the sizes of illustration canvas' to follow a set of consistent aspect ratios. The following ratios are the only ones used throughout the system. Each of these are listed in their Landscape orientation, but can also exist in Portrait format as well.

- 1:1 (Square)
- 5:4
- 4:3
- 3:2
- 16:10
- 1.618:1 (The Golden Ratio)
- 16:9 (Video Size)
- 2:1
- 21:9 (Movie Theater Screen Size)

Note: Each of the placeholder images for these aspect ratios have a different appearance and have the ratio number in the lower right corner of the image to help in understanding the ratios at a glance.

**Overlay** - Provides the ability to include a layer of content over top of the illustration canvas.  This lets us text content, banners, buttons on top of an illustration. There are three areas for overlays...

- **Top** - Docked to the top of the graphic.
- **Center** - Floating at the vertical center of the graphic
- **Bottom** - Docked to the bottom of the graphic

These overlays can be On/Off independent of one another.

**NOTE:** This is the same functionality found in the [Graphic](https://github.com/able-app/docs/blob/f8c133a1a1e00bdc9238465d1a07b23f99322e97/controls/%CE%B5%20elements/graphic/graphic.md) element.