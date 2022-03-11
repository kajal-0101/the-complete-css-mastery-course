## align items
* part of the flex box.
* aligns the flex-items along the cross-axis.
* Syntax
	```
	Selector {
		align-items: pre-defined-keywords;
	}
	```
* it accepts 5 pre-defined values, they are:
	* flex-start
		* aligns the flex items from the starting point of the cross-axis.
	* flex-end
		* aligns the flex items from the ending point of the cross-axis.
	* center
		* aligns the flex-items towards the center of the cross-axis.
	* baseline
		* aligns the flex-items on the basis of text inside them, i.e. the aligning is done in such a way that the text inside the flex-item are in a straight line.
	* stretch
		* default value
		* strecthes the flex-items to fit in the flex container
		* if width and height property is applied to flex-items, the flex-items will not `stretch`
		* when the cross axis is:
			* horizontal = if width value is set, width stretching will not work
			* vertical = is height value is set, height stretching will not work
* chnage in main-axis, will cause change in the cross-axis.



