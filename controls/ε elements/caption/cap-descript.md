# Caption - Description

Collection:  A convenience container for the descriptions of a caption row, which is made up of leading, primary, and trailing containers. These are used in Cells and Cards as vertically stackable, modular pieces of the caption area.

### Definitions

**Bars:** We refer to the container for a collection of cells or cards as Bars. These are also capable of being stacked vertically to form Views as in CardView, CellView which are in a scrollview

**Cell:**  In bars we have repeating objects that are organized into cells.  This could be a single element like a graphic, or multiple objects (graphic, with multiple caption rows) that are combined to form the cell. Cells do NOT have visual borders around its contents.

**Card:** A container similar to a Cell but with a visually defined edge and padding between the edge and its contents. Cards and cells function the same and just carry different padding and visual appearance.

**Caption Rows:** We divide the cell/cards caption into vertically stackable rows. These rows can then be added/subtracted from the caption area depending on the use case.  Inside each caption row we have three columns, the leading, primary, and trailing content containers.

[Styleguide Link](https://zpl.io/VDNyOEv)

- Parent: [CardItem](https://github.com/able-app/docs/blob/26fef4dd60d663f49dd419ed514bd2b8d643c5ed/controls/components/card/card-item.md), [AdaptIcon - Bar](https://github.com/able-app/docs/blob/26fef4dd60d663f49dd419ed514bd2b8d643c5ed/controls/%CE%B5%20elements/adapticon/adapticon-bar.md), [Avatar - Bar](https://github.com/able-app/docs/blob/26fef4dd60d663f49dd419ed514bd2b8d643c5ed/controls/%CE%B5%20elements/avatar/avatar-bar.md), [Graphic - Bar](https://github.com/able-app/docs/blob/26fef4dd60d663f49dd419ed514bd2b8d643c5ed/controls/%CE%B5%20elements/graphic/graphic-bar.md), (AdaptIconItem, AvatarItem,GraphicItem???)
- Child:  CapCon - [Leading](https://github.com/able-app/docs/blob/26fef4dd60d663f49dd419ed514bd2b8d643c5ed/controls/%CE%B5%20elements/caption/capcon-leading.md), [Primary](https://github.com/able-app/docs/blob/26fef4dd60d663f49dd419ed514bd2b8d643c5ed/controls/%CE%B5%20elements/caption/capcon-primary.md), [Trailing](https://github.com/able-app/docs/blob/26fef4dd60d663f49dd419ed514bd2b8d643c5ed/controls/%CE%B5%20elements/caption/capcon-trailing.md)

## Properties

### Size

The general size of the primary text used in the caption row.

- XXSmall

  

### Styles - Leading & Trailing

Here's where we bring in the columns (leading, primary, trailing) in order to customize the layout of the row. Those options available in the lower level caption containers for leading, primary, trailing are available to choose from.

**Leading Options**

- Nothing at all
- Icon
- Avatar
- AdaptIcon
- Graphic

**Trailing Options**

- Nothing
- Subtext - Used for short bits of information that are right aligned text.
- Action - An icon that is typically used as a More button to reveal additional actions that can be taken on the subject matter.
- Super Action - More of a primary action and most often used as an Add capability, this icon is slightly larger and carries a larger hit area.
- Button - A prominate primary action used to take an action on the subject matter.
- Link - Text based actionable content that will usually navigate to a new screen.
