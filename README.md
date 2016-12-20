## Website Performance Optimization portfolio project



### Getting started

 - Clone the github repository or download the zip File to local desktop
 - After extracting the file click open index.html

#### Part 1: Optimize PageSpeed Insights score for index.html
  - Google fonts removed
  - JavaScript
    - link was placed above end body tag
    - async attribute was added
  - Css minified and inlined
  - Image optimisation
    - Image resized
    - Image compressed

Good PageSpeed Insights score achieved

***
#### Part 2:  Optimize Frames per Second in pizza.html

 - Forced Synchronous Layout(FSL)
  - Event Scroll FSL removed
    - Most calculations done outside for-loop and only once , preventing long delays in recalculation
  - pizza size slider FSL removed
    -  dx variable removed , no more need of layout calculation
    - 3 cases with different pizza width created and pizza size changed accordingly
  -incresed FPS     
 - 3D Transform used
  - transform : translate(0) used on mover class-Name
  - To make sliding pizza background to another lawyer
  - prevents painting of whole page again and again
  - increases FPS
 - Reduced the number of background Animating Pizzas(200 to 40)
 
***

#### Part 3: Hosting the site

    Github pages used

***
### Customization with Bootstrap
The portfolio was built on Twitter's <a href="http://getbootstrap.com/">Bootstrap</a> framework. All custom styles are in `dist/css/portfolio.css` in the portfolio repo.

* <a href="http://getbootstrap.com/css/">Bootstrap's CSS Classes</a>
* <a href="http://getbootstrap.com/components/">Bootstrap's Components</a>
