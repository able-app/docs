# MasonryView

Component: A collections of Graphics (Images) of varying heights, that are vertically stacked in a Scrollview.

[Styleguide Link]()

### Functionality

The Graphics (Images) within the masonry grid have a variety of different "set sizes". All options have the focal point at the horizontal and vertical center of the graphic (which means part of the image may be masked, depending on the source image size).  The size of the images dynamically change IN PROPORTION based on the width of a portrait format screen. NOTE: The screens are designed with a 360 dp wide screen, so when on an iPhone the screen is 375 dp. The gutters between the images remains constant and the images shrink/grow to fill the space in proportion.

### Set Sizes (Portrait)

- 1:1 (Square)
- 2:3
- 4:3
- 9:12
- 9:16

### Structure -The "Properties" of the object.

### Content

Double - Two graphics positioned side-by-side in a portrait view on the device.

### Header

The view either has a header or not within the scrollable view.  Note this is different from a header that is outside of the scrollable area.

### Gutter

The gutters around the content can be on or off depending on the use case.

### Surface

The background of the view can be light or dark depending on the use case.  Most often when browsing photos on your device you're displaying these in the dark style, but if your looking at say, Instagram photos in a collection, those would be displayed in a light style.
