## Website Performance Optimization portfolio project

The objective for this project was to optimize Cameron Pittman's portfolio page for speed. The strategy was to optimize the critical rendering path, making the page render as quickly as possible, using techniques you've picked up in the Website Performance Optimization.

To get started, click [here](https://witchfather.github.io/Udacity-front-end-Website-optimization/)

### PageSpeed Insight Scores - 
* index.html        95/ 97
* project 2048      93/ 94
* project webperf   94/ 96
* project mobile    95/ 96
* pizza.html        97/ 97


#### Part 1: Optimization made to HTML files
* inlined all CSS except print.css
* compressed all images
* async all JavaScript




#### Part 2: Optimization made to main.js
* Unnecessary JS operations were pulled out of for loops
* scroll events were 'debounced' to decouple the animations and only reflow/repaint when needed.


