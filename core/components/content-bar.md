# Content Bar

Container: A horizontally scrollable section of content used with vertical Scrollviews where we want a section to scroll horizontally.

[Styleguide Link](https://zpl.io/6NR0wPK)

* Parent: ScrollView
* Child: [CardBar](../ks-modules/card-view/card-bar.md), [GraphicBar](../overview/graphic/graphic-bar.md), [AvatarBar](../overview/avatar/avatar-bar.md), [AdaptIconBar](../overview/adapticon/adapticon-bar.md), [ChipBar](../overview/chip/chip-bar.md), [ToggleBar](../overview/toggle/toggle-bar.md), [ButtonBar](../overview/button/button-bar.md)



### Architecture

**ScrollView:** In this use case a vertically scrollable part of the screen that can contain content bars, ListItems, or Graphics in a grid format.

**Bar:** This is the outermost container for cells that can either be horizontally scrollable with cells that scroll off the right side of the screen or have a locked width with a set number of cells.

**Cell:** In bars we have repeating objects that are organized into cells. This could be a single element like a graphic, or multiple objects (graphic, caption rows) that are combined to form the cell.

**Primary Content:** The visually dominate part of the cell. Options include an graphic, avatar or adaptIcon depending on the use case. Primary content like an image either has a locked aspect ratio (as is the case with avatars and adaptIcons at 1:1), or variable sized, locked aspect ratios, like we see with images that grow to fill the screens width while maintaining their aspect ratio.

**Cell Caption:** We divide the cells caption into vertical rows of content, where each row serves a specific purpose. These rows are then vertically stacked in the cells caption area depending on the use case.

**Leading/Primary/Trailing Collections:** Inside a cell caption row there are three columns, the leading, primary, and trailing content collections. These are convenience containers where we store the options available in each of the columns of the cells caption row.

## Properties

### Type

* **Card**
* **Graphic**
* **Avatar**
* **AdaptIcon**
* **Chip**
* **Toggle**
* **Button**



### Functionality

**Fixed:** For fixed width bars with a set number of cells, multiple bars can be stacked on top of one another to form a scrollview scrolling vertically.

**Scrollable:** For horizontally scrollable bars that have their content bleed off the right side of the interface, the number of cells is determined by the content it is supplied. This could be a set number like 10, or infinite like we see with a vertical infinite scroll.

