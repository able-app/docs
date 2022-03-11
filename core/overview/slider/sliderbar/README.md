# Φ Slider Bar

Primitive: A visual bar that allows users to make selection(s) from a range of values with a press/click and drag of a knob.

[Styleguide Link](https://zpl.io/a7p4GWp)

* Parent: [Slider](../) (Control)
* Child: [Slider Knob](sliderknob.md), [Slider Indicator](sliderindicator.md), [Slider Track](slidertrack.md), [Ruler Track](rulertrack/), [ToolTip](../../tooltip.md)

## Properties

### Type

**Continuous**: Provide the ability to set a value(s) along a subjective range. The best example of this is volume control, where it isn't important to set to a specific value to a single value of volume, but a subjective range.

**Discrete**: The ability to set a specific value(s) that are snapped to based on allowed values, which can be optionally shown as tics along the track of the slider. With discrete sliders we normally display the selected value(s) as either a label or a floating tooltip above/below the selection knob(s).

### Choice

**Single**: Default, a slider bar with One value that it is setting.

**Dual**: A slider bar with Two values that can be set within the same bar.

### Size

The relative size of the slider as a whole in relation to other slider options.

### Ruler

The ruler with its tic marks can be turned On/Off with this property. The default is Off.

### State

* Enabled
* Disabled
* Hover
* Pressed
* Focus

### Other Properties

**Range:** Min/Max values

**Divisions:** Amount between discrete values

**Tic Location:** On(default), Above, Below, Left, Right

**Orientation:** Horizontal (default), Vertical

NOTE: We do not cover labels for values at this level. That is cover one level up, in Slider.
