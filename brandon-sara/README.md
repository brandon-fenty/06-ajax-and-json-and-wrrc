# Project Name

**Author**: Sara Bahrini & Brandon Fenty
**Version**: 1.0.0 (increment the patch/fix version number up if you make more commits past your first submission)

## Overview
<!-- Provide a high level overview of what this application is and why you are building it, beyond the fact that it's an assignment for a Code Fellows 301 class. (i.e. What's your problem domain?) -->

We are building this page to function as a technology blog with several contributing authors. It will have to ability to generate new articles and send them to a server for storage as well as pull article objects from the same server and render them to the page.

## Getting Started
<!-- What are the steps that a user must take in order to build this app on their own machine and get it running? -->
To build this app on your own page, you would first start by creating an index page and building the basic structure of the page. While building the structure, keep in mind that all articles will be taken from an articles JSON object and ran through a template before rendering to the page. After you have created the structure, add a JS file that will request the raw data object (our articles) through AJAX, stringify them to JSON, store the stringified object to local storage, retrieve the objects and finally, render them to the page.

## Architecture
<!-- Provide a detailed description of the application design. What technologies (languages, libraries, etc) you're using, and any other relevant design information. -->

The application is designed using JQuery for DOM manipulation, locating objects, and storing them. In order to render the articles to the page, we use Handlebars.js to create a template that grabs individual key/value pairs from the raw data object, compiles them, and passes the template along to a protoyping function that renders the articles to the page.

## Change Log
<!-- Use this are to document the iterative changes made to your application as each feature is successfully implemented. Use time stamps. Here's an examples:

01-01-2001 4:59pm - Application now has a fully-functional express server, with GET and POST routes for the book resource.

## Credits and Collaborations
<!-- Give credit (and a link) to other people or resources that helped you build this application. -->
Handlebars.js - https://handlebarsjs.com/
JQuery - https://jquery.com/