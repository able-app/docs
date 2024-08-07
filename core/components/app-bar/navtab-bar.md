---
description: CAPABLE USING APP BAR
---

# NavTab

A combo of a left aligned back navigation (NavToggle) with a Tab - Bar. The navigation on the left side is a toggle button that has a width that hugs its content and the tabs to it's right will disappear behind it when they are side-scrolled.

NOTE: The left side nav could have one or more toggle buttons. In the example it's a solo toggle button, but if additional buttons are added it would form a toggle button group, pushing the Tab - Bar area to the right.

[Styleguide Link](https://app.zeplin.io/styleguide/6041aec8159a9b10c34d0182/components?cseid=60e5f9a7c9c9c207f78a9879)

Child: [Tab](../../overview/tab/), [NavToggle](../../overview/toggle/navtoggle.md)

## Properties

### Type

* **Icon:** Tab Bar with Icons on each Tab
* **Text:** Word(s) used on each Tab
* **Icon Left:** An Icon to the left of word(s) on the Tab
* **Icon Top:** An Icon above word(s) on the Tab

### Side-Scroll

**On:** The tabs area scrolls horizontally off the right side of the screen to reveal additional tabs

**Off:** The tabs area is locked to the width of the screen and does not scroll horizontally

### Surface

* Base: This uses the default Mode (Light) for the tab bar. If the devices mode were to be changed in the settings or by the device settings this would also change to reflect that setting.
* Dark Lock: This locks the background color to a darker tint.  This is useful for areas of the app like the camera where we want to keep the tab bar in a darker mode no matter the settings of the app or device.

