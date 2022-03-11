# Actions

At next layer up in the Design System is our "Actions" kit containing Modules, Screens, Flows and Collections of these that can be assembled into a self contained app Extension. When referring back to the [Atomic Design](https://bradfrost.com/blog/post/atomic-web-design/) principles these equate to "Organisms", "Templates", and "Pages". This is where we start to build out the functionality of the actionable activities that a user will do within the application. For example, most applications have a Sign Up process that have a series of Screens (Name & Pass > Recovery Email > Choose Username... ) in a Flow. Where one of those screens, or parts of the screen could be the Module for turning on FaceID.  Here's how we break down the Actions kit...

## **Ξ** Modules

Think of modules as self-contained, single purpose objects. They often are relatively complex groupings of components, with a specific purpose that can be full screens or parts of the screen. As an example, GridView (listing of graphics in a grid) or FaceID example from above would be considered a module.

## Screens

This is where Modules and Components from Core are combined to form a screen design at each of our different screens sizes, referred to as "breakpoints" for phone, tablet, web/desktop. Our default screen width for all Component is set to 360 dp, but they are all built to dynamically adapt to different screen widths.

## Flows

The Screen to Screen interaction in how a user accomplishes a task. How does the screen, modal, sheet, etc. enter the view, or exit the view... does it fade in, does it slide in from the left or up from the bottom. These transitions are important in guiding the user through the flow of an Action. Remember those Dictionaries in our Theme, here's where they come into play.

## Extension

The end result of our Modules, Screens and Flows between them is a stand alone Extension. An extension can exist as a section of the application, as would be the case with a Sign Up process, or as a helper to an existing Extension, like we'd likely see with a Profile Extension having a helper for Wallet.
