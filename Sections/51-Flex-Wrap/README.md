## flex-wrap
* used to align the flex-items either in a signle or multiple lines.
* This propery decides whether the flex-items should bundle up or stick to a single line or take up a new line.
* Syntax
	```
	Selector {
		flex-wrap: pre-defined-keyword;
	}
	```
* It accepts 3 pre-defined values:
	* nowrap
		* default value
		* all the flex items will be aligned in a single line.
		* width and height of the flex-items are compressed.
	* wrap
		* flex-items will not shrink, instead they will move to a new line.
		* wraps along the cross axis.
	* wrap-reverse
		* opposite of the wrap value, i.e., wraps the flex-items in the reverse order.

### summary
* the flex-wrap property is used to determine, how the flex items should behave when the width or height of the fles-items is larger than the flex-container.
* The flex-wrap proprty is used to make the flex-items align in a same line or multiple lines.
* It accepts three pre-defined keywords as values, they are:
	* nowrap: used to align the flex items in a single line
	* wrap: creates a multi-line alignment ot overflowing flex-items.
	* wrap-reverse: behaves exactly the same like the wrap value, but the alignment starts from the end of the cross-axis.
* The flex-wrap value depends on cross-axis and the align-items property.

