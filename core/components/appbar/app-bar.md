# App Bar

The primary control for navigation and actionable activities in the application.

[TOP - Styleguide Link](https://zpl.io/254ANOr)

[BOTTOM - Styleguide Link](https://zpl.io/an3L6pv)

## Properties

### Leading Style

Taken from the ABC-Leading collection the leading style allows us to change up the appearance of the far left column of content.

- Icon (default)
- Text
- Avatar
- Button
- Logo (1:1 ratio)
- None
- Wordmark - Only used in situations where there is NO center content.
- Title - Only used in situations where there is NO center content.
- Toggle - Only used in situations where there is NO center content.
- Input - Only used in situations where there is NO center content.

### Center Style

Provided to us from the ABC-Center collection the center style gives us the ability to control the center column of the App Bar. The contents of this center column expand to fill the space, where the Leading and Trailing styles hug their contents.

- Title (default)
- Search
- Toggle
- Wordmark
- Logo (1:1 ratio)
- None

### Trailing Style

Supplied by the ABC-Trailing collection this provides us with the ability to alter the styling of the right side column of the App Bar.

- Icon (default)
- Text
- Button
- Avatar
- Logo
- None

### Location

We've divided the App Bar into two distinct vertical areas, Top for those at the top of the screen and of course Bottom for those at the bottom of the screen.

### Interaction

When the user scrolls content within a list, we will want the app bar to gracefully hide itself to provide the best experience, since the intent of the user is the contents of the screen and not navigating or taking action on that content, while they are scrolling. When we detect that the scroll has stopped the app bar top/bottom will gracefully return to view. This should be a property of the component that defaults to on, but can be turned off. [Here's an example from MD.](https://material.io/components/app-bars-top#behavior)

### Extension

An extension can be added to the app bar to provide an additional layer of navigation, sorting, filtering, or actionable activities. With app bars that dock to the top the extension is below the main App Bar, and when docked to the bottom the extension is above the main App Bar.

### Surface

Depending on the screen the background surface of the component can change (Light, Dark, Keyboard)

### Keyboard Extension - App Bar

When the keyboard is engaged we still have the need for a primary navigation and actions, so the app bar that would normally be at the bottom of the screen now gets attached to the top of the keyboard as an extension.  Note, all of the functionality of the keyboard extension for an app bar is the same as the app bar - bottom/top.  The only change is to it's bottom spacing and background surface which is matched to the color of the keyboard.



### Types

* **NavAct** - The base level App Bar, with Navigation on the far left with actionable icons and usually presented with a promenant CTA (Call-to-Action) on the right side. Normally used when the subject matter of the screen is a listing of many objects or a variety of subject matter, like in a dashboard.
* **NavTitleAct** - A variation of the base NavAct that's used when the subject matter is a specific object and the user is trying to take some sort of action on that object like, adding, editing, moving, deleting, etc. where the Title informs them of that action.
* **NavSearch** - Used when in a listing of objects and one of the primary actionable events is to search for something.  Note, the search ability could also be a little more hidden under an icon (like in the base NavAct) and revealed to display the search input.
* **NavTab** - Similar to NavAct but in place of the action icons we have tabs that can exist in an infinite side scroll.  The tabs are normally used as the primary sections of the application and the navigation is there to navigate the user through the history stack, much like a desktop browser does with tabs.
* **Mini** - When scrolling through content and in cases where we want to provide a little bit of information but don't wish to take up a lot of screen real estate.  This is quite common with webview content.