## box sizing property
* this property is used to define the behaviour of width and height when border and padding is added.
* width = left-border + left-padding + width + right-padding + right-border
* height = top-border + top-padding + height + bottom-padding + bottom-border
* content box refers to the width & height starting from the border not from elements width & height.
* box-sizing accepts two values
	* content-box: default value for the property
	* border-box

### difference between content-box and border-box
* In case of content-box, the border and padding is added with the element's width and height.
  But, in case of border-box, the border and padding is not added with the element's width and height.
* In case of content-box, the element's width and height is changed but in case of border-box, the element's width and height is not changed.

### summary
* The box-sizing property is used to control the width and height of an element when border and padding is applied.
* The content-box value adds up the border and padding with the width and height of the element.
* The border-box value does not add up the border and padding size to the total width and height.
* In content-box value, there is no change in elements width and height while in border-box the element width and height will decrease.

