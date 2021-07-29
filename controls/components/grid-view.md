# GridView

A collection of multiple CardItems in a scrollable vertical index (list).

[Styleguide Link](https://zpl.io/adKWyRp)

- Parent: Screen
- Children: [GridItem]()

## Properties

### Column

- **Single:** A single GridItem for the entire width of the screen, which collectively forms a GridRow.
- **Two:** Two GridItems for the width of the screen, which collectively forms a GridRow.
- **Three:** Three GridItems for the width of the screen, which collectively forms a GridRow.

**Note:** These are standards for the portrait mode of the small form factor (phone) style screen.  In landscape mode the content adjusts its column count to maintain the same relative size as these GridItem widths to fill the landscape mode screens width, with the appropriate gutter and padding.

### Header

A header (aka SecHead) can exist at the top of a GridView and be used to separate list content into different collections under that header. That Section Header has a title and can have additional actionable icons associated with the section to take action on the collection.

### Gutter

The gutters around the content can be on or off depending on the use case.

### Surface

The background of the view can be light or dark depending on the use case.  Most often when browsing photos on your device you're displaying these in the dark style, but if your looking at say, Instagram photos in a collection, those would be displayed in a light style.

## Functionality

The Graphics (Images) within the grid are set to a 1:1 ratio with the focal point being the horizontal and vertical center of the graphic.  The size of the images dynamically change based on the width of a portrait format screen.

Note: If the device is in landscape format the screen accepts a 1:1 image in a 5 wide format, while still providing a vertical scroll in that landscape format. All of the padding and grid spacing remain the same.
