# ε RatingCtrl

Element: A collection of rate points (primitive) to form a scaled rating value for both interactive control and visual representation.

[Styleguide Link](https://zpl.io/29GBKQy)

* Parent: Multiple
* Child: [RatePoint](ratepoint.md)

### Properties

**Size** - The general size of the element as a whole.

**Style** - Supplied by the child level (Base - Shape) this is the general appearance of the screen object. Note: Additional appearance can be added to the Base - Shape file to extend the styles at this level.

**State** - The different appearances of the screen object based on interaction and the status of the screen object. Possible states are Enabled, Disabled.

### Interaction

**Hitarea** - It's important to understand that the tappable/clickable area of the screen object being displayed may be small in appearance than the actual area you can interact with. This hitarea will normally be based off the parents container for this element. [Here's an example](https://codepen.io/ashdurham/pen/HBxLK) of what we're looking for.

{% embed url="https://www.figma.com/proto/VN320MmRlLNR0UmdFula6N/Kitchen-Sink?node-id=2%3A23638&page-id=0%3A1&scaling=min-zoom&show-proto-sidebar=1&starting-point-node-id=2%3A24853&viewport=377%2C48%2C0.14" %}
