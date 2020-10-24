# Week 7 HTML/CSS Lab

## Competencies

Below are some of the competencies you will further develop and demonstrate through this assignment:

- Using Gulp to compile SASS and watch for file changes
- Using SASS to make for more mointable and readable CSS
- Using jQuery to load html
- Using Javascript to load html


## Overview


1. Pair Partner One (PP1) updates their local repo with any changes to the [Program Increment 1 HTML/CSS assignment repo](https://gitlab.mccinfo.net/code-school/course-work/pi1-html-css). (_Note: Pair Partner Two [PP2] may do the same, but it's not required for the assignmet._)
1. PP1 updates their local GitHub Pages repos with any remote changes.
1. PP1 copies the directory "wk07-lab-exercise-files" from this week's lab into their GitHub Pages project's `html-css/` folder.
1. PP1 creates a link to `html-css/wk07-lab-exercise-files/tickets.html` on  `html-css/index.html`
1. Install gulp in this project folder (hint: we did this during class)
1. Create a "gulpfile.js" to compile CSS from SCSS files
1. Set up a folder structure for CSS and SCSS files
1. Use `gulp watch` to watch for file changes
1. Use the following SASS abilities to reduce duplication and make your styles more maintainable
    - Create variables for non-keyword styles that are used more than once (colors are the most obvious)
    - Nest the selectors with descendents to reduce duplication
    - Use the "&" in place of the parent selector for classes and ids on the parent selector and pseudo-classes for the parent selector
1. Use your choice of Javascript or jQuery solutions to add reused html content:
    - header
    - navigation
    - speaker list
    - footer


## Requirements

Below are the details of what you must do to perform and submit this assignment:

- All non-keyword reused colors use a SASS variable
- As many repeated selectors as possible are nested
- "&" is used in your nested selectors
- Content reused on multiple pages is broken out into separate html files (header, navigation, speaker list, footer)
- External html is correctly loaded onto the page after the page loads
- The page should look **exactly** the same as it did before you did this refactoring

## Rubric

Below are the primary criteria for how the quality and completeness of this assignment will be assessed:

You will be assessed on completeness and use of best practices for HTML and CSS.
