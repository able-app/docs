# structure

## Libraries

All assets are organized in libraries and managed in a central repo \(GitHub\) with design token mapping to the resources. We consider assets to be any file that's referenced in the styles, elements and components of the design system. Examples of assets are font files, iconography sets, audio files, and illustrations. These source files are the base \(aka master\) files used in the design system. These files and folders are all stored in a parent folder of "assets", with each asset "type", images, fonts, illustrations etc. having their own folder.

## Quality Assurance

All elements, components, modules, screens are built to dynamically response to varying screen dimensions \(phone, tablet, web/desktop\). The intent is that development teams will then code to the functionality displayed in those components, modules, and prototypes. It’s the responsibility of every designer, prior to considering the design of an object or screen complete, to TEST their design to ensure that it functions as intended, primarily the dynamic resizing of objects for different screen sizes.

## Documentation

All design work/logic is clearly outlined in the "docs" repo and ready for review prior to pushing each object to the “Dev Ready” Kanban column. Clearly outlined meaning, enough detail to allow the developer to build the object with the desired, form and function.

## Communication

Use of a lightweight Kanban style management board \(Trello\) is used to keep track of design system objects and progression through the design and initial QA process. Hand off to core team members will happen within the Kanban board to communicate an objects readiness for development.

Note - A feedback mechanism will be set up to inform the design team of gaps in the system \(missing components or variants on a component to accomplish the desired functionality\). This feedback then gets evaluated by the core design team for the best solution and either resolved with the person giving the feedback or added to the backlog for addition to the design system.

## Screen Designs

All on screen objects are pulled from the Figma “Assets” area of the design system as instances. Those designers that are building screen designs should strive to not add any screen objects that do not exist in the design system. Screen designers are expected to attempt to solve all screen challenges with the existing design system. Often choosing the closest component to the desired need and looking at the different variants and turning on/off hidden layers in the components tree structure will provide a suitable solution.

If an object cannot be found to solve the needed functionality the designer will provide feedback to the Design System team. This feedback should include a solution proposal. This solution should be designed and shared in a separate Figma “Feedback” file showing how it works within the screen or across multiple screens. The core design system team will then take that proposed solution into consideration, research solutions and determine if that feature/functionality should be added to the design system. The final solution will then be shared with the person that submitted the proposal and added to the documentation repo.

