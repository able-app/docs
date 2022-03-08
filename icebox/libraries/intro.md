# Libraries

Libraries are where our assets are held. These are the files that will be referred to in the styles, elements and components. Examples of assets are fonts, iconography sets, and illustrations. These source files are the master files used in the dictionaries of the design system. These files and folders are all stored in a parent folder of "assets", with each "type" having their own folder. The files are then stored in the appropriate folder. Asset libraries can be expanded to house any number of asset types like images, illustrations, video, or audio, haptic files.

## Global Designation

There are asset families that we'll call a "global". These families can be used across multiple themes. These might be for brands, flags, credit cards, emojis etc. that we will want to make available through the assets folder for use within the application.

These global families are also excluded from a list of icon family options when styling the overall look and feel of the application in a theme.

### Properties

**File Name:** How this object is known in the system

**Type:** Font\(fnt\), Iconography\(icn\), Illustration\(ill\)

**Resource:** The actual file or folder that contains the files to be referenced.

**Global:** This family can be used "globally" across multiple themes

**Thumbnail:** The visual to represent this object

**Description:** Context to understand what the object is

**Token:** The shortcode to reference this asset \(i.e. \#astFntLato for our Lato font family\)

## Asset Types

These are the different subcategories of assets. This gives us the ability to keep things neat and tidy and add in the design token to use when referring to assets of this type. The ability to add another grouping \(folder\) to the Assets list. This is a "more" menu option for the Assets List.

### Properties

**Name:** How the asset "Type" will be known in the system \(this is used to name the folder and is added as an option in the "Type" field when adding an asset file.

**Thumbnail:** The visual to represent this object

**Description:** Context to understand what the object is

**Token:** The shortcode to add to the beginning of files of this type \(i.e. "icn" for Icon\)

