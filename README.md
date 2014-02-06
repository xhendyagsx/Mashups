Mashups: Creating with Web APIs
===============================

NYU ITP Spring 2014  
Class: Thursdays 6:30 - 9pm  
Instructor: Craig Protzel  
Email: craig.protzel@nyu.edu  
Office Hours: [Thursdays 10:30am - 2:30pm](https://www.google.com/calendar/selfsched?sstoken=UUdZSW52V1dpZUEwfGRlZmF1bHR8NGY4NmMwMTJiMWVkZGE0YjJkNjBlODM0ZmM1NTJkNjc)

[Class Email List](https://groups.google.com/forum/#!forum/itp-mashups)  
[Class Blog List](https://docs.google.com/spreadsheet/ccc?key=0AhUAnC0yr2QRdFp6alNMeVJleTZERnlYX2VDTGVjVkE&usp=sharing)  
[Office Hours Sign-Ups](https://www.google.com/calendar/selfsched?sstoken=UUdZSW52V1dpZUEwfGRlZmF1bHR8NGY4NmMwMTJiMWVkZGE0YjJkNjBlODM0ZmM1NTJkNjc)

Course Description
------------------

Much data and many services are now accessible through public APIs - Application Programming Interfaces - from sites such as YouTube, Google Maps, Twitter, and Xively. But how can we access these datasets and services? How can we transfer, store, initialize, and display this data on our own pages? And how might we use the data to create unique and creative web experiences of our own? 

This class is about building interactive single-page web applications that leverage public data from a range of existing web services. The overall goal of the class will be for each student to have 3 functional well-designed single-page web applications by end of semester. Much of class time will be spent reviewing and writing code, mostly Javascript, for front-end (in-browser) web development. We will use a number of frameworks, including JQuery, Underscore, PaperJs, and D3. Where backend work is required, we will use Node-Express. Students should have some programming experience (ICM) as well as a basic understanding of web development (Comm Lab Web). Experience with Javascript is a plus.


Course Goals
------------

* Develop an understanding of front-end web development and the roles of client-side technologies, specifically HTML, CSS, Javascript, and public web APIs.
* Develop a basic understanding of Javascript and the world of open source (client-side) Javascript libraries
* Learn how to work with a variety of data-serving public web APIs
* Learn how to create web pages in modern browsers that leverage data from web services via public web APIs
* Gain exposure to server-side web development
* Be empowered to produce compelling single page web experiences


Course Requirements
-------------------

* Sign up for class email list - [ITP Mashups Google Group](https://groups.google.com/forum/#!forum/itp-mashups)
* Attend all classes, no more than 2 absences allowed 
* Arrive on time to the start of class or office hour appointment
* Complete all homework exercises and assignments on time
* Post homework exercises and assignments to your blog at least one hour prior to class
* Participate in class through presentations, discussion, questions, and feedback
* Respect fellow students' work, questions, and comments
* Communicate with me if you need to miss class, would like extra help, or schedule additional office hours


Grading
--------

**25%**  Attendance & Class Participation  
**25%**  Homework  
**25%**  Assignments #1 & #2  
**25%**  Final Project  

Syllabus
--------

* **PART I: Weeks 1 - 5 Client-Side Web + API Fundamentals**
* **PART II: Weeks 6 - 9 Client-Side Javascript Frameworks**
* **PART III: Weeks 10 - 14 Server-Side Web + Final Project**

### Week 1 (01/30) - The Web, APIs, & Data

##### Class Intro
* [ITP Mashups - Remixing the Web by Dan Aminzade](http://webremix.org/syllabus.php)
* [ITP Write Once Access Anywhere by Corey Menscher](http://menscher.com/teaching/woaa/)
* [ITP Dynamic Web Development by John Schimmel](http://itpwebclass.herokuapp.com/)
* [StoryScramble](http://storyscramble.com)
* [VimeoLabs](http://vimeolabs.com)

##### Review Course Info & Syllabus

##### Student Intros

##### Lecture: The Web, APIs, & Data

* [Lecture Slides](https://dl.dropboxusercontent.com/u/9648298/Mashups_TheWebAPIsData_LectureSlides.pdf)
* References
  * [What's In An HTTP Request](http://rve.org.uk/dumprequest)
  * [Programmable Web](http://programmableweb.com)
  * [Codecademy API Tutorials](http://www.codecademy.com/tracks/apis)
  * [Temboo](https://www.temboo.com/)
  * [IFTT Recipes](https://ifttt.com/recipes)
  * [HealthCare.gov for Developers](https://www.healthcare.gov/developers/)
  * [OpenWeatherMap API](http://openweathermap.org/API)
  * [HowManyPeopleAreInSpaceRightNow?](http://www.howmanypeopleareinspacerightnow.com/)
  * [Data.Nasa.gov API](http://data.nasa.gov/api-info/)
  * [Open-Notify.org](http://open-notify.org/)
  * [Sunlight Foundation Labs - APIs](http://sunlightfoundation.com/api/)
  * [New Yorker - A Month of CitiBike Data](http://www.newyorker.com/sandbox/business/citi-bike.html)
  
##### Homework
* Sign Up - for class email list [ITP Mashups Google Group](https://groups.google.com/forum/#!forum/itp-mashups)
* Add -  your blog URL to the [class blog list](https://docs.google.com/spreadsheet/ccc?key=0AhUAnC0yr2QRdFp6alNMeVJleTZERnlYX2VDTGVjVkE&usp=sharing)
* Read - [Ch.3 of Interactive Data Viz for the Web by Scott Murray](http://chimera.labs.oreilly.com/books/1230000000345/index.html) up to but not including the section on Javascript
* Download - a text editor
* Donwload - a JSON formatter extension for the browser (I use [JSON Formatter](https://chrome.google.com/webstore/detail/json-formatter/bcjindcccaagfpapjjmafapmmgkkhgoa?hl=en) in Chrome)
* Explore - [ProgrammableWeb](http://programmableweb.com)
* Find, Post, & Describe - a url that returns JSON data from an Open API
* Create & Upload - a single web page that displays (some of) the data you found with some basic css styling. The upload should include a .html file and .css file. Feel free to copy and paste your data into the DOM, no need to programatically connect your page to the data 
* Additional Readings
  * [WebPlatform.org - How Does The Internet Work](http://docs.webplatform.org/wiki/concepts/internet_and_web/how_does_the_internet_work )
  * [Mozilla - Intro to HTML](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/Introduction)
  * [WebPlatform.org - The Basics of HTML](http://docs.webplatform.org/wiki/guides/the_basics_of_html)
  * [WebPlatform.org - Getting Started with CSS](http://docs.webplatform.org/wiki/guides/getting_started_with_css)
  * [Mozilla - Getting Started with CSS Tutorials Parts 1-14](https://developer.mozilla.org/en-US/docs/Web/Guide/CSS/Getting_started)
  * [API 101](http://apievangelist.com/index.html)
  * [The Future of API Design by Daniel Jacobson](http://thenextweb.com/dd/2013/12/17/future-api-design-orchestration-layer)


### Week 2 (02/06) -  Web Dev 101 - HTML, CSS, & Javascript

##### Discussion - Week 1 Homework

##### Mashup of the Day - [Spell with Flickr](http://metaatem.net/words/)

##### Workshop - HTML & CSS
* Setting up your page(s)
* Adding Elements
* Basic Styling
* Pair Programming Exercise
* Review

##### Workshop - Intro to Javascript
* Using the Browser Console
* Playing with Data Types
* The Window and the DOM
* [Google Maps API](https://developers.google.com/maps/documentation/javascript/tutorial) Example
* Pair Programming Exercise
* Review

##### Discussion - Assignment #1 Due Monday 03/03
* Create a single web page experience that, upon user input, responds with data from a web api. One possible approach to this assignment would be to design the experience around answering a question for the user. An example of this is [doineedanumbrella.com](http://doineedanumbrella.com/). Another approach would be to create a mashup that pulls together data from two different apis. An example of this is the InstaTimes example provided here in the class repo. Ulitmately, it's up to you what you want to build. But **(1)** a user needs to "trigger" an event, **(2)** data needs to be requested via AJAX from an API, **(3)** and the page should update appropriately. Your completed assignment should include a .html file, a .css file, and a .js file. 


##### Homework
* Read - [Javascript section of Ch.3 - Interactive Data Viz for the Web by Scott Murray](http://chimera.labs.oreilly.com/books/1230000000345/index.html) up to but not including the section on SVGs
* Read - [Javascript 101](http://learn.jquery.com/javascript-101/) up through the section on Functions  
* Complete & Upload - the 3 code exercises at the end of [Eloquent JS 2nd Edition Preview Ch.2 - Looping A Triangle, FizzBuzz, & ChessBoard](http://eloquentjavascript.net/2nd_edition/preview/02_program_structure.html)
* Think & Post - idea(s) for Assignment #1
* Additional Readings
  * [Eloquent Javascript 2nd Edition Preview - Intro, Ch.1, & Ch.2](http://eloquentjavascript.net/2nd_edition/preview/)
  * [JS For Cats](http://jsforcats.com/)
  * [Mozilla - JS Guide - Values, Variables, & Literals](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Values,_variables,_and_literals)
  * [Mozilla - A Re-Introduction to Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/A_re-introduction_to_JavaScript)


### Week 3 (02/13): Making Things Happen On The Page - Javascript + jQuery

##### Exercise - JS Function

##### Discussion - Week 2 Homework

##### Workshop - Javascript + jQuery
* AJAX
* Loops
* Selectors
* Events
* [PeopleInSpace Example 1](https://github.com/craigprotzel/Mashups/tree/master/PeopleInSpace/Example%201)
* [WikiSearch Example 1](https://github.com/craigprotzel/Mashups/tree/master/WikiSearch/Example%201)
* [WikiSearch Example 2](https://github.com/craigprotzel/Mashups/tree/master/WikiSearch/Example%202)
* [WikiSearch Example 4](https://github.com/craigprotzel/Mashups/tree/master/WikiSearch/Example%204)

##### Homework
* Read - [jQuery - Selecting Elements](http://learn.jquery.com/using-jquery-core/selecting-elements/)
* Read - [jQuery - Manipulating Elements](]http://learn.jquery.com/using-jquery-core/manipulating-elements/)
* Read - [JQuery - Introducing Events](http://learn.jquery.com/events/introduction-to-events/)
* Watch - [The Definitive Guide to Object-Oriented Javascript](http://www.youtube.com/watch?v=PMfcsYzj-9M)
* Create & Upload - a single web page that uses AJAX to load data from a public web api, your work should include a .html file, a .css file, and a .js file


### Week 4 (02/20): Structuring Your App + Guest Talk by Josh Begley 

##### Workshop - OOP in JS + Underscore & Client-Side Templates

##### NY Times + Instagram API Mashup
* [InstaTimes Example 1](https://github.com/craigprotzel/Mashups/tree/master/InstaTimes/Example%201)
* [InstaTimes Example 2](https://github.com/craigprotzel/Mashups/tree/master/InstaTimes/Example%202)
* [InstaTimes Example 3](https://github.com/craigprotzel/Mashups/tree/master/InstaTimes/Example%203)

##### Wikipedia Search API
* [WikiSearch Example 3](https://github.com/craigprotzel/Mashups/tree/master/WikiSearch/Example%203)
* [WikiSearch Example 5](https://github.com/craigprotzel/Mashups/tree/master/WikiSearch/Example%205)

##### Josh Begley - "TBD"

##### Homework
* DUE - Assignment #1
* Read - [Getting Cozy with Underscore JS](http://net.tutsplus.com/tutorials/javascript-ajax/getting-cozy-with-underscore-js/)
* Read - [An Undesrcore Templates Primer](http://headspringlabs.com/blog/an-underscore-templates-primer/)


### Week 5 (03/03): Assignment #1 DUE + Guest Talk by Martin Bravo 

###### **NOTE RESCHEDULED CLASS DATE**
###### **CLASS WILL BE 6:30 - 9:00pm MONDAY NIGHT MARCH 3RD**

##### Presentations - Assignment #1

##### Martin Bravo - "Going From 0 to 1"
* References

##### Homework
* Read - [Ch.4-6 of Interactive Data Viz for the Web by Scott Murray](http://chimera.labs.oreilly.com/books/1230000000345/index.html)

### Week 6 (03/06): Graphs on Graphs on Graphs + Guest Talk by Jeremy Scott Diamond

##### Data Visulaization Tools
* [Google Charts](https://developers.google.com/chart/)
* [ChartJS](http://www.chartjs.org/)
* [D3JS](http://d3js.org/)

APIs - Sunlight Labs

##### Jeremy Scott Diamond - "Working With D3" 
* References


### Week 7 (03/13): A Blank Canvas

##### Animation Tools
* [RafaelJS](http://raphaeljs.com/)
* [PaperJS](http://paperjs.org/)
* [P5](https://github.com/lmccart/p5.js)

API - Xively


### Week 8 (03/27): Moving Pictures

##### Video Tools
* [HTML5 Video](http://www.html5rocks.com/en/tutorials/video/basics/)
* [VideoJS](http://www.videojs.com/) 
* [PopcornJS](http://popcornjs.org/)

APIs - Youtube & Vimeo


### Week 9 (04/03): Assignment #2 DUE + Intro to the Server

##### Presentations - Assignment #2


### Week 10 (04/10): The Server & Storage + Guest Talk by Steve Klise
[API - CouchDB](http://couchdb.apache.org/)

##### Steve Klise - "TBD"
* References


### Week 11 (04/17): Re-Introduce Ourselves with OAuth + Final Project Proposal
API - Twitter


### Week 12 (04/24): Running Wild on Heroku + Guest Talk by Miguel Bermudez

##### Miguel Bermudez - "TBD" 
* References


### Week 13 (05/01): Final Project Workshop & User Testing


### Week 14 (05/08): FINAL DUE

##### Final Presentations


Helpful Links
------------------

#### General Web
* [Mozilla Web Tutorials](https://developer.mozilla.org/en-US/docs/Web/Tutorials)
* [JS Fiddle](http://jsfiddle.net/) - web-based tool to share code
* [11 Phases of a Web Developer's Career](http://net.tutsplus.com/articles/general/the-11-phases-of-a-web-developers-career-as-illustrated-by-memes/)
* [Wappalyzer](http://wappalyzer.com/) - browser plug-in to quickly identify a site's software
* [URL Encoding](http://www.blooberry.com/indexdot/html/topics/urlencoding.htm) or 'What are those "%20" codes in URLs'?
* [Favicon Generator](http://www.favicon.cc/)


#### HTML


#### CSS
* [CSS Tricks - Set Page Background to a Full Image](http://css-tricks.com/perfect-full-page-background-image/)


#### JS
* ["If Hemingway Wrote Javascript" by Angus Croll](http://byfat.xxx/if-hemingway-wrote-javascript)
* [Airbnb Javascript Style Guide](https://github.com/airbnb/javascript)
* [A Drip of JS - Archive](http://designpepper.com/js-drip-archive)  
* [45 Useful JS Tips, Tricks, & Best Practices](http://flippinawesome.org/2013/12/23/45-useful-javascript-tips-tricks-and-best-practices)
* [Mozilla - JS Guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide)
* [Lear X in Y Minutes - Javascript](http://learnxinyminutes.com/docs/javascript/)
* [Javascript Garden](http://bonsaiden.github.io/JavaScript-Garden/) - a collection of documentation about the most quirky parts of JS


#### APIs
* ["A Brief Introduction to REST"](http://www.infoq.com/articles/rest-introduction)
* ["A REST Tutorial"](http://rest.elkstein.org/)
