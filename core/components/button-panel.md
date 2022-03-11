# Button Panel

Component: A collection of buttons vertically or horizontally displayed with padding and elevation

[Styleguide Link](https://app.zeplin.io/styleguide/60470191ec4e65a27a43e21c/components?cseid=604e5635eda5f48a6895f219)

* Child: [Button](../overview/button/)

### Properties

**Qty** - The number of buttons contained within the panel

**Orientation** - The direction that the buttons are situated in the panel, stacked on top of one another vertically, or aligned side-by-side horizontally.

**Padding** - An On/Off toggle to have no padding or to apply padding. Generally only square buttons will not have padding, and others (even square) will have padding.

**Elevation** - An On/Off toggle to determine if the panel should have an elevation applied to it. This comes in handy with dock to bottom button panels that have scrollview lists that flow behind them.

**State** - The possible visual appearances, which are also tied to functionality of the given object. ie Disabled and the object can not be interacted with and visually shows that. States are handled within each of the individual buttons contained within the panel, but we will want a parent child relationship at the panel level to inform the child buttons on a state change.
