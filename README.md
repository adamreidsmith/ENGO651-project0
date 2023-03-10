# Project 0

ENGO 551 - Adv. Topics on Geospatial Technologies

## Description

This repository composes a simple personal website describing a bit about me and my interests.  It consists of four pages: a home/about page, a page on my sport interests, a photo gallery, and a contact page.  The webpage was created using HTML and CSS, with bootstrap 4 and Sass to extent the functionality and improve the code.

## File descriptions

The files [index.html](./index.html), [sport.html](./sport.html), [photos.html](./photos.html), and [contact.html](./contact.html) contain the HTML code for the home, sport, photo gallery, and contact pages respectively.  Styling for all the pages is included in the SASS file [style.scss](./style.scss), which SASS converts into [style.css](./style.css).  This file is divided into 6 sections: styling which applies to all pages, styling which applies to each of the four pages, and a media query for adjusting the styling on smaller screens.  The [media](./media) directory contains all images and icons that are displayed on the webpage.

## Project requirements

This project satisfies all requirements:
* The website contains four pages, and each page is accessable from each other page via the navigation bar in the top left.
* The [contact.html](./contact.html) page uses an unordered list to display my contact information, a table is used to display recent race results in the [sport.html](./sport.html) page, and several images are dispalyed throughout the site particularly on the [photos.html](./photos.html) page.
* The styling is contained in [style.scss](./style.scss), which is converted into [style.css](./style.css) by Sass.
* Many CSS preoperties and selectors are utilized in [style.scss](./style.scss). Some examples of types of selectors I used are:
    * element1, element2
    * element1 element2
    * .class
    * #id
    * element1 > element2
    * element:hover
* A media query is used such that when the display width reduces below 780 pixels, changes are made to the styling of the navigation bar, the photo carousel, the sport paragraph and results table, and other items.
* A Bootstrap 4 carousel was used to create a photo gallery on the [photos.html](./photos.html) page.  Bootstrap's grid feature was used to position the contents of the [sport.html](./sport.html) page into two columns when the screen is larger than 780 pixels in width.
* Two SASS variables are defined at the top of the [style.scss](./style.scss) file.  SASS inheritance was used to change the background image on the header of each page while keeping the styling consistent.  SASS nesting was used to style the table of race results on the [sport.html](./sport.html) page.