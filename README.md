## Project Overview

Feed Reader Testing is 4th project of Front-End Web Developer Nanodegree Program. Udacity provided a web-based application that reads RSS feeds. Our goal is to write a number of tests against this given app and check if the application works properly.
To achive that we will use Jasmine which is an open source testing framework for JavaScript.


## Test functionality

Test covers following areas of concerns

RSS Feeds
- are defined
- url is defined
- name is defined

_This part check if our RSS Feeds - allFeeds variable - is defined and is not empty. Then loops through each feed in the allFeeds object and ensures that properties of our object (URL and name) are defined a not empty._


The menu
- menu is hidden
- menu is displayed or hidden when clicked

_This test check if menu is hidden by default and goes on and off upon every click on its icon._

Initial Entries
- at least one feed is loaded

_This test ensures when the loadFeed function is called and complete, there is at least a single .entry element within the .feed container. The loadFeed() function is asynchronous. That is why this test will require the use of Jasmine's beforeEach and asynchronous done() function._

News Feed Selection
- content changes after loading new feeds

_Here we test if the content actually changes after a new feed is loaded by the loadFeed function._

## How to start

To start the application load the index.html file.
To run a test click on any item of the Jasmine's Spec List

## Resources

* Jasmine documentation http://jasmine.github.io/
* Udacity JS Testinh Course https://www.udacity.com/course/javascript-testing--ud549
