# CardView

Component: A collections of Bars (rows) of CardItems that are vertically stacked in a Scrollview.

[Styleguide Link](https://zpl.io/aBvePwQ)

* Parent: Screen
* Child: [CardItem](card-item.md), [Section Header](../sec-head.md)

## Properties

### Column

* **Single:** Only a single CardItem per vertical view, in other words, a full width CardItem, in portrait format on the device, with padding of course.
* **Double:** Two CardItems positioned side-by-side in a portrait format on the device.
* **Triple:** Three CardItems positioned side-by-side in a portrait format on the device.

### Header

A header (aka SecHead) can exist at the top of a ListView and be used to separate list content into different collections under that header. That Section Header has a title and can have additional actionable icons associated with the section to take action on the collection. See [Section Header](../sec-head.md) for the details.

## Functionality

The CardItems within the grid dynamically changes based on the width of a portrait format screen. The Caption area contents expand to fill, but the Graphic (Image) dynamically changes it's size in relation to its ratio 1:1 16:9 etc. based on the devices screen width.

Note: Any Bar within a CardView can independently side-scroll its contents, if the bar has the property of Side-Scrollable turned on.
