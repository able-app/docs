# Motion

The component as a whole can also have motion applied to it. An example of this might be the "Flash" of a ListItem when it is selected from a list.

## Resources

These resources would be stored in the snippets library as pieces of code that can be used across the application and referenced through the token assigned to it in the snippets library.

[https://pub.dev/packages/flutter\_animator](https://pub.dev/packages/flutter_animator)

**Prebuilt Types**: Bounce, Flash, HeartBeat, Pulse, Rubber Band, Shake, Head Shake, Swing, Tada, Wobble, Jello

**Enter/Exit Types**: Bounce, Fade, Flip, Lightspeed, Rotate, Slide, Slit, Zoom, Hinge, Jack-in-the-Box, Roll

[https://pub.dev/packages/animate\_do](https://pub.dev/packages/animate_do)

[https://pub.dev/packages/animated\_text\_kit](https://pub.dev/packages/animated_text_kit)

[https://pub.dev/packages/motion\_widget](https://pub.dev/packages/motion_widget)

[https://pub.dev/packages/animations](https://pub.dev/packages/animations)

## Properties

**Name**: \[textField\] The human readable way we refer to this "Motion" in the dictionary

**Type**: \[selectList\(\)\] The categories we set up for the different types of motions. The initial thought is that we will have at least two types: Productive which demo a sense of efficiency and responsiveness in the app, and Expressive which are more enthusiastic and highly visible to signify an important moment.

**Resource**: \[searchList\(motion.Type\)\] Every motion will have a source file that it references to provide the code for the activity this is the location of that snippet of code needed to preform the desired action

**Metaphor**: \[textField\] Every motion response acts as a metaphor for something. Some responses can carry multiple metaphors \(i.e. "success" and "win" for a positive result\) This allows us to reuse these feedback metaphors as a design token which is referenced throughout our components while all referencing the same file.

**Token**: \[textField\] The short-code we use to refer to this metaphor \(i.e.. \#moWin, \#moError, \#moWarn, etc.\)

