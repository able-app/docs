# ε FAB

Element: The Floating Action Button with set sizes for display with or without a status badge.

[Styleguide Link](https://zpl.io/b65y6Wq)

* Parent: [App Bar - Bottom](../../components/app-bar/)
* Child: [FABShape](fab-shape.md), [Badge](../badge/)

## Properties

### Size

To account for multiple usecases the design system has established a set sizing standard for FAB's. The size and shape of the FAB is set in the base level feeder of FAB - Shape and passed to this level.

<figure><img src="../../../.gitbook/assets/Size (2) (2).png" alt=""><figcaption></figcaption></figure>

* Tiny
* XSmall
* Small
* Medium
* Medium Extended

### Badge

Most of the time a FAB displays an icon as a metaphor for the primary action to take on the screens subject matter, but it does have the ability to carry a badge as well. For example, there may be a situation where the FAB acts as a shopping cart where the alert can serve as a cart count.

At the smaller sizes (Tiny, xSmall) of FAB the Badge only acts as a colored badge, meaning there is no numeric value or icon possible within the Badge. At the other sizes the numeric and icon badges are possible.

<figure><img src="../../../.gitbook/assets/Badge (1).png" alt=""><figcaption></figcaption></figure>

### State

<figure><img src="../../../.gitbook/assets/State (1).png" alt=""><figcaption></figcaption></figure>

* Enabled
* Disabled
* Hover
* Pressed
* Focus

### Style

The color of the FAB can be set to the following color display options...

<figure><img src="../../../.gitbook/assets/Style (1) (2).png" alt=""><figcaption></figcaption></figure>

* Primary (default)
* Secondary
* Light
* Neutral
* Dark
