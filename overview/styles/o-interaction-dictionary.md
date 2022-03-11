# Ω Interaction Dictionary

Here we outline all gesture types available in the app. We go into detail on each below and this is the general overview. Understand that every element, component, module etc. in the design system will need to carry the ability to use any of these gestures.

We'll define the base level defaults for all gestures on mobile and web/desktop here. These may be altered on an individual bases dependent on the situation, but whats outlined here will act as the default.

We'll start with some basics here and add to them over time. So just think of this area as the space we share the default ways we treat each of these gestures in the design system.

### Tap - Single

Design Token: gestTap

This is your primary action for any on screen object. Every element, component and module will carry methods of interaction with it and this will be the most common one by far. In most cases the activity is to navigate to a new screen or reveal a menu or sheet to choose an action to take. When we define each element and component we will document each gesture and the action it takes if part of a larger module.

### Tap - Double

Design Token: gestTapD

By default this is to open up the “Quick Actions” Modal for the item being interacted with. (ie double tap on a Lists Card will bring up the Quick Actions for that list). If you want to do something with an object the double tap is the method we use.

### Tap - Triple

Design Token: gestTapT

By default this is to toggle the tool tips On/Off for ALL components. A tooltip is meant for those that are still learning how the app works and what certain things do.

### Tap - Long

Design Token: gestTapL

By default this is to open up the Settings for the object being long-pressed. The settings are on a new screen that loads when a long-press is detected on an object.

### Press + Drag

The concept of a press and drag can be at different levels of an app.&#x20;

* At the element level where it may reveal a menu or something within the element.&#x20;
* The component level where it can reveal a hidden menu like we do on a lisItem to reveal buttons behind a ListItem, or a resize ability like we have with image editing.
* Screen level drags are intended for navigational purposes to reveal overarching concepts like a drawer with a swipe from the edge or moving between screens in an on-boarding carousel (previous/next).

#### Contextual Actions

When a swipe is used we reveal the top actions in a reveal for that object. The possible actions are any of those listed as Global Actions, but could include others. One example being, a To-Do list, where a user would like to check something off of the list with a simple left-to-right swipe of a list item. Here’s a good article explaining its use and best practices... [https://www.nngroup.com/articles/contextual-swipe/](https://www.nngroup.com/articles/contextual-swipe/)

#### Swipe - Right to Left

Design Token: gestSwipeL

This type of swipe, by default reveals the tops action(s) for the object.

#### Swipe - Left to Right

Design Token: gestSwipeR

With a swipe left to right we will most often preform the top activity for the object. These activities could be: Check-off, Print Label, Comment, Favorite, Share, Assign, etc. In some situations we may have more than one activity. In these situations we reveal the menu choices, with a full swipe preforming the top activity. You can see an example of this in the Microsoft Outlook iOS app when interacting with an inbox message. NOTE: Not all options will be available to every object, they are contextually used.

#### Adding Functionality

When we have list items with the "More” icon, we still add left and right swipe to reveal. This adds to the functionality of the “More” with a quicker action for more advanced users.



### Transform

Changing an objects size, position, and rotation in response to a user generated action. Here's a good looking project that handles animation...&#x20;

{% embed url="https://docs.swmansion.com/react-native-reanimated" %}

#### Reaction to Scroll&#x20;

When any list is being scrolled we want to hide the header and footer along with the FAB. The interaction would be...

While scrolling

1. The header hides, moving up and fading away over 250ms
2. The footer and FAB moving down with a fade away over 250ms.
3. Once the list stops scrolling the process reverses (fade back into position).
4. Option to have a sticky minified app bar (Explained below).

This link isn't exactly what we're looking for but close. [https://medium.com/android-news/scroll-your-bottom-navigation-view-away-with-10-lines-of-code-346f1ed40e9e](https://medium.com/android-news/scroll-your-bottom-navigation-view-away-with-10-lines-of-code-346f1ed40e9e)

#### Sticky Minify on Scroll

In addition to the above we will want the option to minimize (make the app bar smaller) in the header on scroll. This is often used in webview browser mode, where the name of the page becomes really small at the top center and content will scroll behind it. The default should be to hide with this as an option.

#### Pull to Refresh

Want the ability to pull the list down to initiate a refresh of contents on any list globally. Here’s an example... [https://medium.com/enappd/refreshcontrol-pull-to-refresh-in-react-native-apps-dfe779118f75](https://medium.com/enappd/refreshcontrol-pull-to-refresh-in-react-native-apps-dfe779118f75)

#### Lazy Load

Load list contents outside of the viewport so it appears to be an infinite list. The desired effect is to have list items in an infinite list where we won't see images/content loading within the view.

Sticky ListHeaders

For groupings with listheader dividers in the list (ie. User contacts in alphabetical order), sticky listheaders will be used similar to this... [https://docs.nativebase.io/docs/examples/StickyHeaderExample.html](https://docs.nativebase.io/docs/examples/StickyHeaderExample.html)

#### Shimmer Placeholders

For those that do show, or for an initial view where we don't have any data yet, we'd want to show activity using a shimmer effect. Most popular apps (Facebook, Instagram, Pinterest) handle it this way. Like this... [https://github.com/Ashwin-Mothilal/react-native-js-shimmer-placeholder](https://github.com/Ashwin-Mothilal/react-native-js-shimmer-placeholder)

#### Progress Indicator - Style

Default to a circular progress indicator, but we will want the ability to add in our own animated graphic gif/svg or a Flare (Rive) object for the indicator in the future.

The location of a progress indicator can be in a different location depending on the situation...

1. In a Button. The Icon and text of the button switch to a loading indicator and/or text upon press.
2. App Bar. When a list is loading or a search is being done the linear infinite loading version is displayed at the bottom of the app bar. This is the default method, with a more pronounced loading circular indicator being an option when we want to give more weight to the loading/searching.
3. On a Screen. Sometimes we will have dedicated success screens with loading feedback.



### TYPES

### Navigational

Helps the user move through the application easily with simple interactions with the screen and/or device.

* Tap - gestTap
* Drag - gestDrag
* Flick - gestFlick
* Swipe Left - gestSwipeL
* Swipe Right - gestSwipeR
* Swipe Up - gestSwipeU
* Swipe Down - gestSwipeD
* Double Tap - gestDblTap
* Pinch - gestPinch
* Long Tap - gestLongTap
* Shake - gestShake

### Action

A gestural move done as a shortcut to complete an action

* Draw Z -&#x20;
