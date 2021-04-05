# App Bar

The primary control for navigation and actionable activities in the application.

## Types

* Base - Used when the subject matter of the screen is a listing of many objects or a variety of subject matter, like in a dashboard.
* Action - Used when the subject matter is a specific object and the user is trying to take some sort of action on that object like, adding, editing, moving, deleting, etc.
* Search - Used when in a listing of objects and one of the primary actionable events is to search for something.  Note, the search ability could also be a little more hidden under an icon and revealed to this state on tap, with the type "Action" above.
* Mini - When scrolling through content and in cases where we want to provide a little bit of information but don't wish to take up a lot of screen real estate.  This is quite common with webview content.

## Extension

An extension can be added to the app bar to provide an additional layer of navigation, sorting, filtering, or actionable activities. With app bars that dock to the top the extension is below, and when docked to the bottom it is above.

## Location

* Top
* Bottom

## Functionality

When the user scrolls content within a list, we will want the app bar to gracefully hide itself to provide the best experience, since the intent of the user is the contents of the screen and not navigating or taking action on that content, while they are scrolling. When we detect that the scroll has stopped the app bar will gracefully return to view.

