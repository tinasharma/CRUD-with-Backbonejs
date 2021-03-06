[![Build Status](https://travis-ci.org/tinasharma/CRUD-with-Backbonejs.svg?branch=master)](https://travis-ci.org/tinasharma/CRUD-with-Backbonejs)

### Run the app
In order to run the app:
1. Clone this repo
2. Run npm install
3. Connect to local mongodb
3. Run node server.js

#### What we've made
We built very simple app with Backbone.js (which has not much styling right now) that allows you to create a list of restaurants which you like or dislike. Our app corresponds with Express routes and MondoDb as well. ( We like the feature of sending request to a server in Backbone.js because all you need is to specify correct url in backbone collection. It saves a time and makes the code more readable.)
The client side files are placed in app directory.

#Angular.js vs Backbone.js

### General description
AngularJS is a JavaScript framework. AngularJS lets you extend HTML vocabulary for your application. It is a toolset for building the framework most suited to your application development.
AngularJS basics are Controllers (sharing data between Controllers), Scope (defining a method on the scope), Filtering data (filters), Directives.

Backbone is a JavaScript library. It has underscrore.js as a hard dependency and jQuery as a soft dependency. Backbone.js adds structure to your client-side code. It makes it easy to manage and decouple concerns in your application. Backbone basics are models, views, collections, events and routers.

### Advantages
Backbone is a widget builder that just builds blocks of HTML with JavaScript tied to them, its all about render functions.
Angular is shorter.
Angular is live templating engine where you simply put bindings on dom elements and have data come back to you in a really easy accessible manner.

### Disadvantages
Directives are Angular's core feature, but difficult to write.
Most people don't actually use the built-in Router in Angular.

BackboneJS needs more lines of code than AngularJS.
Productivity is an issue as Backbone is more like a library, which means it doesn't have much opinion of its own, which means it doesn't write as much code for you. Memory leaking is a big con of Backbone. If you're new to Backbone you're more likely to have leaking memory when writing applications.
