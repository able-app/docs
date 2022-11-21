# ε Chip

Element: A compact elements that represent an input, attribute, or action.

[Styleguide Link](https://zpl.io/ble1PwG)

* Parent: [Chip - Bar](chip-bar.md), [Field - Content](../field/field-content.md)
* Sister: [Chip - Modal](chip-modal.md)
* Child: [Label](../label.md), [Icon](../icon.md), [Avatar](../avatar/)

## Properties

### Type

These types mirror those outlined in MD for further information [see here](https://material.io/components/chips#types).

**Input** - When a single selection is being made from a collection of options usually consisting of a person, place or thing (tangable objects). This is used to represent complex info in a compact format. These Chips can be added to a collection and removed from the collection using th "clear" icon on the right side of the Chip.

* **Icon** (default) - The use of an Icon in the Leading position of the Chip to give context as to the subject of the Chip in a small space.
* **Avatar** - The use of an Avatar in the Leading position of the Chip to give a visual of the subject of the Chip (usually a picture of a person).

**Choice** - When a single selection is to be made from a collection of mutually exclusive options. When selected (Status:On) the appearance of the Chip changes to represent the choice. For example, "How would you like your stake cooked? a) Raw b) Rare c) Medium d) Medium Well e) Well Done". Choice Chips can also be used in canned responses to contain a sentence for quick one tap responses in chat.

**Filter** - When the user is presented with a collection of options where we want to allow them to select one to many options from the collection. When a Chip has an On status it will appear with a leading checkmark and have its appearance changed. For Ex. in a filter for T-shirt shopping you could select Large, and XLarge or in another situation select vehicle types of SUV or Car excluding Trucks, Vans, etc.

<figure><img src="../../../.gitbook/assets/Type (6).png" alt=""><figcaption></figcaption></figure>

### Style

**Filled** (default) - The Chip has a filled appearance in that the Chips surface is different from the background it is on.

**Line** - The Chip has an outline appearance with the surface of the Chip being the same color as the surface it is on top of.

<figure><img src="../../../.gitbook/assets/Style (4).png" alt=""><figcaption></figcaption></figure>

### Status

**Off** - Shows visually that the Chip is turned Off or Inactive. For Ex. when off the Chip for a search filter would display the type of filter that can be applied by turning the Chip's status to On.

**On** - Shows that the Chip is active and being applied. For Ex. in search filters, different filtering methods can be turned on/off and those that are on will display the details of that filter in its contents and show that it is active by its color.

### State

<figure><img src="../../../.gitbook/assets/State (4).png" alt=""><figcaption></figcaption></figure>

* Enabled
* Disabled
* Hover
* Pressed
* Focus

### Size

Note: This will normally only be used in the design of components, but we want to ensure we keep to standard sizes throughout, thus this property.

**Base** (default) - The normal size of a Chip

**Field** - The size of a Chip when located inside of the Field element. We had to decrease the height of the chip slightly to comfortably fit within the Field.

<figure><img src="../../../.gitbook/assets/Size (1) (2) (1).png" alt=""><figcaption></figcaption></figure>

### Metaphors

We use the metaphors (aka Icon Library) to standardize on the meaning of icons used in the application. In the Chip element we have two metaphors.

**Clear**: Icon-Library > Base > Act - Clear

**Choice**: Icon-Library > Base > Act - Choice Lite

{% embed url="https://www.figma.com/proto/VN320MmRlLNR0UmdFula6N/Kitchen-Sink?node-id=2%3A24825&page-id=0%3A1&scaling=min-zoom&show-proto-sidebar=1&starting-point-node-id=2%3A24853&viewport=377%2C48%2C0.14" %}
