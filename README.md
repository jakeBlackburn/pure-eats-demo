# pure-eats-demo

This is a single page Vue.js app made for a restaurant in my hometown. It uses a third party service called GloriaFood to make online ordering and payment easy to configure. A live demo is viewable @ - https://pure-eats-demo.herokuapp.com
the page includes an image gallery, information about the restaurant, and a map made with the google maps API. It includes an HTML snippet to link the GloriaFood API, retrieving the menu options of the restaurant profile. Because this is just a demo, the buttons lead to "demo restaurant" with limited options, but changing things such as adding a new item to the menu is as simple as logging in to the GloriaFood dashboard and updating the details/configuration.

## Project setup
run "npm install" to install all dependencies, then run "npm run build" to bundle the app into the /dist folder. 
"npm run serve" will serve the app using the vue live reload server, which will automatically update any time changes are saved. you do not have to re-build the app when using the live server.

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
