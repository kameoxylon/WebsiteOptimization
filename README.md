# How to Open/Run
- Download zip and extract.
- Open index.html onto a web browser (Chrome preferred) 

## Project Overview

####Part 1: Optimize PageSpeed Insights score for index.html
- Async perfmatters.js and analytics.js
- Moved both css stylesheets to the end of the html body
- Used WebFont.load to load in the font
- Reduced size of pizzeria.jpg and saved it as pizzeriaReduction.jpg then compressed it and saved as pizzeriaReduction-min.jpg
- Optimized both pizzeriaReduction-min.jpg and profile-pic.jpg

####Part 2: Optimize PageSpeed Insights score and Frames per Second for pizza.html and views/js/main.js
- Added meta name="viewport" to pizza.html
- Minified both style.css and bootstrap.css and included both into pizza.html as an internal source
- Minified main.js and included into pizza.html as an internal source
- Compressed and optimized the size of pizza.jpg and saved it as pizza-min.jpg
- Fixed the jankiness of pizza size slider found in main.js (421)
- Fixed the jankiness of scrolling pizzas found in main.js (489)
- Created new variables and placed them outside of loops to increase performance (429), (464), (534)
- Removed .querySelector and replaced them with .getElementByClassName and .getElementById (408), (428) 
