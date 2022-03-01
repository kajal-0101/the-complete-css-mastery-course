## list-style-property
* shorthand property, accepts three types of values, list-style-type, list-style-position, list-style-image.
* Syntax 
	```
	Selector {
		list-style: list-style-type list-style-position list-style-image;
	}
	```
* The order does not matter.
* always use list-style-type property with list-style-image property, becuase in case the image does not load, the list-style-type can be used.


### list-style-type
* list-style-type property: used to change the style of the list marker.
* styles only the list items
* list-style-type property accepts pre-defined keyword as its value, like:
	* disc
	* circle
	* square
	* decimal (numeric value for the marker)
	* decimal-leading-zero (puts zero before the numeric if its between 0-9)
	* lower-alpha
	* upper-alpha
	* lower-roman
	* upper-roman
	* none - removes the marker.

### list-style-position
* list-style-position: controls the position of the list marker.
* controls the space between list-marker and list-item
* accepts two types of values: inside and outside.
* deafult value is outside

### list-style-image
* sets an image as a list marker.
* it accepts path of the file as value
* CSS uses function to locate the path of an image
* functions are special type of value used by a property to apply style, like 
	* url() - include a resource from an external source, e.x: path of a file, link from the web 
* note: image cannot be resize using this property.
