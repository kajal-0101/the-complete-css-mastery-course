## transform
* using this proerty we will be able to rotate, skew, scale and even move HTML Element.
* Syntax
	```
	Selector {
		transform: function (arguments);
	}
	```
* The transform property accepts 4 types of transform values, they are:
	* translate
	* scale
	* rotate
	* skew


### translate
* the translate value is used to move an HTML element.
* the translate is combination of translateX() and translateY() values.
* the translateX() value is used to move an HTML element towards right or left.
	* Syntax
	```
	Selector {
		transform : translateX(length);
	}
	```
	* positive value moves the element towards right and negative value moves the element towards left.
* the translateY() value is used to move an HTML element upwards or downwards.
	* Syntax
	```
	Selector {
		transform : translateY(length);
	}
	```
	* positive value moves the element down and vice versa.
* the translate value is used to move an HTML element diagonally.
* Syntax
	```
	Selector {
		transform : translate(translateX, translateY);
	}
	```

### scale
* used to increase or decrease the size of an HTML element.
* combination of scaleX() and scaleY() value.
* the scaleX() value is used to increase or decrease the width of an HTML element.
* Syntax
	```
	Selector {
		transform : scaleX(length);
	}
	```
* the default value is 1, if it is set to 0, then it won't be shown.
* the scaleY() value is used to increase or decrease the height of an HTML element.
* Syntax
	```
	Selector {
		transform : scaleY(length);
	}
	```
* the scale value is used to increase or decrease the width and height of an HTML element.
* Syntax
	```
	Selector {
		transform : scale(scaleX, scaleY);
	}
	```

### rotate
* used to rotate an element in clockwise or anticlockwise direction.
* rotateX(): rotates an element along the x-axis.
* Syntax
	```
	Selector {
		transform : rotateX(degree);
	}
	```
* positive value rotates and element in clockwise direction and negative value rotates an element in anti-clockwise direction.
* rotateY(): rotates an element along the y-axis.
* Syntax
	```
	Selector {
		transform : rotateY(degree);
	}
	```
* rotate(): used to rotate an element around a fixed position

### skew
* used to make some slanting effects to HTML element.
* shorthand value combining both skewX() and skewY() values.
* used to make some slanting effects on all four sides.
* Syntax 
	```
	Selector {
		transform: skew (degree, degree);
	}
	```
* skewX()
	* tilts an element along the x-axis
	* used to make some slanting effects on left and right side.
* skewY()
	* tilts the element along the y-axis.
	* used to make some slanting effects on top and bottom side.


### summary
* with the help of transform property, you will be able to rotate, skew, scale and even move an HTML element from one place to another.
* We use the translate value to move an HTML element from one place to another.
* We use the scale value to increase or decrease the width and height of an element.
* we use the rotate value to rotate an HTML element.
* we use the skew value to make some slanting effects on all four sides of an HTML element.
