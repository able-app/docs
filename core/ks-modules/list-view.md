# ListView

A collection of multiple ListItems in a scrollable vertical index (list).

[Styleguide Link](https://zpl.io/adKWyRp)

* Parent: Screen
* Children: [ListItem](../components/list-item/), [Section Header](../components/sec-head.md)

## Properties

<figure><img src="../../.gitbook/assets/ListView.png" alt=""><figcaption></figcaption></figure>

### Content

* **Single Line:** A single title
* **Two Line:** A title and subtext below
* **Three Line:** A title, secondary subtext below and a tertiary subtext below that

### Header

A header (aka SecHead) can exist at the top of a ListView and be used to separate list content into different collections under that header. That Section Header has a title and can have additional actionable icons associated with the section to take action on the collection.

## Functionality

The ListItems dynamically changes its width to fill the space based on the width of a portrait format screen. For the most part, the heights of ListItems is a fixed height and are stacked one on top of another down the screen in a single column for small form factor (phone) devices in portrait and landscape mode.

