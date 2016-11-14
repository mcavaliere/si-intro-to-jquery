# Startup Institute - Intro to jQuery
## Course Outline



### What is jQuery?

jQuery is a JavaScript library that makes doing things in JavaScript easier. 

* Used on millions of websites. 
* Saves time, work, and thinking

document.addEventListener("load", function() {
	var links = document.getElementsByTagName("a");
	
	for (var i=0; i<links.length; i++) {
		var classes = links[i].attributes.....class.split(" ");
		classes.push("highlighted");
	}	
});

$(function(){
	$("a").addClass("highlighted");
});



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







	
	



