Website Performance Optimization portfolio project Version 1.1 5/10/2017
===============================

it's Project Four in Frond-End Developer Nanodegree program from Udacity to optimize this online portfolio for speed!.

You can visit [Udacity]( https://www.udacity.com/) site and register in any courses that you love to join, Trust me you will have lot of learning and fun at udacity.

===============================

Instructions :

1.  visit my github [here.](https://github.com/nouraal/frontend-nanodegree-mobile-portfolio-master)
2. download ZIP file green button on the right of the screen,  then extract the zip file to your computer.
3. to open file  Double-click on " index.html " to open the portfolio in your browser.

* Or you can opne the file online from [here.](https://nouraal.github.io/frontend-nanodegree-mobile-portfolio-master/)

===============================

### Getting started

#### Part 1: Optimize PageSpeed Insights score for index.html

for Optimize PageSpeed i did:
1. asynchronous attribute for all  JavaScript flie.
2. to compression all images and use .WebP to instead of .JPG
3. use media="print" for print.css flie.
4. Move all contents of style.css file inside the index.html file
5. Remove Google Fonts from the file.


######PageSpeed result is:
- for Mobile: 93
- for Desktop: 98

===============================

#### Part 2: Optimize Frames per Second in pizza.html

To optimize views/pizza.html, you will need to modify views/js/main.js until your frames per second rate is 60 fps or higher. You will find instructive comments in main.js. 

* optimize pizza.html:
1. compression pizzeria.jpg image and use .WebP to instead of .JPG
2. compression pizza.png imge to be 13KB instead of 48KB.

* optimize main.js:
1. Reduce the size of the array as much as possible 
2. Replace document.querySelector to document.getElementById
3. Replace document.querySelectorAll to document.getElementsByClassNam

* optimize css:
1. Added (backface-visibility: hidden) to the .mover class, to move each animated pizza to its own composite layer.
===============================