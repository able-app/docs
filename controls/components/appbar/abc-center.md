# App Bar Control - Center

Collection: A container for the content that is in the center (horizontally) of the app bar.  This content can be informative or actionable depending on the type of app bar.

[Styleguide Link](https://zpl.io/2vjgx55)

- Parent: [App Bar Top & Bottom](https://github.com/able-app/docs/blob/08eb774e348952235f1f4eb0369879387a684280/controls/components/appbar/app-bar.md)
- Children: [App Bar Pieces](https://github.com/able-app/docs/blob/08eb774e348952235f1f4eb0369879387a684280/controls/components/appbar/abc-pieces.md)

## Properties

### Type

The general theme for the collection of controls, most often this type will be the same as the central (most centered) object in the collection. These "Types" are supplied by the abc-pieces collection.

**Title** (default)- Informational content to give the user the name/action of the screen they are on.

**Wordmark/Logo** - Normally for branding purposes with the wordmark just being a wider reserved width of 21:9 and the logo set to a 1:1 ratio.

**Search** - When one of the primary abilies of the screen is to search its contents we will opt to show the search field as opposed to hiding it behind a search icon.

**Toggle** - When the contents of the screen can be divided into sub sections we can drop in a toggle button group.

**Tab Bar** - The ability to navigate to the primary areas of the application in a side-scrollable (optional) grouping of tabs.

**None** - Of course the app bar could also set the center area to nothing at all.

## Functionality

The ABC - Center expands to fill the full width of the App Bar, where the Leading and Trailing sections hug their contents.