# Size

For objects on the screen we want to adhere to sizing standards as much as we can to create a consistent look and feel across our visual elements. To accomplish this we have sizing standards that are associated with different objects (i.e. Grids, Spacing, Icons, Avatars, Images and Button).

## Size Dictionaries

There are various sizing types (grid, spacing, radius, object width & height, timing, etc.) that are a part of the design system that used to design our components and screen layouts. This is where we group those individual sizes together into use case dependent dictionaries. These are then used by our elements and components to provide the sizing options available to that object. 

The design system starts with a few base dictionaries (grid, spacing, radius etc.). More can be added as needed to accommodate the needs of the system as it grows. As a sub-category under this "Size" page is where we list each of these base dictionaries with their usage, properties, and JSON details. 

### Properties 

**Name**: [textField] The human readable dictionary name for this "Size" option. (i.e. spacing, radius, etc.) 

**Type**: [selectList] The family grouping for this size i.e. Radius, Image, Grid… 

**Thumbnail**: [fileAdd - optional] The visual to represent this object  

**Description**: [textArea - optional] Context to understand what the object is 

**Token**: [textField] The short-code we use to refer to this dictionary (i.e.. #dicSpacing, #dicRadius etc.) 

A single dictionary "source of truth" can then be referenced across multiple elements, components and screens to provide the size properties for that object in the design system. 



## Add Entry

These are the individual "entries" added to this size dictionary. As an example we have an Icon Size "Dictionary" which is referenced from all icons in the design system. That dictionary has options of Small, Medium, Large. Now when we are building a component with an icon in it, we have those options and only those options available to us, which enforces consistency throughout the design.

### Properties

**Name**: [textField] The human readable way we refer to this "Size" option in the Dictionary.

**Value**: [slider-tick(1-99;12)] This is the digital pixel size

**Base**: [toggle(on,off;off)] Makes this entry the default "base" value.

**Token**: [textField] The short-code we use to refer to this metaphor (i.e.. #szSm, #szMed, #szLrg, etc.)