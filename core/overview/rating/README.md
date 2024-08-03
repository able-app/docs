# ε RatingCtrl

Element: A collection of rate points (primitive) to form a scaled rating value for both interactive control and visual representation.

[Styleguide Link](https://zpl.io/29GBKQy)

* Parent: Multiple
* Child: [RatePoint](ratepoint.md)

### Properties

**Size** - The general size of the element as a whole.

<figure><img src="../../../.gitbook/assets/Size (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

**Style** - Supplied by the child level (Base - Shape) this is the general appearance of the screen object. Note: Additional appearance can be added to the Base - Shape file to extend the styles at this level.

<figure><img src="../../../.gitbook/assets/Styles.png" alt=""><figcaption></figcaption></figure>

**State** - The different appearances of the screen object based on interaction and the status of the screen object. Possible states are Enabled, Disabled.

<figure><img src="../../../.gitbook/assets/States (2).png" alt=""><figcaption></figcaption></figure>

### Interaction

**Hitarea** - It's important to understand that the tappable/clickable area of the screen object being displayed may be small in appearance than the actual area you can interact with. This hitarea will normally be based off the parents container for this element. [Here's an example](https://codepen.io/ashdurham/pen/HBxLK) of what we're looking for.
