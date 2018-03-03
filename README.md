# Joe's Diner Website

## Scenario
Pretend that a friend owns a diner and wants you to update their website. Since this is a favor, you don't want to spend more than a couple hours on it. Your goals are to modernize the markup and styles, both in visual design and technical quality. How you approach this is entirely up to you, keeping in mind Joe will likely ask you to maintain this in the future. Many of Joe's customers use their phones now and there is a center for the blind around the corner that likes to eat there.

## Directions
1. Spend no more than two hours on this exercise. Time management is part of the assessment.
1. Fork this repository and submit your finished work as a pull request.
2. Make any changes to the site you see fit (including layout, design, and underlying code quality) while keeping the content that Joe wrote. Assume the PHP behind the form is functioning.
3. Set up the structure in a way that makes it easier to maintain moving forward. Bring in any additional resources and dependencies if you find that helpful. Explain major design or code decisions and things you'd do if you had more time.


## Design & Code Decisions
1. I reorganized the file structure for the site. I added folders to house images and css files. 
2. I moved all of the css from an internal style sheet to an external stylesheet.
3. I added normalize.css to help with cross-browser consistency.
4. I chose to make a one page site broken into sections: about, menu, and contact. I used an anchor tag navigation structure so that people could either scroll (ideal for mobile) or click on the links to get to the different sections on the page. 
5. I made sure the page was accessible through the use of contrast and the use of alt text for screen readers. 
6. The design utilizes a color scheme of grey, blue, and white. I wanted to keep the design simple and streamlined. The page is built to highlight both the images and the content. 
7. I utilized HTML5 for the site, making sure to uilize HTML5 semantic markup.
8. I also took a mobile first approach, since it was stated that many of the users are on mobile devices. 

## What else I would do with more time
1. I started to work with media queries and flexbox to reorganize the content for desktop, but ran out of time with this. I would continue to adapt the design for desktop and mobile with more time. 
2. I would look at adding a google font, most likely for the name of the restaurant, or determine if there is a logo for the restaurant and incorporate that as the title for the site. 
3. I would consider utilizing bootstrap as a framework to build the site, if I thought that there would be more pages/content added in the future. 
4. I would look at redesigning the menu with more time. Possibly breaking the menu into sections with headings to make it more organized. 