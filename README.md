# Feed Reader Application 

PROJECT DESCRIPTION
--------------------

- The Application is used to fetch data from a remote site using ajax and Api and be shown back to the         screen .
- we have been using five diffrent API's .
- the `App.js` located in the (**./js/app.js**) folder handle the project logic .
- Using `jasmine` testing framework to run the test .
- the `feedreader.js` located in the (**./jasmine/app.js**) holds all the Test cases .

--------------------
## Installing
--------------------

- Needs browser to run the application.
- Can see the output by double clicking on index.html
- index.html can be opened with any browser on any device.
- To edit needs editor like sublime text, notepad++ etc.
- for testing chrome dev tools is preferred.
- testing framework used is `jasmine-2.1.2`

----------------------
## Tests Running 
----------------------
### A) RSS Feeds
- Write a test that loops through each feed in the `allFeeds` object and ensures it has a URL defined and that the URL is not empty.
- Write a test that loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty.
### B) The Menu 
-  Write a test that ensures the menu element is hidden by default. You'll have to analyze the HTML and the CSS to determine how we're performing the hiding/showing of the menu element.
- Write a test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display when clicked and does it hide when clicked again.
### C) Initial Entries
-  Write a test that ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.
- an entry has a link starting with 'http(s)://' .
### D) New Feed Selection
 - Write a test that ensures when a new feed is loaded by the loadFeed function that the content actually     changes. 

********************
 When complete - all of your tests should pass. 
******************
----------------------
## WHAT'S INCLUDED
----------------------

### A) css
	1) style.css
		- css file for index.html where are the magic take place .

### B) Fonts
	- Consists of icons used in the project .

### C) js
	1)app.js
		- contains javascript code that handles page functionality ; 
### D) Jasmine
    1)`lib`
		- contains jasmine main folder files requierd for the application test . 
		
	2)`spec`
		- contains jasmine main test file where all test cases are requierd for the application .

### E) index.html
	- Browser creates DOM tree from this html file.
	- Displays web contents of API's .
    - desplay the  test resluts 
	
### F) readme.txt
	- States Overall description of project

********************************************************************

## Thank you 

#### Created by ` Mohamed Riaad `

*********************************************