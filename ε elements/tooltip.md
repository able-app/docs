# Tooltip

Element: Shows info text when users tap an on screen object. Desktop it also includes hover and focus states. Tooltips display a text label identifying an object, such as a description of its function.

### Behavior

A tooltip displays on tapping and holding a screen object (on mobile) or hovering over it (desktop). We display the tooltip as long as the long-presses or hovers interaction takes place.

Tooltips display for 1500ms, unless another action is taken by the user prior to end of that time period, in which it would disappear immediately on that new action.  On open and close of the tooltip a 250ms grow/shrink fade transiton is used.

### Properties

**Arrow:** None, Top Left, Top Center, Top Right, Left, Right, Bottom Left, Bottom Center, Bottom Right

NOTE: The padding between the edge and label varies based on it's use. What's being shown (16dp) is the default.  For example, with a slider the tooltip has padding of 8dp.