# Φ SwitchCtrl

Primitive: A singular control switch with its possible status (on/off) and states.

[Styleguide Link](https://zpl.io/bLvqy06)

* Parent: [Switch](../../components/form/switch.md) (Form Component), Multiple others
* Child: [SwitchShape](switch-shape.md)

### Properties

**Status** - The value given to the screen object, in this case a switch with possibilities of On or Off.

<figure><img src="../../../.gitbook/assets/Status (3).png" alt=""><figcaption></figcaption></figure>

**Style** - Supplied by the child level (Base - Shape) this is the general appearance of the screen object. For now we only have the base style you'd normally see a switch, and a rectangular option which is our customized appearance for a switch. Note: Additional appearance can be added to the Base - Shape file to extend the styles at this level.

<figure><img src="../../../.gitbook/assets/Styles (1).png" alt=""><figcaption></figcaption></figure>

**State** - The different appearances of the screen object based on interaction and the status of the screen object. Possible states are Enabled, Disabled, Focus, Hover, Pressed.

<figure><img src="../../../.gitbook/assets/States (3).png" alt=""><figcaption></figcaption></figure>

### Interaction

**Hitarea** - It's important to understand that the tappable/clickable area of the screen object being displayed may be small in appearance than the actual area you can interact with. This hitarea will normally be based off the parents container for this primitive.

{% embed url="https://www.figma.com/proto/VN320MmRlLNR0UmdFula6N/Kitchen-Sink?node-id=2%3A23617&page-id=0%3A1&scaling=min-zoom&show-proto-sidebar=1&starting-point-node-id=2%3A24853&viewport=377%2C48%2C0.14" %}
