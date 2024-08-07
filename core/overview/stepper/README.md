# ε Paginator

Element: A collection of page points (primitive) to represent a series of steps involved in a process and your progress.

[Styleguide Link](https://zpl.io/aRRyz5E)

* Parent: [Paginator Panel](../../components/stepper-panel.md) (Form Component)
* Child: [PagePoint](steppoint.md)

### Properties

**Size** - The general size of the element as a whole.

<figure><img src="../../../.gitbook/assets/Size (1) (2).png" alt=""><figcaption></figcaption></figure>

**Style** - Supplied by the child level (Base - Shape) this is the general appearance of the screen object. Note: Additional appearance can be added to the Base - Shape file to extend the styles at this level.

<figure><img src="../../../.gitbook/assets/Style (7).png" alt=""><figcaption></figcaption></figure>

**Ornaments** - Each Step Point at a size of Large and above have the option to add ornamentation in the form of a Label Element, which can be text which is nice for placing numbers in each of the step points, or icons which could give a visual indicator of the task to accomplish at that step of the process when multiple step points are strung together into a Paginator.

**Status** - The status of each step point is given to the Paginator from its parent, turning on/off each step point as a visual indicator of where you are in the progression.

<figure><img src="../../../.gitbook/assets/Panel (1).png" alt=""><figcaption><p>Paginator Panel</p></figcaption></figure>

### Interaction

There is no direct interaction with Page Points or the Paginator Element, it acts as a visual indicator of where you are in a process (what Step of the process). This primitive is told by its parent the status of each of the page points in a series of steps (Pages), turning on and off the status of those steps. Possible parents to this element are a Screen (when a process involves multiple screens), an Image Carousel (Ex. Multiple photos of a product), Hero Carousel (Ex. Top CTA's for a section of the app).
