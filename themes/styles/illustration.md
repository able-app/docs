# Ω Illustration

Used as a way to visual tell a story and add visual eye-candy to the layout. Illustrations are meant to support the purpose of the screen in an easy to understand visual narrative of an object or activity. Illustrations are visual cues that provide clues about how the user should interact with the screen using metaphorical associations.

## Illustration Library

With any application there will be the need for some level of visual story telling throught graphics and illustrations. To provide a scalable, consistent, and easy way to move between different illustration families we use an Illustration Library. This ties a metaphor, the intent/idea behind an visual to a design token which can have one or more words associated with it. As an example, lets take the idea "metaphor" of a security screen. We can use the design token "guard" for that illustration in multiple illustration canvas, and screen across the application and then have the ability to swap out that illustration, app wide from a single source of truth in the library. In the library we define each metaphor independently.  In the previous example of "security" we might have used a visual with a padlock with a hand stating stop, along with other visual flares. That same illustration could be used to represent another metaphor for example "security". By having the two metaphors represented in the Illustration Library as separate objects we can change out the "Security" metaphor for a different visual without effecting the "guard" illustration hooks throughout the app. This also gives us a way of swapping out an entire illustration family (ie link a new Illustration Library file) for another when you want to change the look and feel of the application.

### Properties

**Name**: \[textField\] The human readable way we refer to this "Illustration" in the metaphor library

**Family**: \[selectList\(Assets.Illustration\)\] The icon family that this illustration is in. The list of available illustration families is pulled from the Assets &gt; Illustrations folder. Those illustration families that have been uploaded into the system.

**Resource**: \[searchGallary\(selectedFamily\)\] Every illustration will have a source file that it references to provide the look of the illustration.

**Metaphor**: \[textField\] Every illustration acts as a metaphor for something. Some illustrations can carry multiple metaphors \(i.e. "lock" and "security" for the ill-secure.svg\) This allows us to reuse these metaphors as a design token which is referenced throughout our components while all carrying the same look.

**Referenced By**: \[textArea.ReadOnlyCsvList\] The list of elements and components that are referencing this library

**Token**: \[textField\] The short-code we use to refer to this metaphor \(i.e.. \#illSecure, \#illFaceID, \#illAccount, etc.\)

### Base Metaphors

| **Name** | **Family** | **Resource** | **Metaphor\(s\)** | **Token** |
| :--- | :--- | :--- | :--- | :--- |
| Secure | Security & Safety | ill-secure.svg | lock, security, guard | \#illSecure |

