# Project Overview

In this project a web-based application that reads RSS feeds is tested. Several test suites are written using [Jasmine](http://jasmine.github.io/) to test the underlying business logic of the application as well as the event handling and DOM manipulation.


# Test suites in the project

1 Test suite "RSS Feeds"  
1.1 A test that ensures all RSS feeds are defined.  
1.2 A test that ensures all feeds url are defined and not empty.  
1.3 A test that ensures all feeds names are defined and not empty.  
  
2. Test suite "The menu"  
2.1 A test that ensures the menu is hidden by default.  
2.2 A test that ensures the menu changes visibility when the menu icon is clicked.  

3. Test suite "Initial Entries"  
3.1 A test that ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container.  loadFeed() is asynchronous, so this test will require the use of Jasmine's beforeEach and asynchronous done() function.  
  
4. Test suite "New Feed Selection"  
4.1 A test that ensure when a new feed is loaded by the loadFeed function that the content actually changes.


# How to run the project

Open index.html by browser and check the jasmine test results.  

Author: Tina D. Wu  
Date: 09 / 17 / 2015