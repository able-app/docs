# Toggle

Element: A grouping of solo toggle buttons that act together as a unit. This group is then treated as a single unit for dynamic resizing capabilities. Note, a single toggle can exist in a group.

### Style

The different options for the stylings from the toggle-solo are passed through to this layer since they act as a unit.

### Surface

This is a pass through from the toggle-solo layer where we set the visibility of the toggle surface.

### State

This is here primarily as a design convenience.  All states for a toggle are set at the toggle-solo layer and get passed up to their parent.

### Formats

**Multi:** The default type, used when there is more than a single toggle option.  This type then has a "Choice" funcitonality depending on the intention of the grouping.

**Single:** In situations where we only need a single toggle on/off of a single button we use this option.  An example of this in use could be with a mute button, where we'd want to display the status of "Muted" or "Unmuted" in an interface. 

### Choice (Functional)

**Singular:** By default, the toggle button acts like a grouping of radio-buttons where only one option can be chosen. An example of a "singular" choice is a text editor list style where the list can be either bullet or numeric but not both at the same time.

**Multiple:** Setting the choice type to multiple allows multiple buttons to be selected (checkbox like) at the same time. An example of this choice "multiple" is a text editor with Bold, Italic, Underline options where multiple can be on/off.

-----



**Possible Future Consideration**

### Orientation

**Horizontal:** By default, toggle buttons display horizontally across the screen and adjust their widths to the size of its parent container.

**Vertical:** In the vertical orientation text and icons continue to display upright, and the toggle buttons are just stacked vertically one on top of the next.

