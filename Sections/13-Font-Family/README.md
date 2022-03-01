## font-family
* Used to change the font of the text.
* Accepts font-name/ font-family as the value.
* There are two major font-family in CSS, they contains many fonts.
	* serif
		* Times New Roman
		* Garamond
		* Georgia
	* sans-serif
		* Arial
		* Poppins
		* Calibri
* Not all fonts might be installed in browsers of different devices, for this reason, use backup fonts.
* Example
	```
	p {
		font-family: Arial, "Times New Roman", sans-serif;
	}
	```
	* all the backup fonts must be separated using `,`.
	* If the font name has more than one words, it should be written with `""`.
	* In this case, the priority of fonts redices from left to right.
* Even while using google font, its a good idea to use backup font, in case the browser is unable to download the required font.



### Summary
* The font-family property is used to change the font of the text.
* Always use some backup Fonts and a font family at the end.
* Google Fonts are game changers, so always keep an eye on Google Fonts.
* Most of the Websites uses Google Fonts.
