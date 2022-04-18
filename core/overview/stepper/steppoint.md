# Φ StepPoint

Primitive: A single point of a Stepper (element) with its possible status.

[Styleguide Link](https://zpl.io/V13oQdX)

* Parent: [Stepper](./)
* Child: [StepPointShape](steppoint-shape.md)

### Properties

**Status** - The value given to the screen object, in this case a single step point inside of a series of steps (stepper) with status possibilities of On or Off.

**Ornament** - Each Step Point at Large and above have the option to add ornamentation in the form of a Label Element, which can be text which is nice for placing numbers in each of the step points, or icons which could give a visual indicator of the task to accomplish at that step of the process when multiple step points are strung together into a Stepper.

**Style** - Supplied by the child level (Base - Shape) this is the general appearance of the screen object. For now we have two styles, the normal appearance of the circular step point which is the default, and a square which is our customized appearance for a single step point. Note: Additional appearance can be added to the Base - Shape file (ie. diamond, tiangle) to extend the styles at this level.

### Interaction

There is no direct interaction with Step Points, it acts as a visual indicator of where you are in a process (what Step of the process). This primitive is told by its parent the status of each of the step points in a series of steps (Stepper), turning on and off the status of those steps.

NOTE: This is not meant to be an object that the user interacts with, it is truely a visual indicator.
