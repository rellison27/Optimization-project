## Website Performance Optimization Project

Optimized the critical rendering path and made this page render as quickly as possible while increasing the insights score (above 90) and refactored code to get pizza.html website to run at 60 frames

To get started, check out the repository and inspect the code.

### Getting started
Clone the repository `$ Git clone https://github.com/rellison27/Optimization-project.git` 
 or click the download button.
open
```
index.html
```
from there click on "Cam's Pizzeria"

#### Part 1: Increasing Optimize PageSpeed Insights score for index.html
- Put this on a server to get the insights so I used gitHub pages to get a score
- Inlined CSS
- compressed, localized, and resized photos using GIMP
- used the async attribute on the script tags

#### Part 2: Optimized for a consistent 60 Frames per Second in pizza.html
- fixed some of the forced reflow that was happening when resizing the pizzas
- decreased the number of pizzas in the background andrefactored some of the code involved to get a crisp and smooth scroll
