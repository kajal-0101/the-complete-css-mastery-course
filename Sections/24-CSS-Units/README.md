## css units
* CSS Units are used to determine the size of a property.
* Length value will have CSS units.
* There are two types of CSS units, Absolute and Relative.
* Absolute Unit: does not depend on the size of the parent element, these unit are static throughout all devices.
* Relative Units: Depends on the size of the parent element.
* Three of the most commonly used relative units are:
	* percentage
	* em
	* rem
* percentage is a relative unit, it always depends on the value of its parent element.
* percentage formula = parent pixel value * child percentage value / 100
* Percentage for font-size: This percentage unit gets the value from the parent elemnt having the font-size property.
* the pre-defined value for the font-size property is 16px.
* em is font-relative unit, it depends on the font-size of the parent element.
* It is used for building responsive websites.
* Both percentage and em depends on the font-size of the parent element.
* Why do we need em units? for responsive font size
* px unit is not responsive.
* em units multiply the pixel value of the parent element.
* Challenges: em units for nested elements in case of font-size
* thus, avoid em units for font-size.
* Including em units for width and height
	* While using em units for width and height, it does not depend on its parent element.
	* First, it checks for the font size property inside the element itself.
	* Second it checks for the parent element for font-size property.
* rem: root font size
* rem depends on the font-size of the root or HTML element.
* The font size of the browser is the font size of the rem unit.
* There are two ways to change the font size of the root element.
	* Option-1:
	```
	html {
		font-size: 20px;
	}
	```
	* Option-2:
	```
	:root {
		font-size: 20px;
	}
	```

### summary
* CSS units are used to control the size and length of a property.
* CSS Units are divided into two parts: absoulte units and relative units
* Absolute units does not depend on any other units.
* Relative units depend on other CSS value.
* The most popular absolute unit is pixel.
* A pixel is nothing but a small squared boc with RGB colors.
* In CSS we define pixel as px.
* Percentage value always depend on the value of its parent element.
* em units depend on the font-size of the parent element.
* rem units always depend on the value of the font-size property that is present in the root element.
* HTML element is known as the root element.

