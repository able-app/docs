# Θ Caption - Title

Collection: A convenience container for the title of a caption rows, which is made up of leading, primary, and trailing containers. These are used in Cells and Cards as vertically stackable, modular pieces of the caption area. Please see [Caption - Definitions](https://github.com/able-app/docs/blob/57a78e2f25b43d8f5e72755f1e2740d12a2998ee/controls/%CE%B5%20elements/caption/cap-def.md) for a run down on the structure and terminology used in captions.

[Styleguide Link](https://zpl.io/2jqG8Gp)

* Parent: [CardItem](https://github.com/able-app/docs/blob/26fef4dd60d663f49dd419ed514bd2b8d643c5ed/controls/components/card/card-item.md), [AdaptIcon - Bar](https://github.com/able-app/docs/blob/26fef4dd60d663f49dd419ed514bd2b8d643c5ed/controls/%CE%B5%20elements/adapticon/adapticon-bar.md), [Avatar - Bar](https://github.com/able-app/docs/blob/26fef4dd60d663f49dd419ed514bd2b8d643c5ed/controls/%CE%B5%20elements/avatar/avatar-bar.md), [Graphic - Bar](https://github.com/able-app/docs/blob/26fef4dd60d663f49dd419ed514bd2b8d643c5ed/controls/%CE%B5%20elements/graphic/graphic-bar.md), (AdaptIconItem, AvatarItem,GraphicItem???)
* Child: CapCol - [Leading](https://github.com/able-app/docs/blob/26fef4dd60d663f49dd419ed514bd2b8d643c5ed/controls/%CE%B5%20elements/caption/capcon-leading.md), [Primary](https://github.com/able-app/docs/blob/26fef4dd60d663f49dd419ed514bd2b8d643c5ed/controls/%CE%B5%20elements/caption/capcon-primary.md), [Trailing](https://github.com/able-app/docs/blob/26fef4dd60d663f49dd419ed514bd2b8d643c5ed/controls/%CE%B5%20elements/caption/capcon-trailing.md)

## Properties

### Size

The general size of the primary text used in the caption row.

* XXSmall
* XSmall
* Small
* Medium
* Large

### Styles - Leading & Trailing

Here's where we bring in the columns (leading, primary, trailing containers) in order to customize the layout of the row.

**Leading Options**

* Nothing at all
* Icon
* Avatar
* AdaptIcon
* Graphic
* Label

**Trailing Options**

* **Nothing**
* **Action:** An icon that is typically used as a More button to reveal additional actions that can be taken on the subject matter.
* **Super Action:** More of a primary action and most often used as an Add capability, this icon is slightly larger and carries a larger hit area.
* **Button:** A prominent primary action used to take an action on the subject matter.
* **Subtext:** Used for short bits of text in a right aligned format.
* **Multi-Image/Avatar/AdaptIcon:** To show an association with the object being represented
