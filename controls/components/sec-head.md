# Section Header

Component: Used at the top of list, card, grid, masonry sections to separate groupings of like items into sections.  Actionable icons/text can be used as well to jump the user to additional functionality or activities. For Ex. A "More" text link to a full list, which the Section only represents a few.

[Styleguide Link](https://zpl.io/2pRQ39M)

- Parent: ListView, CardView, GridView, MasonryView
- Child:  [Label](https://github.com/able-app/docs/blob/78b7d0a469492d69eba8f33ae838468642242f52/controls/%CE%B5%20elements/label.md), [Icon](https://github.com/able-app/docs/blob/79c4b081b07ceefe4735af4cfe3099b297a9ad69/controls/%CE%B5%20elements/icon/icon.md)

## Properties

**Size**: Generally the size of the title and its relative component height.

- Tiny (R4B)
- XSmall (R3B)
- Small (R2B)
- Medium (R1B)
- Large (H5B)
- XLarge (H4B)
- Huge (H3B)

**Alignment**: Can be left aligned or center depending on the use case

**Surface**: Light, Dark, or Neutral depending on the section it is being paired with, list, card, grid, masonry's background.

**Divider** - A division line at the bottom of the Section Header to draw more attention to the start of the section.  This option is Off by default.

## Interaction

The Labels to the Left and Right of the Title for the Section are meant to serve as tappable/clickable Actions.  These could expand/collapse a section, order a list, open a menu... many types of Action. Note, at the smaller sizes the hitarea for these Labels (text and/or icons) is below the recommended hitarea sizes, so these will primarily exist as visual ID's for content columns that may form in the list.

