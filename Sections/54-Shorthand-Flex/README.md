## flex short hand property
* it is a shorthand property and accepts 3 pre-defined properties:
	* flex-grow
	* flex-shrink
	* flex-basis
* Syntax
	```
	Selector {
		flex: flex-grow flex-shrink flex-basis;
	}
	```
* this property needs to be applied on the flex items and not on the flex container.
* flex-grow is a mandatory property, flex-shrink and flex-basis are optional values.
* depiction of values by this property
	* one value: flex-grow
	* two values (both the values are integers): flex-grow and flex-shrink
	* two values (integer and length values): flex-grow and flex-basis
	* three values: flex-grow flex-shrink flex-basis

### flex-grow
* used to increase the size of the flex-item.
* applied to flex-items and not flex-container.
* takes up the free space in the flex-container to increase the size of the flex-item.
* if flex direction:
	* row/ row-reverse: increase the width
	* column/ column-reverse: increases the height
* it depends on the main axis.
* Syntax
	```
	Selector {
		flex-grow: integre value (or) decimal value;
	}
	```
* default value: 0

### flex-shrink
* used to decrease the size of the flex-item
* default value: 1
* flex-shrink does not work in case of flex-wrap properties wrap/wrap-reverse

### flex-basis 
* used to define the initial size of the flex-item.
* accepts length values
* in case of the following flex-direction values, the respective mesaurement gets determined
	* row/row-reverse = width
	* column/column-reverse = height

### summary
* The flex-property is a shorthand property combining flex-frow, flex-shrink and flex-basis properties.
* The flex-grow property takes up the free space in the flex-container and increases the size of a flex-item.
* The flex-shrink property is used to determine, how much an flex-item should shrink depending upon the other flex-items.
* The flex-basis property is used to define the initial size of a flex-item.

