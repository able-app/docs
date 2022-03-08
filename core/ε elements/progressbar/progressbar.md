# Progress Bar

Primative: A visual indicator to express either a determined length of time an activity will take, an indeterminate amount of time, or the fact that a query or buffer is happening.  Common uses are the loading of screen contents, video/audio files, the submission of a form, or a software update.

[Styleguide Link](https://zpl.io/Vx9Lo1k)

- Parent: [Progress Indicator](https://github.com/able-app/docs/blob/d689178b930c7095c750671b112985ac09eccd08/controls/%CE%B5%20elements/progressbar/progressindicator.md)

## Properties

### Size

The relative size in relation to the other bars in the collection.

- Tiny
- XSmall
- Small
- Medium
- Large

### Shape

**Linear:** A bar that displays horizontally to indicate progress.

**Circular:** A bar that displays in a donut shape with the progress being shown in the shape

### Type

**Determinate:** Show how long a process will take.  Used when the time to complete is known.

**Indeterminate:** When an unspecified amount of time is found.  Used when the time to complete ISN'T known, or it isn't important to show the length of time remaining.

**Query:** During the time the app is communicating with the backend we show a visual indicator of that process in an animated dashed progress bar.

**Note:** As we know more about a process (loading, saving, etc.), the type can change from Indeterminate to Determinate.

<ProgressLine color="primary" size="small" type="determinate" value={progress} />

<ProgressCircle color="primary" size="medium" type="indeterminate" value={progress} />