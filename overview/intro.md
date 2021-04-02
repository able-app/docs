# Introduction

#### An overview of the design system structure

As the breadth of solutions and interconnected experiences grows, it becomes increasingly important to maintain a consistent style to ensure an expected and uniform experience. This will accelerate the design and development of solutions in addition to reducing user confusion and extended on-boarding. To do this, we’ve built a design system to document and store reusable aspects while also sharing best practices for faster design and development. The design system is broken down into Guidelines, Building Blocks, Libraries, and Resources.

## Building Blocks

#### The atomic assets and properties used in the creation of library objects

### Properties

At the base of our system are the styling properties of **type**, **color**, and **space** of the primitive elements and iconography. Style properties can be both global and/or platform dependent. For example, the solutions theme color, a global style, is reflected on all interface types independent of platform, where the theme typeface, an OS dependent style, changes depending on the platforms recommended typeface.

### Elements

The individual primitive interface building blocks used to build the objects that reside in the design system libraries are called elements. For example, the label of a textfield acts as element in the design, as it can’t be broken down further. Each element has their unique properties, such as typeface, color, size, and spacing, which make up the styles used in the design system.

### Iconography

Used as a visual language to represent type, level, status, content, or adding context to supporting material. Icons are meant to be a simple, immediately recognizable, visual representations. Icons are visual cues that provide clues about how the user should use the app using metaphorical associations. Iconography is treated in the same way as an element with color, size, and spacing properties.

## Libraries

#### Shared resources for design and development teams

### Components

Groups of elements bonded together, that follow the styles, flows, and behaviors from our libraries are considered components. These components contain the interface patterns, use to build consistent designs. With a centralized component library, the design and development process is accelerated across teams. As a simple example, a label \(text element\) and a single line text input field element can be bonded together to create a textfield component.

### Modules

Relatively complex groupings of components with a specific purpose are considered modules. A Sign In/Sign Up module or navigation drawer would be considered a module. Modules can also be thought of as self-contained and sellable, to those building their own solutions.

### Layouts

Layouts are the structural scaffolding and screen-level templates used for component and module layout. To build on the previous example of way-finding, we can stack a list module with the way-finding map module to display location based directions in a turn-by-turn style, adding context to map related activity.

### Patterns

People are hardwired to recognize patterns, it's in our DNA to connect the dots. Design patterns help to reinforce the relationship between different elements making the experience intuitive and predictable. The pattern library is where we store and document the most common patterns for reuse.

### Themes

To control the look and feel independent of the functionality or content of the solution we use themes. What that means is that you can change the design as often as you want without modifying the built in functionality or content. Solutions built with components, modules, and layouts that follow the theming system provide a consistent appearance and provide a quick method of changing the design.

### Metaphor \(Icons\)

Iconography is used to visually symbolize objects we're familiar with in the physical world. This helps the user interpret and navigate what they're seeing much quicker, and in less space than spelling out the metaphor in text format. The metaphor library keeps the iconography that we use, consistent across the different systems and teams that will build application interfaces.

