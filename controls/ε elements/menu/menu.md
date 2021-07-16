# Menu

Component: The display of a list of choices on a temporary surface (modal). The contents of this component are feed it's options from the Menu Control's primitives that separates the menu into three sections (left, center, right).

[Styleguide Link](https://zpl.io/VkymMBg)

- Parent: SelectList, App Bar, More Icons
- Child: Menu - Leading, Menu - Primary, Menu - Trailing

## Properties

### Type

- **Text** - The default menu display method with different possible configurations (single line, 2 and 3 line options, ratings).
- **Icon** - A menu option with a leading icon to provide additional context to the option.
- **Avatar** - When presenting a list of users we use a leading avatar in addition to the users handle or name.
- **Graphic** - Used when we'd like to display a "Thing" in a menu. 
- **AdaptIcon** - For those situtations where we'd show categories of something or a place (ie. map location types).

### Configurations

- **Base** - The default configuration for each of the Types of menu.
- **Choice** - The ability to visually display the currently selected options within the menu.  This functions as either a singular choice, or multi-choice.
- **Trailing Icon** - Visually provides another level of context to a menu option.  For example, the status of the option being locked or unlocked by visually showing an unlocked,locked icon. A trailing icon can also display a chevron to indicate that there's another level to the menu options.

### Elevation

Note, that menus carry an elevation, aka drop shadow.