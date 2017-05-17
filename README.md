[![Build Status](https://travis-ci.org/andela-mmakinde/checkPoint1.svg?branch=master)](https://travis-ci.org/andela-mmakinde/checkPoint1) [![Coverage Status](https://coveralls.io/repos/github/andela-mmakinde/checkPoint1/badge.svg?branch=master)](https://coveralls.io/github/andela-mmakinde/checkPoint1?branch=master) [![Code Climate](https://codeclimate.com/github/andela-mmakinde/checkPoint1/badges/gpa.svg)](https://codeclimate.com/github/andela-mmakinde/checkPoint1)

# newsApp
A news feed application that delivers news headlines ranging from sports, to politics, business, entertainment, etc. from sources all around the world. 

### Introduction

newsApp allows you to view news headlines from different
news sources globally(e.g Al Jazeera,BuzzFeed, CNN, Bild, Ars Technica, BBC Sport, Mirror, MTV News, TechCrunch e.t.c).
With newsApp, Users can access the page to view the news sources avalaible to view articles from without logging in and can also search through a list of the news sources. But they will be required to login with Google+ in order to view news articles, sort
headlines for these news sources based on options(Top, Latest, Popular).

### Development

newsApp is built using ReactJS, React-router for routing and it
consumes a public api from the endpoints on
newsapi.org. The tests have been written using Mocha, Chai expect syntax and
Enzyme.


### Features

* Google+ sign-in
* List of news sites available.
* View news for preferred source.
* Sort through news headlines(Top, Latest, Popular).

### User Guide

* Visit  https://naijnews.herokuapp.com to use this app.

### How To Contribute

* Clone this repository.
* Navigate to the project root folder on your terminal.
* Install the dependencies using npm install.
* Run webpack to compile the files and create a bundle file (scripts.min.js).
* Run npm run dev to start the application.
* To test: run npm test.
* Fork this repo to your own repository.
* Make all changes in a new branch.
* Create a pull request to the develop branch of this repo stating the features you implemented in your PR.

### Core Technologies

* React: For the User Interface (https://facebook.github.io/react/)
* React-Router: For routing in the app
 (https://www.npmjs.com/package/react-router)
* ReactDom: This package serves as the entry point of the DOM-related rendering
 paths(https://www.npmjs.com/package/react-dom)
* Node.js (npm): NPM was used to install all node packages
 (https://nodejs.org/en/)
* ES6: Used in React classes
* Webpack: webpack bundles my modules into one static asset
 (https://webpack.github.io/)
* Babel: For transpiling ES6 syntax to ES5(https://babeljs.io/)
* Mocha: For writing tests(https://mochajs.org/)
* Chai: Expect statements in my test suites(http://chaijs.com/)
* Enzyme: Used with Mocha and chai to test React components
 (https://github.com/airbnb/enzyme)
* axios: http client library for making api calls
(https://www.npmjs.com/package/axios)

### Resources
* News api: provides endpoints for news sources and headlines (newsapi.org)

# Limitations
* Users cannot bookmark/favourite headlines currently
* Users cannot view Articles within the application.


