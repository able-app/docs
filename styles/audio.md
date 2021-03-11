# Audio

Sound is used to communicate with the user, provide (emotion identity style) for a brand, and improve the experience through sensory feedback. There are three primary types of sound "audio" communication… interface, musical, and voice.

### Resources

These resources would be stored in the snippets library as pieces of code that can be used across the application and referenced through the token assigned to it in the snippets library.

[https://storage.googleapis.com/material-design/downloads/material_product_sounds.zip](https://storage.googleapis.com/material-design/downloads/material_product_sounds.zip )



### Properties 

**Name**: [textField] The human readable way we refer to this "Sound" in the dictionary 

**Type**: [selectList(Interface, Music, Voice; Interface)] Interface, Music, Voice 

**Family**: [selectList(Assets.Sound)] The sound family that this sound is in. The list of available sound families is pulled from the Assets > Sounds folder. Those sound families that have been uploaded into the system. 

**Resource**: [searchGallary(selectedFamily)] Every sound will have a source file that it references to provide the source file for the sound 

**Metaphor**: [textField] Every sound acts as a metaphor for something. Some sounds can carry multiple metaphors (i.e. "success" and "win" for a positive result) This allows us to reuse these sound metaphors as a design token which is referenced throughout our components while all referencing the same file. 

**Token**: [textField] The short-code we use to refer to this metaphor (i.e.. #audWin, #audAdd, #audWarn, etc.)