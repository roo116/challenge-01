# Code Refactor Starter Code
https://roo116.github.io/challenge-one/
<img src=./assets/screen-shots/readme.jpg>

## Description

This project was motivated by the desire to complete successfully the 24-week coding bootcamp at UNC; with the goal of learning something new, acquiring some skills, and maybe going back to work. 
 
The purpose of the exercise was to meet the Acceptance Criteria as stated in the course work.   The acceptance criteria and results are listed below. 

## Acceptance Criteria and solutions
1. WHEN I view the source code THEN I find semantic HTML elements
    * added "header" and "nav" elements to replace the "div" elements in the header section.
    * wrapped the hero image in a “section” tag rather than “div”.
    * wrapped the content and benefits sections with the “main” tag.
    * In the content section, replaced elements with “section” and “article” tags as appropriate.  
    * did the same in the benefits section, first wrapping it in the “section” tag.
    * finally I set the footer section with a “footer” tag, replacing the “div” tag.
    * 

2. WHEN I view the structure of the HTML elements THEN I find that the elements follow a logical structure independent of styling and positioning.
    * I changed the order of the benefits section to more closely align with the articles position to the left.  The new order is Cost Management; Brand Awareness; Lead Generation.
    *  

    

    (NOTE: These should probably be further ordered so the page is read from left to right rather than from up to down in Voice Over but I haven't figured that out yet.  What I mean by that is that with Voice Over it would ideally read the "Search Engine Optimization" text and then read the "Cost Management" benefit text.  Currently Voice Over goes down to "Online Reputation Management" next. I will add it to the backlog for consideration in the next sprint. 😉) 

3. WHEN I view the image elements THEN I find accessible alt attributes.
    * Added some descriptions to the alt attributes for the images in the content section.
    * added the alt="" attribute to images in the benefits section, as these looked to be decorative images rather than informational. 
    *

4. WHEN I view the heading attributes THEN they fall in sequential order
    * I left this as it, seemed to meet the criteria without requiring further changes.
    *

5. WHEN I view the title element THEN I find a concise, descriptive title
    * added a more descriptive title than "website".   

## Additional Criteria
6. Application's links all function correctly.
    * added an id attribute to the the article tag for "search-engine-optimization"

7. Application's CSS selectors and properties are consolidated and organized to follow semantic structure.
    * ordered CSS file to mirror the order of the HTML page to the fullest extent possible.  Also consolidate several rules to clean up the CSS and reduce complexity. 

8. Application's CSS file is properly commented.
    * added comments to the CSS file.

Sample views of changes to CSS files
<img src=./assets/screen-shots/vscode-img-1.jpg>
<img src=./assets/screen-shots/vscode-img-2.jpg>


## Credits
The code for this activity was sourced from https://github.com/coding-boot-camp/urban-octo-telegram.  All the coding was done by me without any collaboration from others.  However this activity was discussed with fellow classmates, at some of the study groups as well as during office hours on Saturday.  So I acknowledge the insights that these groups and people provided, and I am imminently grateful to all.  
 
## License

This is not a software project, rather it's a class activity.  This repo is available to all admins, educators and classmates associated with the UNC Coding Bootcamp.  

## Tests

Testing was performed using 
* personal judgement
* The Accessibility tools from Chrome and Firefox
* Voice Over from Apple, Inc. 

## Lessons Learned
* spelling matters
* articles about semantics were very useful.  In particular:<br />
<a href="https://www.w3.org/WAI/tutorials/images/">Images Tutorial | Web Accessibility from W3</a>
<br />
<a href="https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Cross_browser_testing/Accessibility#screenreaders">Screen Readers article from MDN</a>