#Web Performance Project
_This project is part of the Udacity Front-End Developer Nanodegree_

###Getting started
1. Fork & clone repo
2. Install http-server & local tunnel if you don't already have it:
    -npm install http-server -g
    -npm install localtunnel -g
3. In the terminal, navigate to the dist folder of the repo.
4. Start http-server
5. Open a new tab in the terminal and run localtunnel
    -lt --port 8080
6. Use the url localtunnel provides to test performance on PageSpeed Insights

###Optimizations

#### Page Loading
1. Remove unused styles from CSS
2. Minify HTML, CSS, JS
2. Inline CSS
3. Async JS
4. Reduce image size
