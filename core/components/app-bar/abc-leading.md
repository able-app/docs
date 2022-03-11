---
description: App Bar Control (ABC)
---

# ABC - Leading

Collection: Those navigation and action controls on the left side of the app bar, that typically function as navigational objects in the app.

[Styleguide Link](https://zpl.io/aw5Qv5D)

* Parent: [App Bar Top & Bottom](./)
* Children: [ABC - Pieces](abc-pieces.md)

## Properties

### Controls

The number of objects in this section of the app bar. Those objects are referenced in "Type". Each of these controls can be any "Type", however they usually follow a consistent pattern of the same "type" after the second control.

### Type

The general theme for the collection of controls, most often this type will be the same as the far left object in the collection. These "Types" are supplied by the abc-pieces collection.

* **Icon** (default) - Most often used as the primary navigation to move back in the applications history stack (previous screen). In this Type the far left object is for that navigation and the other icons can serve as actions to be taken on the screens contents.
* **Text** - As an alternative to an icon for the back navigation you can also use text. This is most commonly used in situations where you want to "Close" the screen which is typical of a screen with a form.
* **Avatar** - Often used to change the users status or go to their profile/account
* **Button** - A more prominent actionable button with lesser actionable icons to the right.
* **Logo** - A 1:1 ratio brand-able area with actionable icons to the right
* **Wordmark** - A wider brand-able area (21:9) with actionable icons to the right
* **Title** - A left aligned screen title with actionable icons to the right.
* **Toggle** - Used as an alternative to tabs when there are limited collection types that could be switched between. For example, people in three groupings, Family, Friends, and Community.
* **Input** - Typically used for search, you'd opt to show the search field as opposed to hiding it behind a search icon.
* **NavToggle** - Used to navigate back in the history stack (previous screen). A secondary action can also be used to expand the toggle button group to reveal additional options (usually actions that can be taken on the screen contents).
* **None** - When we don't want to show anything left aligned in the app bar.

## Functionality

This collection allows us to organize the app bar into its different sections for easier customization on-the-fly through the properties of the App Bar component.
