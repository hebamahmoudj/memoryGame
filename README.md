# Fead Reader Testing Project 
# Table of Contents

* [overView](#overview)
* [Installation](#installation)
[Testing](#Testing)
* [ Run The Project](#HowToRunTheProject)
 # overView 
this project is my fourth project in udacity aim to test the development process and 
many organization practice a standard of development known as TDD this test the behaviour of the code .
  

  # instructions

 ## What I  Was Learn To Make This Project :-
 i learn how to use jasmine library to test pre-existing apps and how the event handling and dom maipulation
 ##How To Use Jasmine Testing In The Project
 you shold know something before you use jasmine library  to test  
 1-How does an IIFE work?
 2-How do you retrieve a particular element from the Document? Feel free to look back at JavaScript and the DOM if you need a review
 3-How do you describe an object by what it does?
 4- How does the expect function work? What do you pass into it?
 5-What is done's role in testing asynchronous processes?
 
# Testing 
* `RSS feed` test  it tests to make sure that the allFeeds variable has been defined , and feeds not empty, loops through each feed to ensure that has a name and URL and both not empty .
* `The menu` test that the menu hidden by default, and also toggle on and off during  click event.
* `Initial Entries`  test to ensures when the loadFeed complete its work , and ensure that the container which have class `.feed` 
has at least single element which have class `entry` in it .
* `New Feed Selection`   when  the feed loaded the content actually changed, using `loadfeed` function as asynchronous.
# How To Run The Project
1 -Download the project and extract it , open `index.html` with any browser.
2 -Or run it using node js.
