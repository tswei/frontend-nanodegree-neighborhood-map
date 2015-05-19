# Neighborhood Map P5 Front-end Nanodegree

## Instructions to Run

To install dependencies, [Node.js](https://docs.npmjs.com/getting-started/installing-node), [Bower](http://bower.io/#install-bower), and [Python](https://www.python.org/downloads/) are required. Instructions on installing these can be found by following the links.

To install the dependencies, run:
`pip install -t lib -r requirements.txt`.
`npm install bower`.
`bower install`.

A sample configuration file template is supplied. This must be modified to include credentials obtained from the following APIs: [Yelp](https://www.yelp.com/developers/documentation/v2/search_api). The configuration file must be renamed to config.json to properly work with app.py.

You may also need to download and install the Google AppEngine SDK. Once installed you can intialize the server by running the dev_appserver.exe in the directory containing the root folder of this project. The google file is usually located at "C:/Program Files/Google/Cloud SDK/google-cloud-sdk/platform/google_appengine/dev_appserver.py".

The server should be initialized at port 8080

## Project Overview

You will develop a single page application featuring a map of your neighborhood or a neighborhood you would like to visit. You will then add additional functionality to this map including highlighted locations, third-party data about those locations and various ways to browse the content.

## Why this Project?

The neighborhood tour application is complex enough and incorporates a variety of data points that it can easily become unwieldy to manage. There are a number of frameworks, libraries and APIs available to make this process more manageable and many employers are looking for specific skills in using these packages.

## What will I Learn?

You will learn how design patterns assist in developing a manageable codebase. You’ll then explore how frameworks can decrease the time required developing an application and provide a number of utilities for you to use. Finally, you’ll implement third-party APIs that provide valuable data sets that can improve the quality of your application.

## How does this help my Career?

Interacting with API servers is the primary function of Front-End Web Developers
Use of third-party libraries and APIs is a standard and acceptable practice that is encouraged

## How will I complete this Project?

1. Review our course JavaScript Design Patterns.
2. Download the Knockout framework.
3. Write code required to add a full-screen map to your page using the Google Maps API.
4. Write code required to add map markers identifying a number of locations your are interested in within this neighborhood.
5. Implement the search bar functionality.
6. Implement a list view of the identified locations.
7. Add additional functionality using third-party APIs when a map marker, search result, or list view entry is clicked (ex. Yelp reviews, Wikipedia, StreetView/Flickr images, etc). If you need a refresher on making AJAX requests to third-party servers, check out our Intro to AJAX course.

## Helpful Resources

### None of these are required, but they may be helpful.

Yelp API
MediaWikiAPI for Wikipedia
Google Maps Street View Service
Google Maps


## Searching and Filtering

We expect your application to provide a search/filter option on the existing map markers that are already displayed. If a list of locations already shows up on a map, we expect your application to offer a search function that filters this existing list. The list view and the markers should update accordingly in real-time. Simply providing a search function through a third-party API is not enough to meet specifications.

### What does "errors are handled gracefully" mean?

In case of error (e.g. in a situation where a third party api does not return the expected result) we expect your webpage to do one of the following:

A message shows up to notify the user that the data can't be loaded, OR There are no negative repercussions to the UI.

Note: Please note that we expect students to handle errors if the browser has trouble initially reaching the 3rd-party site as well. For example, imagine a user is using your neighborhood map, but her firewall prevents her from accessing the Instagram servers.

Here is a reference article on how to block websites with the hosts file:

http://www.digitaltrends.com/computing/how-to-block-a-website/

### Why?

It is important to handle errors to give users a consistent and good experience with the webpage. Read this blogpost to learn more .

### How?

Some JavaScript libraries provide special methods to handle errors. For example: refer to .fail() method discussed here if you use jQuery's ajax() method. We strongly encourage you to explore ways to handle errors in the library you are using to make API calls.