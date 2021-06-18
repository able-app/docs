# CardItem

A single card cell (item) that can be organized into Bars (rows) of a vertical index (list).

### Functionality

CardItems can have multiple touch points the user can interact with.

1. **Primary Action:** When on its own, the primary action takes up the entire surface of the CardItem is used as a hit area to either navigate or take an action related to the contents of the CardItem.
2. **Secondary Action:** When a secondary action is added to the primary action the CardItem is divided horizontally into two hit areas.  The primary hit area takes up the majority of the space which is equal to the Leading and Primary content areas, and the secondary actions hit area covers the Trailing areas space. In cases where there is a button, icon or a text link they act as hit areas to take action or navigate on the contents of the ListItem. Note that this hit area would be no smaller than 56dp wide and the full height of the CardItem - Caption.
3. **Long Press:** Another option with CardItem interaction is the long press, which takes up the entire surface. A long press is considered anything over 1000ms on touch events and is equal to a right click in a web or desktop interface.  Often a long press will result in the reveal of a menu/sheet/modal that displays a list of options for that CardItem.
4. **Swipe Right-to-Left:** Gestures are also a way of interacting with a CardItem.  This action reveals hidden options that appear from behind the CardItem. These actionable options are those activities that are most often used with the CardItem. For example, in a list application an often used action may be to delete an item in the list, or archive it. For a desktop or web interface a click and drag could be used to accomplish the same functionality.
5. **Swipe Left-to-Right:** In the same way that a right-to-left gesture reveals additional actions, the left-to-right also does this same reveal of hidden options on the left side of the CardItem. An example of a good action here would be with a checklist where we want to quickly mark something as complete, a full swipe left-to-right would accomplish that activity.