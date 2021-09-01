# maps

# Testing
I am sorry but I have never had the opportunity to perform front end testing with Mocha or cucumber.

# Media queries
I have set the widths to be 600px (tested on iPhone X, Google Pixel 4 & Galaxy S9 Plus) and 768px for iPad (all four tested using the Blisk browser and the provided device set), this is the point at which the tabs gracefully gain 100% width and render each one in line.

I have tested this at 1280px and 400% zoom, which is in accordance with WCAG advice, and the appropriate media query is used.

Without guidance I have made the tab titles remain together at the top, but it could be required that the content stays with each content title; this could be achieved similar to an accordion component.

# No JavaScript
I have tested my solution with JS switched off and as can be expected the keyboard tabbing and mouse click events are not honoured.  However, I have tested using styled input radio buttons and with JS switched ON & the inputs styled properly, it's impossible to use the cursor keys to move to the next tab.

However, it was possible to use the cursor keys to move to the next radio button if they're not styled and remain as traditional radio buttons, which is not what was required.

At least with the keyboard tabbing working, in the current solution, it's possible for a user with limited mobility to still select a tab.