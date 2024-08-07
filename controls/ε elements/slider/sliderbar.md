# Slider Bar

Primitive: A visual bar that allows users to make selection(s) from a range of values with a press/click and drag of a knob.

[Styleguide Link](https://zpl.io/a7p4GWp)

- Parent: [Slider](https://github.com/able-app/docs/blob/7e988f3a61132db2fd36d56763df3852f06ab3f5/controls/%CE%B5%20elements/slider/slider.md) (Control)
- Child: [Slider Knob](https://github.com/able-app/docs/blob/7e988f3a61132db2fd36d56763df3852f06ab3f5/controls/%CE%B5%20elements/slider/sliderknob.md), [Slider Indicator](https://github.com/able-app/docs/blob/7e988f3a61132db2fd36d56763df3852f06ab3f5/controls/%CE%B5%20elements/slider/sliderindicator.md), [Slider Track](https://github.com/able-app/docs/blob/8cd03de6556a6ec1dcd98dc8c2230863c5dba43c/controls/%CE%B5%20elements/slider/slidertrack.md), [Ruler Track](https://github.com/able-app/docs/blob/7e988f3a61132db2fd36d56763df3852f06ab3f5/controls/%CE%B5%20elements/slider/ruler.md), [ToolTip](https://github.com/able-app/docs/blob/7e988f3a61132db2fd36d56763df3852f06ab3f5/controls/%CE%B5%20elements/tooltip.md)

## Properties

### Type

**Continuous**: Provide the ability to set a value(s) along a subjective range.  The best example of this is volume control, where it isn't important to set to a specific value to a single value of volume, but a subjective range.

**Discrete**: The ability to set a specific value(s) that are snapped to based on allowed values, which can be optionally shown as tics along the track of the slider. With discrete sliders we normally display the selected value(s) as either a label or a floating tooltip above/below the selection knob(s).

### Choice

**Single**: Default, a slider bar with One value that it is setting.

**Dual**: A slider bar with Two values that can be set within the same bar.

### Size

The relative size of the slider as a whole in relation to other slider options.

### Ruler

The ruler with its tic marks can be turned On/Off with this property. The default is Off.

### State

- Enabled
- Disabled
- Hover
- Pressed
- Focus

### Other Properties

**Range:** Min/Max values

**Divisions:** Amount between discrete values

**Tic Location:** On(default), Above, Below, Left, Right

**Orientation:** Horizontal (default), Vertical

NOTE: We do not cover labels for values at this level.  That is cover one level up, in Slider.