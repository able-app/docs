# Element - Metaphors

The visual queues to activities get assigned a design token in the metaphor library. That design token is then used to reference that metaphor in primitives, elements, and components throughout the system. This provides the ability to swap an icon out globally, without going into every single instance where it is used to make a change.

Icon metaphors reference the SVG source files found in the assets folder. In that assets folder we have multiple svg libraries (ie. Flags, emoticons, specific icon libraries etc.)

Design tokens need to carry a unique name which is referenced to build the component.

Here are the metaphors that are used in elements...

**Clear:** Used to reset fields and removing chips.

**Check:** Used to represent a selected Chip - Filter

**Circle Check:** Used as an over-ride to the shape of checkbox and radio button to customize its appearance for use within lists.

- Status: Selection On
- Status: Selection Off
- Status: Indeterminate