# Assignment 4A
Starter code for DGL 203 assignment 6

## Objective
Our goal for this assignment is to take code from Assignment 2A-2 and to *Sassify* it. In other words, we're going to take what was a fairly complete CSS implementation and use Sass in selected areas to simplify and clarify the code. Note that the entire CSS code base need not be fully Sassified.

## Requirements
Use the starter code provided and add modify the CSS as necessary. You may modify the HTML (for example to reorder the images, or add classes, etc.), though you should not need to add any additional HTML elements. 
### Sass properties
* Your final submission must include the following Sass features:
    - Sass variables for all theme colours (variables for white and black are not necessary), theme fonts, and for any common size values;
    - Use nested Sass anywhere it is possible and improves the readability of the code;
    - Use a mixin to handle the `.site-nav > li > a` and `.cta-button` rulesets.
    - Use an `@if` and `@else` statement to make a change to at least one element (of your choice) based on a condition of your choice.
### Design
* As always, feel free to improve upon the presented design.
* As an added bonus this week I'll also be looking at extended uses of Sass for this category: If you make use of one of Sass looping tools (either `@for`, `@each`, or `@while`) in a meaningful way then this will count towards your design approach. 
### General CSS requirements
* Keep inter-rule and intra-rule organization in mind.
* Don't overload individual rulesets - keep your CSS code concise and precise.
* Consider naming conventions for classes and IDs carefully 
* Keep selector specificity as low as possible! 