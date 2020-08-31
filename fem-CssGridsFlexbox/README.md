README

These are my notes for Jen Kramer's FrontEndMasters course on CSS Grids and Flexbox for Responsive Web Design

https://github.com/jen4web/fem-layout/
https://static.frontendmasters.com/assets/courses/2018-01-30-css-grids-flexbox/transcripts.zip

Where I got to last: https://frontendmasters.com/courses/css-grids-flexbox/float-exercise-setup/

Responsive Design
- Defined by 3 characteristics
    1. flexible grid-based layout
    2. media queries (CSS3)
    3. images that resize

Floats
- One of the original hacks for layouts. 
- Was intended to float an image over a webpage kind of like print (was never meant for responsive)
- Major disadvantage: equal column heights
- Attribute selectors seem cool!!
    - eg. `[class*="col-"] {}` selects every element with class that starts with 'col-' (.col-1, .col-hello both affected)
