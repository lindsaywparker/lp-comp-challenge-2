# Lindsay's Static Comp 2
## Project Overview
This version of Static Comp 2 is built from the mobile size up.  At mobile size, the navigation links are hidden and a three line menu icon ("hamburger") is used.  The specifics of the user login are also hidden so only the icon is displayed.

The media query at 660px shifts the above-mentioned navigation and user login to their full versions.  This width allowed for two cards to display comfortably side-by-side.  From 660px on, the cards are given hard min-width and max-width properties to eliminate excessive distortion on larger screens.

Layout was primarily achieved using `display: flex`, resulting in the need for 'dummy' divs to allow for left-aligned orphans.

The card images are from a Google search of "Famous Paintings."  The color scheme is from Adobe Color, specifically the [Orange Gray Website color theme](https://color.adobe.com/Orange-Gray-Website-color-theme-8432429/edit/?copy=true "Orange Gray Website color theme on Adobe Color").  Icons are from [Flaticon](http://www.flaticon.com/ "Flaticon").


## Images
Original Comp
![alt text](http://frontend.turing.io/assets/images/static-comp-challenge-2.jpg 'Original Comp')

Lindsay's Version
![alt text](/images/lindsays.png 'Lindsay\'s')
