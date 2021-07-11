# Rate Point

Primitive: A single point of a ratings (element) with its possible status.

[Styleguide Link](https://zpl.io/VQJrR84)

- Parent: [Rating](https://github.com/able-app/docs/blob/b10f6d1205bbfb1cddfd150d1390ba848812d9d0/controls/%CE%B5%20elements/rating/rating.md)
- Child: [Rate Point - Shape](https://github.com/able-app/docs/blob/b10f6d1205bbfb1cddfd150d1390ba848812d9d0/controls/%CE%B5%20elements/rating/ratepoint-shape.md)

### Structure -The "Properties" of the object.

**Status** - The value given to the screen object, in this case a single step point inside of a series of steps (stepper) with status possibilities of On or Off.

**Style** - Supplied by the child level (Base - Shape) this is the general appearance of the screen object.  For now we have two styles, the default star appearance of a single rate point, and a heart which is our customized appearance for a single step point.  Note: Additional appearance can be added to the Base - Shape file (ie. diamond, tomato "rotten tomatoes style") to extend the styles at this level.

### Interaction

Rate Points act as a visual indicator of a rating as well as the point of interaction to provide a rating. A slide of the finger along multiple Rate Points will activate each of those that are rolled over in the series of rate points (Rating). So for example, if the finger starts at Rate Point 1 (far left) and is held and drug to Rate Point 4, 1-4 will have a status of On and Rate Point 5 will have a status of Off.  Now lets say you start the finger at 4 and move down to 2, then only the first two Rate Points would be On and the remaining 3 Off.