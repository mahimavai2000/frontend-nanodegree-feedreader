Feed Reader testing
===============================
# How to run the project

  **1.** Clone this repo:

```
$ https://github.com/mahimavai2000/frontend-nanodegree-feedreader.git
```
or 
**2.** Download the repository:
Download the repository in your desktop, unzip it and open the "index.html" file in your browser to run this project.

# This project contains 4 test suites and 7 tests.

1. The first test suite "RSS feeds" just contains a related set of tests. 
        * The first test is to make sure that the allFeeds variable has been defined and that it is not empty.
        * The second test is to make sure that allFeeds objects has a URL defined and that the URL is not empty.
        * The third test is to make sure that allFeeds objects has a NAME defined and that the NAME is not empty.

2. The second test suite "The Menu" contains a related set of tests. 
        * The first test is to make sure that does the menu element is hidden by default.
        * The second test is to make sure that does the menu displays when clicked and hidden when clicked it again.

3. The third test suite "Initial Entries" contains one test. 
        * The test is to make sure that ensures there is at least a single .entry element within the .feed container.

4. The fourth test suite "New Feed Selection" contains one test. 
        * The test is to make sure that ensures when a new feed is loaded by the loadFeed function when the content actually changes.