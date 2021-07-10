# Stepper

Element: A collection of step points (primitive) to represent a series of steps involved in a process and your progress.

[Styleguide Link](https://zpl.io/aRRyz5E)

### Structure -The "Properties" of the object.

**Size** - The general size of the element as a whole.

**Style** - Supplied by the child level (Base - Shape) this is the general appearance of the screen object.  Note: Additional appearance can be added to the Base - Shape file to extend the styles at this level.

**Ornaments** - Each Step Point has the option to add ornamentation in the form of a Label Element, which can be text which is nice for placing numbers in each of the step points, or icons which could give a visual indicator of the task to accomplish at that step of the process when multiple step points are strung together into a Stepper.

**State** - The different appearances of the screen object based on interaction and the status of the screen object.  States will normally be given to this Element from its Parent with possible states being Enabled, Disabled, Focus, Hover, Pressed.

### Interaction

There is no direct interaction with Step Points or the Stepper Element, it acts as a visual indicator of where you are in a process (what Step of the process). This primitive is told by its parent the status of each of the step points in a series of steps (Stepper), turning on and off the status of those steps.  Possible parents to this element are a Screen (when a process involves multiple screens), a Image Carousel (Ex. Multiple photos of a product), Hero Carousel (Ex. Top CTA's for a section of the app).