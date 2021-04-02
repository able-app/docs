# Spacing

Whitespace is crucial to drawing the user’s attention to key areas, maximizing readability and guiding the flow of information. As with typography, by adhering to a spacing scale, we can ensure that each component and layout will be uniform. To keep spacing consistent between elements and allow the interface to both breathe and accommodate information rich interfaces we've modeled our spacing on Android’s Material design soft grid system which follows the 8dp grid.

The basic principle of the eight-point grid is to design screen elements using multiples of eight, whenever possible. This type of grid system is used to ensure a consistent unit of measurement between designers.

## Dictionary

Just as type and color has a dictionary we have one for spacing both at the component level and at the layout level. Both are designed to complement components and typography throughout the system. It's important to divide our spacing into two different roles in the display of objects on the screen.

**Spacing Scale:** Used for smaller spacing needs which are often found in the layout of components \(i.e. the space between two elements in the component like the label and a textfield in a component\)

**Layout Scale:** Most often used for the positioning of components within the screen \(i.e. the space between a textField and selectList component on a form\).

## Spacing Scale

Just as color has a palette and type has a scale we have a scale for spacing. Within spacing we break down the scale into its building blocks. These building blocks then contain the rules of our space scale. The spacing scale is used in the construction of individual components. The scale uses small increments to create consistent and appropriate spatial relationships between objects in the design.

### Properties

The structure of these properties follows that of all Size properties which can be found in the parent to this section "Size".

| Name | Size \(dp\) | Token |
| :--- | :--- | :--- |
| 0dp - Spacing | 0 | \#none |
| 2dp - Spacing | 2 | \#tiny |
| 4dp - Spacing | 4 | \#xxs |
| 8dp - Spacing | 8 | \#xs |
| 16dp - Spacing | 16 | \#s |
| 24dp - Spacing | 24 | \#m |
| 32dp - Spacing | 32 | \#l |
| 48dp - Spacing | 48 | \#xl |
| 56dp - Spacing | 56 | \#xxl |
| 64dp - Spacing | 64 | \#huge |

## Layout Scale

Used for arranging components as part of a screen layout. This scale tends to offer larger increments than the spacing scale to increase the amount of white space between components and disassociate separate sections from one another. A good example of layout spacing happens with the Card component in a list. The spacing between the sides, top, and bottom of the cards is managed by the layout scale. In that card we might have spacing on the sides set to \#xs \(8dp\) and the top and bottom of cards set to \#tiny \(4dp\).

### Properties

The structure of these properties follows that of all Size properties which can be found in the parent to this section "Size".

| Name | Size \(dp\) | Token |
| :--- | :--- | :--- |
| 0dp - Layout | 0 | \#none |
| 4dp - Layout | 4 | \#tiny |
| 8dp - Layout | 8 | \#xs |
| 16dp - Layout | 16 | \#s |
| 24dp - Layout | 24 | \#m |
| 32dp - Layout | 32 | \#l |
| 48dp - Layout | 48 | \#xl |
| 64dp - Layout | 64 | \#xxl |
| 96dp - Layout | 96 | \#huge |

