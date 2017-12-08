# CSS Week3 2-day SASS Project - Extended

### A continuation of the previous two day SASS project where I will be using one of the designs that we created on Wednesday.

#### By _Nathan Barrett_

## Description

A simple, and responsive design an online magazine by dogs for dogs.

##Project Thoughts

As frustrating as the two project was, looking back, I think I learned a lot about how to approach building sites for the future. It was nice to take a critical look about how we were going each part of our site moving forward. Mainly our frustration stemmed from not knowing exactly what type of wire-framing we were doing - making a template or just a sketch of what we wanted from our website. What did work was making everything one step at a time and looking at building our site from the outside-in and not trying to move forward with an idea before we finished up the previous one.   


## Table of Sass Elements used on Wednesday Project
| Term | Description | Implementation |
| :-------------     | :------------- | :------------- |
| **SASS partials** | Partials are .scss files containing code snippets that will be compiled into final CSS code. Uses the 7-1 file structure -- 7 folders with partials, 1 main.scss input file | Examples of how we're using partials include a folder that contains layout items specifically, nav, hero, intro, etc. Each file has element-specific styling |
| **grid system** | We will define column units much like Bootstrap (12 units per 1 row) and use SASS to calculate the space that each column takes up in that row. | Using a @for loop we will obtain SASS-calculated distribution of columns that are divisible by 12. This grid will afford uniformity and flexibility when used with breakpoints |
| **SASS @extend** | @extend is a SASS tool that allows you to share sets of CSS properties from one selector to another | We will use this for a clearfix on parent containers in our document; we will also use this to design various-sized cards and buttons |
| **SASS @mixin** | @mixin is a directive which allows you to reuse css rules through your site.| We will use @mixins for border radius, media queries and our responsive grid system to keep our code DRY. For example @mixin border-radius ($radius) {border-radius: $radius} (after you create this mixin you can you use it as a css declaration with @include border-radius(5px))|
|**SASS variables**| variables are a way to store information that you want to reuse throughout your stylesheet | We are going to use to hold many different values in our style sheet. For example: $primarycolor, $textcolor, $grid-columns: 12, $breakpoint-large: : "only screen and (min-width: 1000px)". |
| **SASS operators** | Operators allow us to do math in CSS. | We are using operators in our responsive grid (i.e., 100% / $grid-columns * index) |
| **Nesting** | SASS nesting places additional child selectors within parent selectors; it is a good way to organize CSS. | We are using nested selectors to style our nav |
| **@content** | @content is a sass directive that allows you to pass content block into the mixin. @content is equal to whatever you pass into the mixin inside of the curly braces | We are going to use the @content directive when we use the media query mixin to make elements responsive |
| **SASS loops** | @each is a control directive in the format of: @each $var in <list>. When processed, the parameter is applied to each item in the list. | We will be using @each loop  with a list of our color variables to apply styles to classes we create using the loop. |
| ** color functions ** | Built in SASS functions that allow color changes to be more fluid, easy, and complementary to the colors you're using; actions include darken and lighten, saturate and desaturate | We will use color functions to change the color in our nav list when hovering; we want that color to be a lighter version of the original color instead of a default color |

## How I will change my approach

I learned a lot from working with Cat and how best to approach planning a site and using SASS. I really love how much work the SASS variables, loops and mixins do for you in both making your code DRY but also creating classes for you. I will try my best to keep my CSS rules separated using partials and to use the different SASS elements to make my workflow more efficient. I feel like, especially with SASS - its important to pay attention how you applying styles and committing when you finish (or a significant part) of a section you are styling. 

## Setup/Installation Requirements

* access computer with internet connection and a browser
* go to github.com and search "nathan-barrett"
* browse nathan-barrett's repositories to find 'css-week3' repository
* click on 'css-week3' repository and copy URL link that directs to this specific repository
* access computer terminal and make sure you are at the top directory
* in terminal, after $ prompt, type in: git clone {-don't type the following, just do the following: paste URL into terminal after git clone-} then hit enter
* complete repository should be available at top directory (although desktop is suggested)
* browse folder of repository to find 'index.html'; drag file directly into browser OR in browser click file open and access 'index.html'


* or access gh-pages assigned to this project:
* nathan-barrett.github.io/css-week3

## Support and Contact Details
* For any questions please reach out. Here are my GitHub account details:

  * [Nathan Barrett](https://github.com/nathan-barrett) - thatcat13@gmail.com


## Technologies Used
* CSS
* HTML
* Sass 3.5.2



### License
* Font Awesome: License: SIL OFL 1.1
* Pixabay: CC0 1.0 Universal (CC0 1.0)


Copyright (c) 2017 **Nathan Barrett**
