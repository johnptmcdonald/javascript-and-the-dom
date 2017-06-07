#Javascript and the DOM!
###Display Types, Normalize.css, centering!

##Students will be able to...
* Explain what the DOM is
* Use javascript to select parts of the DOM
* Use javascript to change parts of the DOM

##Starter
Let's mess up the New York Times! Turn Google into Bing!

As a browser loads a page, it creates a representation of that page in which each element is an object. This representation is called the DOM tree, and it is stored in the browser's memory. 

![DOM Tree](http://www.webstepbook.com/supplements/slides/images/dom_tree.gif)

##Pair questions
* what is a JS object? (how would we write it out?)
* how can I access the properties of a JS object?

Let's discuss JS objects with a real world example.

We can do example the same thing with JS objects. 

##Let's use JS to 'grab' part of the DOM
Do a git pull, and subl . into "javascript_and_the_dom"

* document.getElementsByTagName("h1"); <!-- this returns an array! -->
* document.getElementsByClassName("info") <!-- this also returns an array! -->
* document.getElementById("content"); <!-- this returns a single object -->

##Now let's use JS to CHANGE some of the attributes of these elements.
* if we want to change the text of the element, we can grab the element and change its innerHTML property.
* if we want to change the CSS of an element, we can grab then element and change its style.color or its style.width

##BONUS ROUND! Let's use JS to add an event listener to an object...

###There are three ways to do it
* In HTML: ```<element onclick="myFunction()">``` <img src="http://upload.wikimedia.org/wikipedia/en/2/2f/Thumbs-down-icon.png" align="top right" height="25px" width="25px"</img>

* In JavaScript: ```object.onclick=function(){myScript};``` <img src="http://www.clker.com/cliparts/2/7/d/5/1247117411176075605Symbol_thumbs_up.svg" align="top right" height="25px" width="25px"</img>

* In Javascript using the addEventListener() method: ```object.addEventListener("click", myFunction);``` <img src="http://www.clker.com/cliparts/2/7/d/5/1247117411176075605Symbol_thumbs_up.svg" align="top right" height="25px" width="25px"</img>

When the happy/sad face is clicked, make a pop up a window appear saying how happy you are now that you know how to manipulate the DOM. 









# javascript-and-the-dom
