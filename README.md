Feed Reader Testing version 2.0 12/07/2015


PROJECT LINK

Check out the project by clicking the following link!

http://pradnya-123.github.io/Feed-Reader-Testing/

PROJECT DESCRIPTION
--------------------
A web-based application that reads RSS feeds is tested with Jasmine for various test cases.

--------------------
Installing
--------------------
- Download the project
- Open index.html with browser (Google chreome, Firefox etc.)
- All the necessary files and libraries are included
- Can check the written tests in jasmine/spec/feedreader.js
- The index.html will display all the tests that pass or fail

--------------------
Tasks accomplished
--------------------

Tests written in feedreader.js to make sure : 

- allFeeds variable has been defined 
	and that it is not
 empty.
- each feed
 in the allFeeds object has a URL defined 
	and is non empty
- each feed
 in the allFeeds object has a name defined
	and is non empty
- menu element is
 hidden by default.
- menu changes
 visibility when the menu icon is clicked.
- loadFeed function is called and completes its work,
	there is at least a single .entry element within
	the .feed container.
- new feed is loaded by the loadFeed function that the
	content actually changes.

-----------------------------
Update In This Version
-----------------------------
- Checked id each feed has a URL defined
- Checked if each feed has name defined
- updated has atleast single entry test.

=============================================================================================================
