###Overview

This project was prepared for the Udacity Front-End Developer Nanodegree.

This web app tests whether the web app loads and behaves correctly corresponding to the expectations set up.

The testing is done using Jasmine testing framework.

The web app fetches data from a remote site using Google Feed Reader API and the data is displayed in a browser window.

The testing code is located in the file feedreader.js. 

To run the app open index.html in a browser such as Google Chrome or Mozilla Firefox.

###Tests


The tests include:
*a test that loops through each feed in the allFeeds object and ensures it has a URL and name defined and that the URL and name is not empty.
*a 'Menu' suite that ensures the menu element is hidden by default but toggles visibility when clicked.
*a test suite 'Initial Entries' that ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container.
*a test suite 'New Feed Selection'  ensures when a new feed is loaded by the loadFeed function the content changes.

