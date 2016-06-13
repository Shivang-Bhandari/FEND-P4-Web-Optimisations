## Website Performance Optimization portfolio project

View the Project in Working at: [Git Pages](http://shivang-bhandari.github.io/FEND-P4-Web-Optimisations/).

The Key Goal of this Project was to Optimize a Given Website As Much As Possible for Faster Rendering & to Achieve High PageSpeed Score.

#### Part 1: Optimize PageSpeed Insights score for index.html

##### Results achieved:
###### PageSpeed Insights
* Desktop (97/100)
* Mobile (95/100)

##### Optimizations performed:

* Optimized Images
* Removing Render Blocking CSS
* Inline CSS styling in `index.html`

#### Part 2: Optimize Frames per Second in pizza.html

##### Results achieved:
To optimize `views/pizza.html`, I modified `views/js/main.js` until the frames per second rate were 60 fps or higher.

##### Optimizations performed:

* Inline CSS styling in `pizza.html`
* Optimized Images
* Modified CSS `.mover` in `style.css` and `pizza.html` inline CSS to increase the site's performance with hardware accelerated CSS.
* Modifications to the `main.js` code:

1. Modified the `changePizzaSizes` function with a new variable randomPizza, and moved the `dx` and `newwidth` variables outside the for loop with it for a more efficient loop.

2. Modified the Pizza Generator function `document.addEventListener` to be more efficient by reducing the number of pizzas generated to populate the page to the minimum required. Also removed the process of resizing.

3. Added `cachedScrollTop` outside the for loop in `updatePositions`.

#### Tools used
* [Compressor.io](http://compressor.io)
* [Tinypng](http://www.tinypng.com)
* [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/)
