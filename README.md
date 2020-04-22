# Scroll-down Christmas Carol
This code is activated when the user scrolls. The number of pixels scrolled is derived using `document.documentElement.scrollTop`.

## Carol
From there, more calculations are made to determine which line of the carol is "sung". Each line is further divided into words so that the words will play out one by one along with the scrolling.

## Caroller
The caroller is rendered using CSS. The "mouth" is a black div whose height and width varies according to randomly generated values as the user scrolls.

***Note:** This will probably not work in Safari due to the `document.documentElement.scrollTop` issue.
