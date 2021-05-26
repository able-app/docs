# Snackbar

Element: Snackbars provide brief messages about app processes on the screen. These normally do not require user interaction, and disappear from view after a short period of time.

### Actions

A snackbar can contain a single action. "Dismiss" or "Cancel" actions are optional.

### Layout - Action

None - No actionable activities are associated with the notification

Beside - The default, when an actionable event is presented to the user.

Below - For actions that have longer wording we can place the action below the message.

### Content - Message

The message should be short and to the point, taking up no more than two line in the snackbar.

### Behavior

Snackbars appear one at a time upon an event trigger, and don't require interaction from the user. They disappear from view automatically, with the time of display ranging depending on the use case but normally between 1000ms and  5000ms.