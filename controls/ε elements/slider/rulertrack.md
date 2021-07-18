# Ruler Track

Primitive: The combination of the individual tics to form a series of tics along a track, similar to the tics on a ruler that indicate a specified value.

[Styleguide Link](https://zpl.io/bLJOLOd)

- Parent: [Slider Bar](https://github.com/able-app/docs/blob/7e988f3a61132db2fd36d56763df3852f06ab3f5/controls/%CE%B5%20elements/slider/sliderbar.md)
- Child: [Ruler Tick](https://github.com/able-app/docs/blob/7e988f3a61132db2fd36d56763df3852f06ab3f5/controls/%CE%B5%20elements/slider/rulertics.md)

## Properties

### Style

There are many different looks and densities that can be set for the tic track.  Multiple tic styles may even be mixed together within the same track (ie. circle major tics with minor ticks of line).  These tics will align with the possible values that can be set along the slider both spacially and value wise (ie. the knob points directly at a tic of value 2.5, which based on the sliders possible values as an option).

**None:** Default, no visual indicators on the Ruler Track.

**Circle, Square, Line:** Evenly distributed indicators along the Ruler Track.

**Line Major/Minor:** This is very similar to the appearance of a typical ruler with longer lines for whole numbers and shorter lines for fractional numbers. 

### Size

To account for the different sizes of ruler tracks we give different sizes of the tics here.

### Location

Tic tracks can be displayed on/in the slider track as an overlay (with transparency) or above or below the track, which works nicely with a knob that may be pointing to the tic track for a specific value.

### Other Properties

Here are a few other things to consider when constructing this primitive.

**Orientation:** Horizontal, Vertical

**Width/Height:** value

**Direction:** Start, End

NOTE: This is the first use of ruler and we will use this in other elements and components outside of the slider element in the future.