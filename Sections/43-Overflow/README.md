## overflow
* controls the extra content of an HTML element.
* shorthand property, combining oevrflow-x and overflow-y.
* the overflow-x property controls the extra content along the x-axis.
* the overflow-y property controls the extra content along the y-axis.
* Syntax
	```
	Selector {
		overflow: overflow-x overflow-y;
	}
	```
* accepts four types of values, they are:
	* visible: does not remove the extra width and height
	* hidden: removes the extra width and height
	* scroll: uses scrolling to show the extra content
	* auto: similar to scroll, but scroll bar is only visible when there is extra content.
* we mostly use the overflow property to the parent element, to remove the extra content from the child element.

