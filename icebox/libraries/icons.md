# Icons

Icons that are added to the design system need to be in a SVG \(Scalable Vector Graphic\) format to allow for multiple usecases.

## Families

As with fonts we do the same for icons. There are a number of open source icon sets as well as paid icon sets. Ww encourage the use of these sets which all follow the same look and feel and are used together as a "family" of icons when building a certain look and feel to your app. Here are a few free options.

### **Base Families**

* Material Design \([https://github.com/Templarian/MaterialDesign](https://github.com/Templarian/MaterialDesign)\)
* Material Design Light \([https://github.com/Templarian/MaterialDesignLight](https://github.com/Templarian/MaterialDesignLight)\)
* Google Material Icons \([https://github.com/material-icons/material-icons](https://github.com/material-icons/material-icons)\)
* Unicons \([https://github.com/Iconscout/unicons](https://github.com/Iconscout/unicons)\)
* BoxIcons \([https://github.com/atisawd/boxicons](https://github.com/atisawd/boxicons)\)
* Font Awesome \([https://fontawesome.com/](https://fontawesome.com/)\)
* The Noun Project \([https://thenounproject.com/](https://thenounproject.com/)\)

## Global Families

Remember, these can be used across multiple themes, but not as the themes main icon family.

### **Flags**

We will use an open source repo of SVG flags to represent countries. [https://github.com/hjnilsson/country-flags](https://github.com/hjnilsson/country-flags)

To keep things organized we'll structure the design tokens for these as, token type "icn", the set name of "Flag" + 2-letter country code. Each file is named as that 2-letter country code as a file name. So for example the United States flag is us.svg and the design token is \#icnFlagUS.

| **Name** | **Asset** | **Token** |
| :--- | :--- | :--- |
| US Flag | country-flags/svg/us.svg | \#icnFlagUS |

### **Credit Cards**

The Credit Card SVG's are a part of this GitHub Repo, where you can get them all.

[https://github.com/aaronfagan/svg-credit-card-payment-icons/](https://github.com/aaronfagan/svg-credit-card-payment-icons/)

Here we structure the design tokens as, token type "icn", set name "Cc", brand "Amex" with a resulting design token of \#icnCcAmex

### **Emoji**

[https://github.com/googlefonts/noto-emoji](https://github.com/googlefonts/noto-emoji)

### **Brands**

[https://github.com/gilbarbara/logos](https://github.com/gilbarbara/logos)

