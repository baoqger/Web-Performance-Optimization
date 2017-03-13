## Website Performance Optimization portfolio project


In this project, the online portfolio was optimized to speed up. In the first part, the critical render path was optimized to get a better Pagespeed Insights score (over 90 on both desktop and mobile platform). And in the second part, javascript was optimized to realize jank free application. 

### How to run
#### Part 1: 
There two folders inside the repo, src is the source code, and dist is for production which has been minified. 

To run the first part, just open the /src/index.html file with web browser.
#### Part 2: 
To run the second part, just open the /src/views/pizza.html with web browser

### The optimizations made in the project

#### Optimization for Part 1: 
* Minify the resource files: CSS,JS and HTML
* Separate the CSS styles into different files based on media query: one for print only, the other is for small mobile screen
* Compress the big image files
* Asynchronous the JS script to avoid render blocking
* Put the rendering block CSS  as inline style.

#### Optimization for Part 2: 
* Fix the re-calculate style and layout issue (which is triggered by JS ) while changing the size of pizza image.
* Fix the re-calculate style and layout issue (which is triggered by JS ) while scrolling.
* Generate less moving pizza element based on the user's screen size dynamically. 


