---
description: The master files used to build screens
---

# Core

At the heart of the Design System is our "Core" kit containing Primitives, Elements, Components and Collections of these. Elements and Components are the equivalent to Atoms and Molecules in the [Atomic Design](https://bradfrost.com/blog/post/atomic-web-design/) structure. _Note, we've added our own lower level of "Base (Particles)" and other segmentations like "Primitives" and "Collections" to add much needed layers to the Atomic Design structure when speaking to the way we actually need to organize things in the design system._

## **Φ** Primitives

At both the Element and Component level we have the need to separate out parts of the object (Element or Component) into even more simplistic objects before combining them as an element or component. Primitives are how we classify these simple objects. A good example of a "Primitive" is a single Tab, which doesn't serve much of a purpose on its own, but when combined with other tabs, in an "Element" it is able to realize its purpose/function.

## **ε** Elements

The individual or combined primitive interface building block(s) used to build components in the design system. These objects typically don't have much use on their own, but when combined with other elements to form a component serve a defined purpose. Elements do not have any spacial spacing characteristics outside of its own borders, meaning its spacing to other objects on the screen. Those spacing choices are applied at the Component level. Elements are never used to build screens directly, they are strictly used to build Components, which are then used to build screens.

## **Θ** Collections

From time to time, to keep things logically organized in the design system we use a Collection. All this is, is a container for us to keep like items together. Know that a Collection can consist of Primitives, Elements and even Components. It's use strictly for organization purposes. A good example of how this is used in the design system is in how we structure a ListItem into Leading, Primary, and Trailing Collections that display in the same relative location in the ListItem but serve different purposes. In the design this provides for a single Component called ListItem, that has hundreds of variations based on the choices for Leading, Primary and Trailing.

## Components

**A component is an interface object built out of elements or by nesting other components, with a background surface and spacing, to serve as a reusable object in building interfaces (Modules & Screens).** They’re the Lego pieces we stack together in a ScrollView to design experiences. _Note that Components do not carry a Greek character._ Components provide focus to the screen designer by solving user needs when designing screens. This is the concept of an abstract component, where the focus is on the intent, as opposed to the interface. Think of an abstract component as the skeleton. And the manifestation at each breakpoint (phone, tablet, desktop, web, etc.), as the skin of the component handled by the Theme.

Components dynamically scale horizontally to fill the width of the screen, but in 99% of cases DO NOT scale in height. All components are designed to stack vertically on top of one another, with no vertical spacing between them, in a ScrollView. The ABLE Design Systems definition of a Component goes beyond those that you typically see in other frameworks like Bootstrap, Angular or Ionic which for the majority of screen objects, all stop at the Element level under our definition of an Element here.
