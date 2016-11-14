# Startup Institute - Intro to jQuery
## Course Outline



### What is jQuery?

jQuery is a JavaScript library that makes doing things in JavaScript easier. 

* Used on millions of websites. 
* Saves time, work, and thinking

```js

// Plain old JavaScript.

document.addEventListener("DOMContentLoaded", function() {
	var links = document.getElementsByTagName("a");
	
	for (var i=0; i<links.length; i++) {
		links[i].classList.add("link1");
	}	
});



// Same code in jQuery. 
 
$(function(){
	$("a").addClass("highlighted");
});
```



### Important Concepts

* Elements
	* Selecting Elements
		* Selectors
		* Traversal
	* Manipulating Them
		* .addClass() / .removeClass()
		* .attr() / .prop()
	* Looping Through Them
	* 	.each()
	* Getting Information About Them
* Getters & Setters
* Events
	* Types of Events
		* .on()
	* Callback Functions
* jQuery Documentation







	
	



