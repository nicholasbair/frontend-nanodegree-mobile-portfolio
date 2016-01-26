#Web Performance Project
_This project is part of the Udacity Front-End Developer Nanodegree_

###Getting started
1. Fork & clone repo
2. Install http-server & local tunnel if you don't already have it:
    1. npm install http-server -g
    2. npm install localtunnel -g
3. In the terminal, navigate to the dist folder of the repo.
4. Start http-server
5. Open a new tab in the terminal and run localtunnel
    1. lt --port 8080
6. Use the url localtunnel provides to test performance on PageSpeed Insights

###Optimizations

#### Page Loading - index.html
[x] Remove unused styles from CSS  
[x] Minify HTML, CSS, JS  
[x] Inline CSS  
[x] Async JS  
[x] Reduce image size  

#### Page Scrolling - pizza.html
[x] Minify HTML, CSS, JS  
[x] Reduce image size  
[x] Optimize JS loops
[x] Remove use of getQuerySelector
