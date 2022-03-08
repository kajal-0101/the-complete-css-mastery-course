## background-image
* used to insert an image as a background.
* This property follows the exact syntax of list-style-image property.
* Example
	```
	styles.css
	div {
		background-image: url("image.jpg");
		width: 500px;
		height: 500px;
		background-size: 500px 500px;
	}
	```
	* In case of background-size, the values represent the width and height respectively.

* gradient refers to combining colors.
* the background-image property accepts three types of gradient values:
	* linear-gradient
	* radial-gradient: starts from the center and mix up the colors in a circular path
	* conic-gradient: mixes up the colors through a rotation starting from the centre.
* we need atleast two colors for exhibiting gradient
* Syntax
	```
	Selector {
		background-image: linera-gradient(direction, color1, color2);
	}
	```
* Sites to find gradient colors: uiGradients
* Sites to generate Gradient Colors:
ColorSpace


### Summary
* The background-image property is used to insert an image as a background.
* We use the background-size property to control the width and height of the image.
* gradient is like mixing of one color with another.
* linear-graident is used to mix up the colors in a straight or in an one direction.
* radial-gradient starts from the center and mixes up the colors in a circular path.
* conic-gradient mixes up the color through a rotation starting from its center as its origin.
