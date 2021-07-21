# Tooltip

Element: Shows info text when users press certain screen objects. Desktop it also includes hover and focus states. Tooltips display a text label identifying an object, such as a description of its function or further info.

[Styleguide Link](https://zpl.io/2vDWlrJ)

- Parent: [Slider - Ctrl](https://github.com/able-app/docs/blob/8cd03de6556a6ec1dcd98dc8c2230863c5dba43c/controls/%CE%B5%20elements/slider/slider.md) (State:Pressed), Multiple others
- Child: [Label](https://github.com/able-app/docs/blob/8cd03de6556a6ec1dcd98dc8c2230863c5dba43c/controls/%CE%B5%20elements/label.md)

## Properties

**Arrow:** None, Top Left, Top Center, Top Right, Left, Right, Bottom Left, Bottom Center, Bottom Right

The arrow for the tooltip will point at the object that was tapped to reveal the tooltip. The spacing between the edge of that object and the edge of the tooltip is set at 4dp.

**NOTE:** The padding between the edge and label varies based on it's use. What's being shown (16dp) is the default.  For example, with a slider that is displaying a single value the tooltip has padding of 8dp left and right.

### Additional Properties

**Max-Width:** The ability to set the width at which the contents will wrap to the next line.  By default the Tooltip body hugs the contents. With this property set, it still hugs the content up to the max-width and once it reaches that width it will wrap.

## Behavior

A tooltip displays on tapping and holding a screen object (on mobile) or hovering over it (desktop). We display the tooltip as long as the press or hovers interaction takes place.

Upon a tap and release the tooltips displays for 1500ms, unless another action is taken by the user prior to end of that time period, in which it would disappear immediately on that new action.  On open and close of the tooltip a 250ms grow/shrink fade transiton is used.

**Content:** The information within a Tooltip will wrap to the next line upon reaching the tooltips max width.