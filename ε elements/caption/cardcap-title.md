# Card Caption - Title

Collection:  A convenience container for the caption rows, which is made up of leading, primary, and trailing objects of the Cards caption rows.  Note, we separate those options that are possible in Cells from Cards at this level.  The sister collection to this one is the Cell Caption - Title.

**Cell:**  In bars we have repeating objects that are organized into cells.  This could be a single element like a graphic, or multiple objects (graphic, caption rows) that are combined to form the cell.

**Caption Rows:** We divide the cells caption into vertical rows These rows can then be added/subtracted from the cells caption depending on the use case.  In a caption row we have three columns, the leading, primary, and trailing content collections.

### Subject

Here we separate the titles into their intent which will allow us to make future alterations to the layout while only effecting that one style.

- Person
- Place
- Product
- Post
- Comment

### Size

- Small
- Medium
- Large

### Progress Stepper

These titles are often used together with an image above or below the title.  We use the progress stepper to indicate that there are multiple images that the user can swipe through, with the current image represented by the highlighted step in the progress stepper.  This control is On or Off for many of the subject matter titles.  Note, great care was taken to ensure that the layout is consistent if the progress stepper is present or not.

### Styles - Leading & Trailing

Here's where we bring in the columns (leading, primary, trailing) in order to customize the layout of the row. Those options available in the lower level caption containers for leading, primary, trailing are available to choose from.

