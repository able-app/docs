# Input Bar

Element: A grouping for design convenience for display in the bar component.  The bar component can have different background surfaces (colors) so we don't include a surface here. Input bars are often used in search situations or when short bits of text content is needed for input purposes.

[Styleguide Link](https://zpl.io/VOyn0QX)

- Parent: [App Bar - Extension](https://github.com/able-app/docs/blob/08eb774e348952235f1f4eb0369879387a684280/controls/components/appbar/app-bar-ext.md)
- Child: App Bar Control - [Leading](https://github.com/able-app/docs/blob/08eb774e348952235f1f4eb0369879387a684280/controls/components/appbar/abc-leading.md), [Center](https://github.com/able-app/docs/blob/08eb774e348952235f1f4eb0369879387a684280/controls/components/appbar/abc-center.md), [Trailing](https://github.com/able-app/docs/blob/08eb774e348952235f1f4eb0369879387a684280/controls/components/appbar/abc-trailing.md)

## Properties

### Layout

The general appearance of the element within the space.

- **Input Only:** No leading or trailing content only the primary input field is present in the bar.  This is commonly used in the App Bar Extension area when a search is needed but the App Bar itself is crouded with other actionable controls.
- **Icon Left:** A leading Icon before the primary input field. Often used when there's the need for a "Back" or "Close" navigational action or when there is a complimentary tool associated with the input field (IE. Find My Location, Scan a Barcode).
- **Icon Right:** A trailing Icon after the primary input field.  Normally used to filteer and sort the contents of a search or a list of pre-fetched content, which can also be searched with the input field.
- **Button Right:** A trailing Button after the primary input field. Used when the Input Bar is attatched to the top of the keyboard diring text entry sessions (IE. Chat conversations) where the Button acts as a "Add" to conversation, and the "Return" key on the keyboard can act as a why of creating a new paragraph in the conversation.
- **Icon Left & Right:** A leading and trailing Icon, used when we need  both a back and a filter/sort ability within the screen.
- **Icon Left, Button Right:** A leading actionable/navigation Icon, with a trailing Button to act as the Primary Action (IE. Submit to Conversation/Post).