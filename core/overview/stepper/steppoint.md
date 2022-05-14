# Φ PagePoint

Primitive: A single point of a Paginator (element) with its possible status.

[Styleguide Link](https://zpl.io/V13oQdX)

* Parent: [Paginator](./)
* Child: [PagePointShape](steppoint-shape.md)

### Properties

**Status** - The value given to the screen object, in this case a single page point inside of a series of steps (paginator) with status possibilities of On or Off.

**Ornament** - Each Page Point at Large and above have the option to add ornamentation in the form of a Label Element, which can be text which is nice for placing numbers in each of the page points, or icons which could give a visual indicator of the task to accomplish at that step of the process when multiple page points are strung together into a Paginator.

**Style** - Supplied by the child level (Base - Shape) this is the general appearance of the screen object. For now we have two styles, the normal appearance of the circular page point which is the default, and a square which is our customized appearance for a single page point. Note: Additional appearance can be added to the Base - Shape file (ie. diamond, tiangle) to extend the styles at this level.

### Interaction

There is no direct interaction with Page Points, it acts as a visual indicator of where you are in a process (what Step of the process). This primitive is told by its parent the status of each of the page points in a series of steps (Paginator), turning on and off the status of those steps.

NOTE: This is not meant to be an object that the user interacts with, it is truly a visual indicator.
