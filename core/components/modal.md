# Modal

Component: A popup/out dialog that appears in front of app content to inform the user about a task that can contain critical information, require a decision, or involve multiple steps to complete the task.

[Styleguide Link](https://zpl.io/aMXYxyR) (Shows the Scrim and Positioning)

* Parent: Screen
* Child: [Headline](headline.md), [Paragraph](paragraph.md), [Button Panel](button-panel.md), [Graphic](../overview/graphic/)/[Illustration](../overview/graphic/illustration.md)

## Properties

### Type

**Grants:** When we want to request access to the devices capabilities an OS controlled modal is displayed that asks the user if they want to grant the application access to that device capability. [Styleguide Link](https://zpl.io/2jyBdq4)

```
- Location
- Camera
- Microphone
- Face ID
- Bluetooth
- Calendar
- Photos
- Notifications
- Reminders
- Speech Recognition
```

**Actions:** Alert the user with urgent information, details, or actions that intentionally interrupt the applications use. [Styleguide Link](https://zpl.io/bzxDOd7)

```
- Paired: Side-by-side action buttons in a dialog
- 1 Action: A single actionable button in a dialog
- 2 Actions: Dual action buttons in the dialog
- 3 Actions: Three action buttons in the dialog
```

**Notifications:** Used to inform the user about new information based on location, time, associations, activities/releases, achievements, Notifications can happen when the app is running in the background, inactive, or in app. In addition to displaying a message notifications can also play a sound or update a badge on the app icon. [Styleguide Link](modal.md)

```
- Base: A standard OS notification with the app icon badge, app name, notification title, description where the notification modal acts as a deep link to the relevant content in the application.
- Actionable: Provide the user with a notification that lets the user respond without launching the app by making a selection with the provided button(s). Tapping a button sends the selected action to the app, which is processed in the background.
```

**Interactions:** Used for in-app user interaction that interrupts with a modal dialog window. [Styleguide Link](https://zpl.io/2Gqe5Pd)

```
- Super Action: A stylized modal dialog with a higher level of visual appeal (graphics/animation, controls, and buttons) than the standard action with simple buttons.
- Intro: A modal dialog that can be used to on-board or inform the user of new capabilities in a multi-step process with a possible carousel of graphics/illustrations.
- Rate: A modal designed to collect ratings information from the user.
- Alert: A modal designed to inform the user of time sensitive actions.
- Ad: The ability to display advertising billboards with deep links to the relative content or activity.
```

**Scrim:** Each modal window has the option of a transparency overlay behind the window. [Styleguide Link](https://zpl.io/29dYMGW)

```
- None
- 10%
- 20%
- 40% (Typical Light Mode Scrim)
- 60% (Typical Dark Mode Scrim)
- 80%
```
