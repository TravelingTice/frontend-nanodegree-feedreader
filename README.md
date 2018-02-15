# RSS Feed Reader, Fully Tested!

## Overview

This is a web-based application that reads RSS feeds.
The application itself is built by someone else, they also included [Jasmine](http://jasmine.github.io/) and added the first test suite. Then they abandoned the project and I finished the testing, of which the results are shown at the bottom of the application.

## How to run

Open index.html in your favorite browser and in there you can find the RSS Feed of 5 blogs. To switch between the 5, just open the menu by clicking on the hamburger icon in the top-left corner.

## How to customize

1. Open js/app.js
2. In the `AllFeeds` Array, add an anonymous object containing two properties: `name` and `url`
3. The value of `name` should be the name of your desired RSS Feed
4. The value of `url` should be the url of the RSS Feed of your desired blog.
5. Save the file and run index.html. If your blog is not the first one in the array, you'll have to choose it in the menu (by default index 0 of the array is displayed).

## Dependencies

- The RSS Feeds are fetched using AJAX and Javascript.
- The application makes use of [jQuery](http://ajax.googleapis.com/ajax/libs/jquery/2.1.1/jquery.min.js) and [Jasmine-JQuery](https://raw.githubusercontent.com/velesin/jasmine-jquery/master/lib/jasmine-jquery.js).
- The application is tested using Jasmine 3.0.0.
- The tests are written in jasmine/spec/feedreader.js

## Bugs

I had a little trouble running the tests just from my explorer, but by testing it in a server it worked.
