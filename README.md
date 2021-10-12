# vue3-sfc-loader-with-vuex
A proof of concept to demonstrate loading Vue SFCs on the web using Vuex with state and implementing persistence with state via the browser's localStorage.

## How to use
Install the `npm` package `http-server` or use `npx` to run it from the command line. Run `http-server` in the root directory of this repository. Visit the website in your browser. You should be able to click the links to travel back and forth between HTML files and the count should remain the same between pages. The count is a variable within the Vuex store and the app is re-mounted every time the page changes, yet the store variable remains.

> npx http-server -p 8080

Then visit http://127.0.0.1:8080/
