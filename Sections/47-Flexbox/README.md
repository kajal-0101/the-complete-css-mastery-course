## flexbox
* Example
	```
	index.html
	<body>
		<div class="parent">
			<div class="child-1"></div>
			<div class="child-2"></div>
			<div class="child-3"></div>
		</div>
	</body>

	styles.css
	.parent {
		width: 1000px;
		height: 700px;
		background-color: #142f43;
		display: flex;
	}
	.child-1 {
		width: 200px;
		height: 200px;
		background-color: #ffab4c;
	}
	.child-2 {
		width: 200px;
		height: 200px;
		background-color: #ff5f7e;
	}
	.child-3 {
		width: 200px;
		height: 200px;
		background-color: #b00b9;
	}
	```

### summary
* the concept of flexbox is used to customize and align the child elements of a parent.
* In the concept of flexbox, the parent element is known as flex-container and the child elements are known as flex-items.
* Primarily, it depends on two axes, they are:
	* main-axis
	* cross-axis
*  Be default, the main axis starts from the left to right, but it can be changed using the flex-direction property.
* The cross axis is always perpendicular to the main axis.
* the display property with flex as a value is used to convert a parent element into a flex container and the child elements into flex-items.
* The flex-containers and flex-items obey all the css flex-box properties.
* The display property with the value `flex` must be used for the parent element, to make the parent and all its child element obey all the cdd flex-box properties.
