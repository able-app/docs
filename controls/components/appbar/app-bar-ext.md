# App Bar - Extension

Container: An area just above/below the app bar bottom/top that serves as a second level for tools, filters, categorization, or selection. This container serves as a collection point for those options available within the Extension.

[Styleguide Link](https://zpl.io/VOLqdEL)

- Parent: [App Bar Top & Bottom](https://github.com/able-app/docs/blob/08eb774e348952235f1f4eb0369879387a684280/controls/components/appbar/app-bar.md)
- Children: [Tab - Bar](https://github.com/able-app/docs/blob/08eb774e348952235f1f4eb0369879387a684280/controls/components/tab-bar.md), [Toggle - Bar](https://github.com/able-app/docs/blob/08eb774e348952235f1f4eb0369879387a684280/controls/%CE%B5%20elements/toggle/toggle-bar.md), Input - Bar, [Chip - Bar](https://github.com/able-app/docs/blob/08eb774e348952235f1f4eb0369879387a684280/controls/%CE%B5%20elements/chip/chip-bar.md), Info - Bar, [Avatar - Bar](https://github.com/able-app/docs/blob/08eb774e348952235f1f4eb0369879387a684280/controls/%CE%B5%20elements/avatar/avatar-bar.md), [AdaptIcon - Bar](https://github.com/able-app/docs/blob/08eb774e348952235f1f4eb0369879387a684280/controls/%CE%B5%20elements/adapticon/adapticon-bar.md), [Graphic - Bar](https://github.com/able-app/docs/blob/08eb774e348952235f1f4eb0369879387a684280/controls/%CE%B5%20elements/graphic/graphic-bar.md), Card - Bar

## Properties

### Type

* **Tab Bar** - Either a scrollable or fixed tabs that act to section off the content being displayed or as tools to take action.
* **Toggle Bar** - Scrollable or fixed a toggle bar can be used to section off content or as a tool bar.
* **Input** - Normally used as a search field the input can be used to filter or search the contents being displayed.
* **Chip Bar** - Typically used with filtering chips can be turned on/off to narrow the results being displayed.  Chips can act as a simple toggle on/off or offer more complex filtering by opening a sheet, dialog box or screen to calibrate the filter.
* **Info** - When the primary app bar doesn't provide an area for general screen information or screen level controls we can apply the info extension.
* **Avatar** - A helpful side-scrolling bar of avatars that can be used when the intent is to select a person from a defined list.
* **Graphic** - Used in situations when a picture is worth a thousand words. A good example of this is with a photo filters to visually display how the selected image would appear with the each filter type.
* **Card** - Similar in use to the Image, this option gives a little more elevation to the image in a card format.
* **AdaptIcon** - Often used in situations where you are narrowing a selection by a type, for example with a search on a map for gas stations where different "types" of establishments can be in each of the adaptIcons.

## Functionality

The extension is contained within the App Bar itself and exists on the same plain.  The height of the App Bar changes based on the contents of the extension.  The contents of the extension can be fixed or side-scrollable based on the properties of the extension.