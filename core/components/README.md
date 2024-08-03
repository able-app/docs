# Components

**An interface object built out of elements or by nesting other components, with a background surface and spacing, to serve as a reusable object in building interfaces (Modules & Screens).**&#x20;

Components are the Lego pieces we stack together in a ScrollView to design experiences.  Components provide focus to the screen designer by solving user needs when designing screens. This is the concept of an abstract component, where the focus is on the intent, as opposed to the interface. Think of an abstract component as the skeleton. And the manifestation at each breakpoint (phone, tablet, desktop, web, etc.), as the skin of the component handled by the Theme.

Components dynamically scale horizontally to fill the width of the screen, but in 99% of cases DO NOT scale in height. All components are designed to stack vertically on top of one another, with no vertical spacing between them, in a ScrollView. The ABLE Design Systems definition of a Component goes beyond those that you typically see in other frameworks like Bootstrap, Angular or Ionic which for the majority of screen objects, all stop at the Element level under our definition of an Element here.

_Note that Components do not carry a Greek character._



We've set up a Kitchen Sink application that isolates all elements and components into their own screens to show the different variations of each.

