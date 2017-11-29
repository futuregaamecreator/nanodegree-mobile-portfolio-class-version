# nanodegree-mobile-portfolio-class-version
Udacity Class Project

How to run my application
1. Download the zip folder
2. Extract the zip folder
3. Right Click index.html and click open With Chrome(or the browser you like to use)

Changes in index.html
1.Optimized all images through photoshop and pagespeedinsight and uploaded in the correct folders
2.Moved analytics and perfmatters scripts to bottom under the footer
3.Added async tag to analytics and perfmatters scripts
4.added width to pizzeria image
5.Created style tag and added css to help reduce load time to DOM

Changes to views/js/main.js
1. Removed Determine DX
2. Moved switch function to changePizzaSizes function
3. Moved pizza slider functionality to changePizzaSizes instead of changeSliderLabel
4.changed document.querySelector all to document.getElementsByClass name to increase speed
5.Created a new loop which will have the slider create pizzas by percent instead of a number.
6.Broke loops up into 2 loops updatePositions function to reduce work in DOM
7.Moved movingPizzas1 variable out of for loop to reduce work in the for loop
8.Reduced Pizza count to 32 instead of 200

