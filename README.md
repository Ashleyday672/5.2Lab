# Lab 5.2

## Overview

In this project we were given a fake webpage to make more accessible by changing certain accessability aspects of it.

To view this website, open an ide of your choice that supports live preview and run live preview. 

 ## Accessibility Lab Answers

The starting color contrast of (#0a0404) on the background (#ad8e58) gives a contrast ratio of around 2.87:1, which fails the test.

The new text color is #0a0404 on a lighter background color #f0ceaa, giving a contrast ratio of 4.58:1, which passed the test.


When navigating the site using only the keyboard, I noticed that the navigation and interactive elements were difficult to focus on. I replaced the <div class="nav"></div> with a <nav> element for the navigation menu. This made the page more accessible to both screen readers and keyboard navigation.
I also improved keyboard focusability on elements by adding aria-expanded and aria-controls attributes. 

The images initially lacked descriptive alt attributes. I added appropriate alt attributes to both images.


I added a transcript for the audio clip so users can expand it and read the content.

To add a label to the search input field without affecting the visual design, I used a visually hidden label.

The "Show/Hide" comment button was not initially keyboard-accessible. I made it accessible by ensuring the button can be focused using the Tab key and activated with the Enter key.


I added a caption element and defined appropriate attributes for the table headers.


Other ideas:

Adding a "Skip to Content" link at the top of the page would allow keyboard users to bypass navigation and jump directly to the main content.

Adding a visible focus indicator for interactive elements.

## Sources and Credits


- https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Attributes/aria-expanded
