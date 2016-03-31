Tacoma-JS Musings 31-Mar 2016

Hello Coders,

First I want to thank [Tim M.](https://github.com/TimMikeladze) and [Chris E.](https://github.com/enviroeberhardt) for recent suggestions for the the Tacoma-JS [weatherApp](https://github.com/Tacoma-JS/weatherapp).  Tim [forked](https://github.com/TimMikeladze/weatherapp) the project, added [meteor](https://www.meteor.com/) as a development tool, and made a few other suggestions for improvement.  He pointed out that we could update the code to use ES6 Javascript. Chris [linked](http://www.meetup.com/Tacoma-JS/messages/boards/thread/49699935) to an example website in our discussion area that presents air quality and wind diagrams.  We will explore this idea as part of our app in future discussions.


### ES6 Javascript (ECMA Script 6th Edition)
--------------------------------------------
* Since the release date was June 2015 this letter is not exactly [news](http://www.infoq.com), however we should take note and begin using the new features that test okay as we code.

  * Some reference links:

    * ECMA Specification [pdf](http://www.ecma-international.org/ecma-262/6.0/ECMA-262.pdf)
    * [Wikipedia](https://en.wikipedia.org/wiki/ECMAScript#6th_Edition)
    * [Features](http://es6-features.org/#Constants)
    * [Compatibility](https://kangax.github.io/compat-table/es6/)

* Authors on ES6
  * [Luke Hoban](https://github.com/lukehoban/es6features#readme)
  * [Kyle Simpson](https://github.com/getify/You-Dont-Know-JS/tree/master/es6%20%26%20beyond)
  * [Nicholas Zakas](https://github.com/nzakas/understandinges6)

### Objects
-----------
At a recent meetup there was a question about understanding javascript objects.  I wonder how many other people may have the same question.  A reference book is "The Principles of Object-Oriented Javascript" by Nicholas Zakas, [no starch press](https://www.nostarch.com/oojs).  A generic reference will help to put objects in perspective, "The Object Oriented Thought Process" by Matt Weisfeild, [Addison Wesley](http://www.informit.com/store/object-oriented-thought-process-9780321861276).
  * Some reference links:
    * Zakas on ES6 [objects](https://github.com/nzakas/understandinges6/blob/master/manuscript/04-Objects.md)
    * [.info](http://javascript.info/tutorial/objects)
    * Intro to [OOjs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Introduction_to_Object-Oriented_JavaScript)
    * [javascriptkit](http://www.javascriptkit.com/javatutors/oopjs.shtml)



### Off the wall hacks
----------------------
#### Variable scope with jQuery AJAX
Assuming the library jQuery is installed consider this line of code which adds a new empty object to jQuery.  ```  $.oyster={};  ```  The analogy might be like going to a fine sea food restaurant and bringing your own appetizer with you into the restaurant; frowned upon, but do-able. Adding the object 'oyster' gives you a place to store transient AJAX response data within the upper scope of jQuery.
```
      $.oyster={}; //a nice cozy place to store my stuff in jQuery scope
      $.get( myURL, function( data, status ) {
        if (status==='success'){
             $.oyster.xml = data; //data will lose scope, but not $.oyster !!!
             }
       });
```

### [Free Code Camp](https://www.freecodecamp.com/)
I was recommending another online school offered through Pierce Countly Library, however that has been discontinued and all brownie points unceremoniously deleted.  Therefore I have begun taking the coursework at [FreeCodeCamp](https://www.freecodecamp.com/) to make sure it is worth recommending to those who want that style of learning.  There is also a facebook [page](https://www.facebook.com/groups/free.code.camp.tacoma/).

### Remote Pair Programming
I made some [notes](https://github.com/Tacoma-JS/BestPractices/blob/master/pair_programming_notes.md) about remote pair programming with links to articles, tools and how-to videos. We could explore doing a remote coding meetup.


## :smile: Coding
Your organizer,
Joe
