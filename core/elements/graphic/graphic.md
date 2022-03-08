# Graphic

Element: Overlays, corner radius and any overlays or effects to the image happen at this level.

[Styleguide Link](https://zpl.io/VxA44QE)

- Parent: [ListItem](https://github.com/able-app/docs/blob/11bba28ef1491560027e9f7e377c9a1bba80bf2e/controls/components/listitem/list-item.md), [CardItem](https://github.com/able-app/docs/blob/11bba28ef1491560027e9f7e377c9a1bba80bf2e/controls/components/card-item.md), GridItem, Multiple
- Sister: [Illustration](https://github.com/able-app/docs/blob/8ba740fa6ffc7f19d74e9a9ef7c48e364c281084/controls/%CE%B5%20elements/graphic/illustration.md)
- Child: [Overlay - Top, Center, Bottom](https://github.com/able-app/docs/blob/7486c8fa88811fddbd49b82001d919e42805712e/controls/%CE%B5%20elements/overlay/overlay.md)

## Properties

**Radius** (Corner) - Gives the Graphic a corner radius treatment. The radius that we use are standardized to the following for all Graphics.

- None (0dp)
- Tiny (2dp)
- XSmall (4dp)
- Small (8dp)
- Medium (12dp)
- Large (16dp)
- XLarge (20dp)

**Aspect Ratio** - The design system has standardized the display of graphics to follow a set of consistent aspect ratios. The following ratios are the only ones used throughout the system. Each of these are listed in their Landscape orientation, but can also exist in Portrait format.

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

**Overlay** - Provides the ability to include a layer of content over top of the graphic.  This lets us add icons, text, banners, buttons on top of the graphic. There are three areas for overlays...

- **Top** - Docked to the top of the graphic.
- **Center** - Floating at the vertical center of the graphic
- **Bottom** - Docked to the bottom of the graphic

These overlays can be On/Off independent of one another.

**Treatment** - The ability to add different filters and fades to a graphic to alter the appearance of the underlying graphic. Note, all fades and shading for overlays are contained within the Overlay itself and not at this treatment layer.  Think of it as three layers (from bottom to top) Graphic > Treatment > Overlay where each sits on top of the previous.