# Avatar

Element: Set sizes for display with or without a status badge. Avatars focus on a subject, using a simple background. They often represent a user or a brand, and are commonly used to represent a user/brand in messaging formats like sms and email.

[Styleguide Link](https://zpl.io/bey1LvW)

- Parent: [Avatar - Bar](https://github.com/able-app/docs/blob/7bb2457d172a78e9e6528e086a642c45224c701f/controls/%CE%B5%20elements/avatar/avatar-bar.md), ListItem, Multiple others
- Child: [Badge](https://github.com/able-app/docs/blob/7bb2457d172a78e9e6528e086a642c45224c701f/controls/%CE%B5%20elements/badge/badge.md), [Avatar - Shape](https://github.com/able-app/docs/blob/7bb2457d172a78e9e6528e086a642c45224c701f/controls/%CE%B5%20elements/avatar/avatar-shape.md)

## Properties

### Size & Shape

To account for multiple usecases the design system has established a set sizing standard for certain interface objects, with Avatar being one of those.  The size and shape of an Avatar is set within the base level feeder of Avatar - Shape.

### Status Badge

An avatar can have a status badge present to show the user/brands current status (online, offline, busy, etc.) or no badge, which may be more appropriate for lists of users.

### State

The state of any nested object (ie. an element inside of a component) get's its state from the parent it is nested within. The state for an Avatar is normally dictated by its parent level container.

- Enabled
- Disabled
- Hover
- Pressed
- Focus

