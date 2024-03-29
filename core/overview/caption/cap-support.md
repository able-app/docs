# Θ Caption - Support

Collection: A convenience container for supporting content of a caption row, which is made up of leading, primary, and trailing containers. These are used in Cells and Cards as vertically stackable, modular pieces of the caption area. Please see [Caption - Definitions](https://github.com/able-app/docs/blob/57a78e2f25b43d8f5e72755f1e2740d12a2998ee/controls/%CE%B5%20elements/caption/cap-def.md) for a run down on the structure and terminology used in captions.

[Styleguide Link](https://zpl.io/aBPGy1m)

* Parent: [CardItem](https://github.com/able-app/docs/blob/26fef4dd60d663f49dd419ed514bd2b8d643c5ed/controls/components/card/card-item.md), [AdaptIcon - Bar](https://github.com/able-app/docs/blob/26fef4dd60d663f49dd419ed514bd2b8d643c5ed/controls/%CE%B5%20elements/adapticon/adapticon-bar.md), [Avatar - Bar](https://github.com/able-app/docs/blob/26fef4dd60d663f49dd419ed514bd2b8d643c5ed/controls/%CE%B5%20elements/avatar/avatar-bar.md), [Graphic - Bar](https://github.com/able-app/docs/blob/26fef4dd60d663f49dd419ed514bd2b8d643c5ed/controls/%CE%B5%20elements/graphic/graphic-bar.md), (AdaptIconItem, AvatarItem,GraphicItem???)
* Child: CapCol - [Leading](https://github.com/able-app/docs/blob/26fef4dd60d663f49dd419ed514bd2b8d643c5ed/controls/%CE%B5%20elements/caption/capcon-leading.md), [Primary](https://github.com/able-app/docs/blob/26fef4dd60d663f49dd419ed514bd2b8d643c5ed/controls/%CE%B5%20elements/caption/capcon-primary.md), [Trailing](https://github.com/able-app/docs/blob/26fef4dd60d663f49dd419ed514bd2b8d643c5ed/controls/%CE%B5%20elements/caption/capcon-trailing.md)

## Properties

### Subject

This Support area is slightly different from the Title and Description areas of Captions. Here we are lumping multiple types (listed below) together into one area.

* **Link:** A word based clickable/tappable navigation point. This may be a persons name for a post, or a brand/store for a product. There are two confirations to the Link (leading and trailing) of the actual link with helper text either before or after the link.
* **Rating:** User provided score for the subject matter being presented, this could be a product or post review rating with the total score and the number of reviewers or viewers.
* **Stats:** To display statistics about the subject matter in a single row with pipes "|" separating each stat.
* **Symbols:** A series of icons that give the user quick bits of information based on the symbols being shown. For example, one of the symbols could indicate that a product has an offer on it and another could represent the amount remaining (icon with number).

### Size

The general size of the primary text used in the caption row.

* XXSmall

### Styles - Leading & Trailing

Here's where we bring in the columns (leading, primary, trailing) in order to customize the layout of the row. Those options available in the lower level caption containers for leading, primary, trailing are available to choose from.

**Leading Options**

* Nothing at all
* Graphic
* Icon
* Rating (stars)

**Trailing Options**

* **None**
* **Action:** Usually a "More" icon
* **Subtext:** Short bits of right aligned content
* **Super Action:** A more prominent action area usually used to add
* **Link:** A text based navigational link to another piece of content
