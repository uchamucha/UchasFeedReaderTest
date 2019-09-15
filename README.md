# Contents

- [About](#About)
- [How to Run](#HowToRun)
- [Tests Performed](#Tests_Performed)

## About

This is an RSS Feed application. A test suite has been implemented using the Jasmine library to ensure proper functioning of the application. This project is part of Udacity's Front End Nanodegree Program.

## How to Run

Download the repository to your local machine and run _index.html_

## Tests Performed

1. Tests whether the `allFeeds` array is defined and not empty
2. Tests whether each object in the `allFeeds` array have a URL property defined and not empty
3. Tests whether each object in the `allFeeds` array have a Name property defined and not empty
4. Tests whether the sliding menu is hidden by defualt unless it is clicked.
5. Tests whether the slides in and out on each successive click of the menu icon.
6. Tests whether the `loadFeed` function upon execution leaves at least a single `.entry` element within the `.feed` container.
7. Tests whether the content actually changes when a new feed is loaded by the `loadFeed` function.