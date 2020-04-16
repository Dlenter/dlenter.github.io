# Project 0
# [Click to see!](https://dlenter.github.io/)

## Web Programming with Python and JavaScript

##### Alright, now it’s time to make your website your own. Design a personal webpage about yourself, one of your interests, or any other topic of your choice. The subject matter, look and feel, and design of the site are entirely up to you, subject to the following requirements:

1. Your website must contain at least four different .html pages, and it should be possible to get from any page on your website to any other page by following one or more hyperlinks.
1. Your website must include at least one list (ordered or unordered), at least one table, and at least one image.
1. Your website must have at least one stylesheet file.
1. Your stylesheet(s) must use at least five different CSS properties, and at least five different types of CSS selectors. You must use the #id selector at least once, and the .class selector at least once.
1. Your stylesheet(s) must include at least one mobile-responsive @media query, such that something about the styling changes for smaller screens.
1. You must use Bootstrap 4 on your website, taking advantage of at least one Bootstrap component, and using at least two Bootstrap columns for layout purposes using Bootstrap’s grid model.
1. Your stylesheets must use at least one SCSS variable, at least one example of SCSS nesting, and at least one use of SCSS inheritance.
1. In README.md, include a short writeup describing your project, what’s contained in each file, and (optionally) any other additional information the staff should know about your project.


## Contents of this project:

##### The 4 pages:
* Home page - index.html
    * Simple font logo designed and created in Photoshop
    * Link bar with links to other pages as well as favicons that link to github/instagram
* About me - about.html
    * A little bit about me/my family
    * Hobbies/adhd paragraph
    * Music favorite artists image table, all resized in photoshop
    * Music tastes paragraph
* Blog page - blog.html
    * Column for blog post dates, column for blog post itself
    * `<p>` tags formatted to have indent
* Photography gallery - gallery.html
    * 12 images, fit into individual columns, in one row so that bootstrap would wrap them automagically
    * Clicking an image opens up the original in a new tab

##### General styling:
* Each page that is not the homepage has a top bar -- basically the page's title -- underneath the top navigational bar
* Each page has a top navigational bar. Links are styled to change color upon highlighting. DJL is also clickable, and leads to the home page.
* All of the layouts were built entirely with bootstrap so that they are entirely responsible. Additionally, I added some media queries to change margins on certain objects depending on the width of the page, eg. the home page has a top margin that will disappear once the width of the page is that of a cell phone screen's width.

##### Additional notes:
* SASS's convenience tools were used quite a bit. I created a palette of colors at the top of my .scss file so that each color could be quickly and easily referred to. I also used nesting in my SASS stylesheets wherever necessary. The file watching functionality couldn't have been more easy to use.
