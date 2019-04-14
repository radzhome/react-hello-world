# react.js hello world
---

Install node and npm - 
https://docs.npmjs.com/downloading-and-installing-node-js-and-npm


1. install deps  
    `npm install .`

1. start develop server
    `npm start`


### What happens when you npm start?
---


1. webpack dev server starts on port 8080 in dev mode (script in package.json)
1. The entry point of main.js is ran, and all imports within it are used to create index.js (output in webpack.config.js)
1. Babel loader is used to convert js/jsx code into something all browsers understand (loaders in webpack.config.js)




### Resources
---

1. https://github.com/buckyroberts/React-Boilerplate
