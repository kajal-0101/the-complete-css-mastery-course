## transition
* it is a shorthand property and accepts four types of values namely:
	* transition-property
	* transition-duration
	* transition-timing
	* transition-delay
* Syntax
	```
	Selector {
		transition: transition-property transition-duration transition-timing transition-delay;
	}
	```
* transition-duration and transition-delay, these two values should be in order.
* Example
	```
	styles.css
	div {
		width: 500px;
		height: 500px;
		background-color: #00ff7f;
		border-radius: 50%;
		position: relative;
		top: 130px;
		left: 550px;
		transition: transform 2s, background-color 2s, border-radius 2s;
	}

	div:hover {
		background-color: #00ff7f;
		border-radius: 50%;
		transform: scale(2.5, 1.2);
	}
	```

### transition-property
* points to a CSS property to which you need to apply transition.
* select a css property to apply transition.
* Example
	```
	styles.css
	div {
		width: 400px;
		height: 400px;
		background-color: #00008b;
		transition-property: transform;
		transition-duration: 2s;
	}

	div:hover {
		transform: translateX(500px);
	}
	```

### transition-duration
* refers to the duration for the transition to take place.
* Example
	```
	styles.css
	div {
		width: 300px;
		height: 400px;
		background-color: #00ff7f;
		transition-property: width;
		transition-duration: 3s;
	}

	div:hover {
		width: 700px;
	}
	```

### transition timing function
* used to control the speed of the transition.
* this property accets six types of values, they are:
	* ease
		it starts slowly then moves fast and at last ends slowly
	* linear
		applies the same speed from start to end
	* ease-in
		starts slowly then keeps increasing the speed until the end.
	* ease-out
		starts at full speed then keeps decreasing the speed until the end.
	* ease-in-out
		combines both ease-in and ease-out value, i.e., it starts slowly then moves fast and lastly ends slowly
	* cubic-beizer
		used to create custom speed.

### transition-delay
* used to define the time than an element needs to wait.

### summary
* the transition property is a shorthand property.
* it accepts four kinds of values, they are:
	* transition-property
	* transition-duration
	* transition-timing-function
	* transition-delay
* The transition-property is used to select a CSS property to which you like to apply transition.
* The transition-duration property refers to the duration for the transition to take place.
* The transition-property and transition-duration property are mandatory property for the transition shorthand property.
* the transition-timing-function property is basically used to control the speed of the transition from start to end.
* the transition-delay property is used to define the time, that an element needs to wait, before applying the transition.
* the transition-duration and transition-delay properties accepts timings as values, basically they accept values in seconds or milli-seconds.
* the transition is the shorthand property that is used to combine all the four properties.
* in transition shorthand property, the first timing value represents the transition-duration and the second timing value represent the transition-delay.

