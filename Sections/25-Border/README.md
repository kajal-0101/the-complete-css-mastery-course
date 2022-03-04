## border property
* It is a shorthand property.
* A short hand property is a property that combines two or mode properties into a single property.
* border property accepts three types of values, border-width, border-style and border-color.
* the border-style value is mandatory.
* in case, the border-width and border-color value is not assigned, the default values are:
	* border-wdith = medium
	* border-color = black
* Syntax
	```
	Selector {
		border: border-width border-style border-color;
	}
	```
	* The order does not matter.
* border refers to the line that is drawn around the HTML element.
* other border properties include:
	* border-top
	* border-right
	* border-bottom
	* border-le

### border-width
* defines the thickness of the border.
* aceepts two types of values, pre-defined keyword and length.
* The pre-defined values are:
	* thin - 1px
	* medium - 3px
	* thick - 5px
* border width property is a shorthand property, it accepts four values
	* border-top-width
	* border-right-width
	* border-bottom-width
	* border-left-width
* In case only one value is used for the border-width property, all four sides will have the same value.
* In case of providing two values, the top & bottom will use the value1 and the left & right will use the value2.
* In case of providing three values, the first value is used by the top, the second value is used by the left and right element, the third values is used by the bottom.
* In case of four values, the first value is used by the top, the second value is used by right, the third value is used by bottom and the fourth value is used by left.
* This syntax is known as 1-to-4 syntax.

### border-style
* Used to change the style of the border line.
* It accepts nine types of values:
	* none - no border is drwan
	* solid - straight border line with no gaps
	* double - line which are parallel to each other.
	* dashed - used to create a dashed line.
	* dotted - used to create dotted line.
	* groove - used to create a 3D type border, that look nice on images
	* ridge - same like groove but colors are exchanged.
	* inset - modern border look
	* outset - opposite of inset value
* This is also a shorthand property and also follows 1-to-4 syntax.

### border-color
* Change the color of the border.
* It is a shorthand value and also follows the 1-to-4 syntax


### inherit value
* inherit value can convert a non-inheritable property to a inheritable property
* Example
	```
	index.html
	<body>
		<div>
			<h1>This is a heading.</h1>
		</div>
	</body>

	styles.css
	div {
		border: 10px solid #f72585;
		color: purple;
	}
	h1 {
		border: inherit;
	}
	```
	* Exaplanation: The h1 tag inherits the color of its parent, i.e. div element, but not the border as border is not a inheritable property. By setting the border element of h1 tag to inherit, we can make the h1 element inherit the border of its parent element.

### summary
* In web-development, b0rder is just a line that is drawn around the element.
* The border-width property is used to define the thickness of the border.
* The border-style property is used to determine the type of the line for the border. It is basically used to change the style of the border line.
* The border-color property is used to set a color for the border.
* All the above three properties obey 1-to-4 value syntax.
* Border is the shorthand property that is used to combine all the baove three properties.

