# ε Progress Indicator

Element: The combination of a leading label, progress bar, and trailing label to inform the user about the progress of an activity being done. Progress indicators are also commonly referred to as spinners. Much of what is found in the [MD component](https://material.io/components/progress-indicators#usage) is available here.

[Styleguide Link](https://zpl.io/2jyQewm)

* Parent: [App Bar - Ext.](../../components/app-bar/app-bar-ext.md), [Button](../button/) , [Icon](../icon.md), Listview, Modal
* Child: [Progress Bar](progressbar.md)

## Properties

### Shape

* Linear
* Circular

### Labels

**Leading:** Used to give context to the progress that is being displayed. This leading label can be an icon, such as a search icon, or text copy like "Searching".

**Trailing:** Used to provide either a percentage of the progress that's represented with the visual or to provide additional context to what's happening

**Inner:** For circular indicators a label can be present inside the visual indicator (circle) which is used to give additional context to the percentage of progress.

**Below:** For circular progress indicators there is an area to provide additional context or a message related to the action that is being done. This message can change either on a carousel rotation of new messages or linked to the status of the progress. For example, after 50% completion display "You're half way there" or upon 100% "Complete".

### Usage

* At the center of the screen in a modal or in a blank ListView to indicate the loading of screen contents
* In an [App Bar - Extension](../../components/app-bar/app-bar-ext.md) (above or below) that is revealed when a query is preformed and the screens contents are being refreshed.
* In place (replacing) of an action [Icon](../icon.md) to indicate the action is being done.
* At the end of an infinite scroll list when additional content is being fetched.
* Integrated into a [Button](../button/) to indicate an action is being preformed after a press
