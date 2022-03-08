# Ω Iconography

Used as a visual language to represent type, level, status, content, or adding context to supporting material. Icons are meant to be a simple, immediately recognizable, visual representations of an object or activity. Icons are visual cues that provide clues about how the user should use the app using metaphorical associations. Iconography is treated in the same way as an element with color, size, and spacing properties.

## Icon Library

With any application there will be the need for some level of visual iconography. To provide a scalable, consistent, and easy way to move between different icon families we use an Icon Library. This ties a metaphor, the intent/idea behind an icon to a design token which can have one or more words associated with it. As an example, lets take the idea "metaphor" of a settings area. We can use the design token "\#icnSettings" for that icon in every element, component, and screen across the application and then have the ability to swap out that icon, application wide from a single source of truth in the library. In the library we define each metaphor independently.  In the previous example of "Settings" we use a gear icon, that same gear icon could be used to represent another metaphor for example "Motor". By having the two metaphors represented in the Icon Library as separate objects we can change out the "Motor" metaphor for a different visual without effecting the "Settings" icon throughout the app. This also gives us a way of swapping out an entire icon family (ie link a new Icon Library file) for another when you want to change the look and feel of the application.

### Properties

**Name**: \[textField\] The human readable way we refer to this "Icon" in the metaphor library

**Family**: \[selectList\(Assets.Icons\)\] The icon family that this icon is in. The list of available icon families is pulled from the Assets &gt; Icons folder. Those icon families that have been uploaded into the system.

**Resource**: \[searchGallary\(selectedFamily\)\] Every icon will have a source file that it references to provide the look of icon.

**Metaphor**: \[textField\] Every icon acts as a metaphor for something. Some icons can carry multiple metaphors \(i.e. "back" and "previous" for the left-arrow.svg\) This allows us to reuse these metaphors as a design token which is referenced throughout our components while all carrying the same look.

**Referenced By**: \[textArea.ReadOnlyCsvList\] The list of elements and components that are referencing this dictionary

**Token**: \[textField\] The short-code we use to refer to this metaphor \(i.e.. \#icnSettings, \#icnAdd, \#icnAccount, etc.\)

### Base Metaphors

| **Name** | **Family** | **Resource** | **Metaphor\(s\)** | **Token** |
| :--- | :--- | :--- | :--- | :--- |
| Back | Base | left-arrow.svg | back, previous, return | \#back |

Design tokens all carry a unique name which is referenced to build the component. Here's an example of the icons that are referenced as part of the AppBar component for the base "default" theme.

Elements and components that have icons in them reference an Icon Dictionary. That dictionary is then used to tie each of the icon families, individual icon files to those elements and components. This allows us to add a new icon family, map them to the proper metaphors, and have different icon families in themes. And everything is correctly map to elements and components without ever modifying them.

#### Navigation - AppBar

| **Name** | **Resource** | **Metaphor\(s\)** | **Token** |
| :--- | :--- | :--- | :--- |
| Drawer | 17-navigation /  navigation-drawer-1.svg | Menu, Drawer | \#drawer |
| Add | 27-remove-add /  add-1.svg | Plus, Add | \#add |
| Remove | 27-remove-add /  subtract-1.svg | Cancel, Delete,  Remove | \#remove |
| Back | 97-arrows /  arrow-left-12.svg | Back, Previous,  Return | \#navBack |
| Forward | 97-arrows /  arrow-right-12.svg | Next, Forward | \#navForward |
| Close | 02-status /  close.svg | Close, Exit | \#close |
| More | 17-navigation /  navigation-show-more-2.svg | More | \#navMore |
| Search | 01-content-edition  / search.svg | Search, Find, Look | \#search |
| Share | 21-share /  share-box.svg | Share, Send | \#share |
| Settings | 03-settings /  cog.svg | Settings,  Properties | \#settings |

