# Bar - Toggle

Element: Adds a wrapper around another element for display in the bar component. At this level we're not adding a surface to the bar since there are multiple bar styles with different background surfaces. The spacing and fixed/scroll alignments are added here and a surface for the bar is added at the parent level to this one.

## Type

The options available in the "Toggle" element are capable here.

* Multi - A group of toggles \(default\)
* Single - A grouping of solo toggles. An example of this could be different filters on a search, where each toggle is a different filter type \(price, weight, rating, etc.\) The Yelp app uses this fairly well in their filtering of search results.
* Hidden - A group of toggles with a hidden button surface

## Behavior

* Fixed - New toggles that don't fit within the fixed width, wrap to the next row, growing the height of the bar - toggle.
* Scroll - Toggles that don't fit within the defined width of the parent container scroll off the side of the bar - toggle \(screen\).

