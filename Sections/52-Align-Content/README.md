## align-content
* aligns the flex-items along the cross-axis
* It is similar to `align-item` property
* Syntax
	```
	Selector {
		align-content: pre-defined-keyword;
	}
	```
* This property accepts 7 pre-defined values, they are:
	* flex-start
		* aligns the flex-items from the starting-point of the cross-axis.
	* flex-end
		* aligns the flex-items from the ending-point of the cross-axis.
	* center
		* aligns all the flex-items along the center of the cross-axis.
	* stretch
		* stretches the flex-items to fit in the flex-container.
		* when the cross axis is:
			* horizontal = if width value is set, width stretching will not work
			* vertical = is height value is set, height stretching will not work
	* space-between
		* creates equal amount of space between the flex-items.
	* space-around
		* creates equal amount of space around the flex-items.
	* space-evenly
		* creates equal amount of space along the cross-axis.
* align-content property works only for flex-container having flex-wrap property with a value other than `nowrap`.

