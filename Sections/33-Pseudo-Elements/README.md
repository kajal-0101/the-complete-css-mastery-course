## pseudo elements
* It is used for two different purposes:
	* to style a specific part of the HTML element, example:
		* first letter
		* first line
		* list marker
		* user select
	* to add content for a website without HTML tags

### ::first-letter
* selects the first letter of the HTML element (text based elements)
* Example
	```
	index.html
	<body>
		<h1>This is a heading</h1>
	</body>

	styles.css
	h1::first-letter {
		font-size: 80px;
		color: rgb(1, 26, 255);
	}
	```

### ::first-line
* selects the first line of the HTML element. (text based)
* Example
	```
	index.html
	<body>
	<p>This is the first line of the paragraph containing random texts.
	This is the second line of the paragraph containing random texts.</p>
	</body>

	styles.css
	p::first-line {
		font-weight: bold;
		background-color: #00ff7f;
	}
	```

### ::marker
* styles the list markers
* list markers are basically like texts and they obey all the text based properties like color, font-size etc.
* Example
	```
	index.html
	<body>
		<ul>
			<li>First Item</li>
			<li>Second Item</li>
			<li>Third Item</li>
		</ul>
		<ol>
			<li>First Item</li>
			<li>Second Item</li>
			<li>Third Item</li>
		</ol>
	</body>

	styles.css
	ul ::marker{
		color: #ffa500;
		font-weight: bold;
		font-size: 50px;
	}

	ol ::marker {
		color: #ff0062;
		font-size: 40px;
		font-style: italic;
	}
	```

### ::selection
* It is used to apply style when a user selects an HTML element.
* It is mostly applied on text based elements.
* Example
	```
	index.html
	<body>
	<p>This is a piece of random text.</p>
	</body>
	styles.css
	p ::selection {
		background-color: pink;
		color: purple;
	}
	```

### ::before and ::after
* used for adding content for a website without HTML Tags, i.e. using only CSS.
* It is used to decorate the already present HTML Element.
* content property is a mandatory property for `::before` & `::after` pseudo elements.
* The ::beofre pseudo element is used to add content before an HTML element.
* The ::after pseudo element is used to add content after an HTML element.
* Example - ::before
	```
	index.html
	<body>
		<h1>Learn to Style Faster</h1>
	</body>

	styles.css
	h1 ::before {
		content: "";
		display: inline-block;
		height: 10px;
		width: 200px;
		border-radius: 20px;
		background-color: #ffb4a2;
		border: 5px solid #6d6875;
	}
	```

* Example - ::after
	```
	index.html
	<body>
		<h1>Happy</h1>
	</body>

	styles.css
	h1 ::after {
		content: "Birthday";
		background-color: springgreen;
	}
	```

