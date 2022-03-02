## psudeo-class
* a selector, uses the `:` symbol.
* it selects elements based on specific state.
* Syntax:
	```
	Selector: pseudo-class {
		property: value;
	}
	```
* Example:
	```
	a: visited {
		color: red;
	}
	```

### :link psuedo-class
* selects all anchor tags with href attribute.
* only elements having href attribute will be selected.

### :visited psuedo-class
* selects all the anchor tags that are visited by the browser.

### :active psuedo-class
* styles the selected element when it is activated.
* in most of the cases, an elements is activated when it is clicked.

### :checked psuedo-class
* This pseudi-class is mostly used with input elements like check-box or radio.
* it styles the elements when checked or selected.
* Example
	```
	input [type="checkbox"]:checked + label{
		background-color: springgreen;
		color: red;
	}
	```

### :focus psuedo-class
* this psuedo class is mostly used for input elements.
* styles the input element when activated by keyboard or mouse.
* Example
	```
	input[type="text"]: focus {
		background-color: yellow;
	}
	```

### :not pseudo-class
* It is like a function and accepst selector as argument.
* It is used to removed an element from a group of elements.
* Example:
	```
	li:not(.second-list-item) {
		background-color: violet
	}
	```
### :first-child pseudo class
* selects the first child of the parent
* Example:
	```
	li:first-child {
		background-color: springgreen;
	}
	```

### :last-chile psuedo class
* selects the last child of the parent
* Example:
	```
	li:last-child {
		background-color: springgreen;
	}
	```
### :nth-child psuedo class
* selects elements based on its order.
* This pseudo class is like a function, it takes numeric value/pre-defined keywords/formulas as arguments.
* Example - numeric-value
	```
	li:nth-child(3) {
		background-color: springgreen;
	}
	```
* Example - predefined-value
	```
	li:nth-child(odd) {
		background-color: springgreen;
	}
	```
* Example - predefined-value
	```
	li:nth-child(3n) {
		background-color: springgreen;
	}
	```
	* selects all the elements that are multiple of n.

### :nth-of-type pseudo class
* It selects elements based on its order like nth-child pseudo class but it is mre specific.
* Example:
	```
	p:nth-of-type(2){
		background-color: #ffcocb;
	}
	```
* use nth-of-type psudeo class in general and use nth-child class only if it is necessary.
	
### :hover psuedo-class
* this psuedo-class can be used for any HTML element.
* Example:
	```
	button:hover {
		background-color: springgreen;
	}

	a:hover {
		font-weight: bold;
		background-color: #ff20cf;
	}
	```

### Summary
* pseudo classes are used to select HTML element based on specific state.
* The `:link` psuedo class selects all anchor tags with the href attribute.
* The `:visited` pseudo class selects all the anchor tags that are already visited by the browser.
* The `:active` pseudo class styles the selected element when it is activated.
* The `:checked` pseudo class styles the input element when it is selected or checked.
* The `:focus` psuedo class styles the input element when it is activated by keyboard or mouse click.
* The `:not` psuedo class is used to remove or omit element or elements styling from a group of selected elements.
* The `:first-chile` pseudo class selects the first child element.
* The `:last-child` psuedo class selects the last child element.
* The `nth-child` psuedo class selects elements based on order.
* the `nth-of-type` pesudo class is similar to nth-child pseudo class but nth-of-type psuedo class is more specific.
* The `:hover` psuedo class styles the element that is in hover state.