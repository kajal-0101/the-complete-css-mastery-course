## justify-content
* part of the flex box.
* used to align the flex-items along the main axis.
* It only works if the following values are set:
	```
	display: flex
	flex-direction: value
	```
* Syntax:
	```
	Selector {
		justify-content: pre-defined-keyword;
	}
	```
* it accepts 6 pre-defined values
	* flex-start: 
		* default value
		* flex-items will be aligned from the starting point of the main axis.
	* flex-end
		* flex-items will be aligned from the ending point of the main axis.
	* center
		* flex-items will be aligned towards the center of the main-axis.
	* space-between
		* creates equal amount of space between the flex-items.
	* space-around
		* creates equal amount of space around the flex-items.
		* an equal amount of space is created between the flex-items, but the space before the first flex-item and the space after the last flex-item is half the space between the flex items.
	* space-evenly
		* creates equal amount of space along the main axis.
		
