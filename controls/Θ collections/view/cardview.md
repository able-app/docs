# GridView

Component: A collections of rows of Graphics (Images) that are vertically stacked in a Scrollview.

### Functionality

The Graphics (Images) within the grid are set to a 1:1 ratio with the focal point being the horizontal and vertical center of the graphic.  The size of the images dynamically change based on the width of a portrait format screen.

Note: If the device is in landscape format the screen accepts a 1:1 image in a 5 wide format, while still providing a vertical scroll in that landscape format. All of the padding and grid spacing remain the same.

### Content

Single - Only a single graphic per vertical view, in other words, a full width image,  in a portrait view on the device, with padding of course.

Double - Two graphics positioned side-by-side in a portrait view on the device.

Triple - Three graphics positioned side-by-side in a portrait view on the device.

### Header

The view either has a header or not within the scrollable view.  Note this is different from a header that is outside of the scrollable area.

### Style

The background of the view can be lite or dark depending on the use case.  Most often when browsing photos on your device you're displaying these in the dark style, but if your looking at say, Instagram photos in a collection, those would be displayed in a lite style.
