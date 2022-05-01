# Sheet

A sheet is a modal container that slides into view when another action triggers the event. Sheets can be positioned at the top or bottom of the screen on mobile devices. Multiple elements and components can be placed within the sheet container.

[Styleguide Link](https://zpl.io/2jyLrnW)

* Child: [Sheet Drag](sheet-drag.md), [ListView](../../ks-modules/list-view.md), [Section Header](../sec-head.md), [Textfield](../form/textfield-1.md), Multiple others

## Properties

### Location

* **Top:** The sheet opens (reveals) from the top of the mobile apps screen.
* **Bottom:** The sheet opens (reveals) from the bottom of the mobile apps screen.

### Open Size

The height of the sheet when opened can be one of three heights. A greaat example of this can be found in the Google/Apple Maps mobile app with the search sheet, where the contents of the sheet have anchors to auto adjust the height of the sheet dependent on the contents of the sheet. This may be a different height for each usecase, but we limit the number of anchor points to a maximum of three.

* Small
* Medium
* Large
* Full - Not technically a sheet but a Full Screen view. Included here so you understand this is a sheet drag option.

### Surface

* Light: The sheet is intended for use on top of Light colored content.
* Dark: The sheet is intended for use on top of Dark color content, for example when browsing photos in a Grid from the camera library (with a dark background to the Grid) and taking an action on a photo.

### Scrim

The semi-transparant backing behind a sheet, modal dialog box, or drawer. The scrim can be set to different levels of transparency depending on the use case, with the default being a 40% opacity.

```
- 0% (None)
- 10%
- 20%
- 40% (Default)
- 60%
- 80%
```

### Use

A sheet has three positions it can open to with snapping to that height...
