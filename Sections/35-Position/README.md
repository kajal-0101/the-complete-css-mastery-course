## position
* This property is used to determine how an element should be positioned on the browser.
* Alternatively, this property can be used to change the position of an element along with the help of top, right, bottom, left properties of CSS.
* The position property accets five types of value, they are:
	* static
		* default value for all HTML elements.
		* Keeps all the HTML elements in the normal document flow.
		* Normal Document flow means the HTML elements are positioned one after the other based on the order written in the HTML file.
		* elements are arranged in an ordered sequence.
		* the major disadvantge of this value is that the top, bottom, left, right properties of the CSS don't work.
	* relative
		* It is similar to the static properties, but the top, right, bottom, left properties of CSS are obeyed.
		* it will keep the elements as per the normal document flow.
	* absolute
		* same as the relative value, but it removes the HTML elements in the normal document flow, i.e., HTML elements will not have any space for it.
		* an element with absolute position will depend on its parent with a position value of relative, fixed, sticky.
		* If no parent have position property, then the absolute positioned element moves to the HTML or root element.
	* fixed
		* The fixed value is same as the absolute value, but the only difference is that it is always relative to the root element.
		* It stays at the same place even after scrolling.
	* sticky
		* combination of relative and fixed value.
		* it looks like the relative value and behaves like the fixed value.
		* While using the top, bottom, left, right value it behaves as the relative propery and while scrolling it behaves like the fixed property.
		* the breakpoint is used to activate the fixed position.
		* Example
			```
			styles.css

			.second {
				width: 200px;
				height: 200px;
				background-color: #00008b;
				position: sticky;
				top: 50px;
			}
			```
		* It acts like a fixed value only inside the parent element.

### summary
* the position property is used to change the position of an element along with the help of top, right, bottom and left properties.
* the position property accepts five types of values, they are:
	* static
	* relative
	* absolute
	* fixed
	* sticky
* static value is the deafult value for all css properties.
* static value keeps the element in a normal document flow and topm left, right and bottom properties are not obeyed.
* relative value is exactly the same as the static value but the only difference is that the top, left, right and bottom properties are obeyed.
* absolute property is similar to the relative property, but the HTML elements are removed from the normal socument flow.
* absolute property always depends on the parent element position property other than static.
* If no parent element have position property other than static, then it moves to the root element.
* fixed position is similar to the absolute position, but the only difference is that they do not depend on the parent elements position property.
* the important part of the fixed value, is that the element stay in the same place even when we scroll.
* the sticky value is a combination of relative and fixed value.
* It behaves like relative value when we position that element.
* But, it acts like a fixed value when we scroll.
* The top property acts as a breakpoint for the sticky value to act like a fixed value.

