## specificity
* a rule that gets applied when multiple selector with same CSS property selects the HTML same element.
* Example Scenario
	```
	index.html
	<body>
		<h1 class="class-heading" id="id-heading">This is a heading </h1>
	</body>

	#id-heading {
		background-color: yellow;
	}

	styles.css
	#id-heading {
		background-color: yellow;
	}

	.class-heading {
		background-color: springgreen;
	}

	h1 {
		background-color: violet;
	}
	```
* Priority of selectors (the priorty decrease down the list
	* important
	* Inline CSS
	* id
	* class, attributee, pseudo class
	* type
	* universal
* During conflict of selectors, the selctor with the highest priority will be selected.
* In case of the above example, the id selector will be selected.

* In case of conflict between CSS styles with same priority, latter rule, i,e, last come first apply, gets applied.
* Example
	```
	p {
		background-color: aqua;
	}

	p {
		background-color: pink;
	}
	```
* In the above example, the paragraph will get pink background colour.
* Syntax of important rule 
	```
	Selector {
		property: value !important;
	}
	```
* Example
	```
	h1 {
		background-color: violet !important;
	}
	```
* Use the important rule, only if it is neccessary.

### Summary
* Specificity is a rule that gets applied when multiple selector with same css property selects the same HTML element.
* In specific ranking, universal selector has the lowest priority.
* Type Selector has higher priority than the universal selector.
* Class, Attribute and Pseudo-Class Selector has higher priority than the Type Selector and Universal Selector.
* ID Selector has the highest priority than any other CSS selector.
* Inline CSS has higher priority than the ID Selector.
* Latter Rule uses a concept named last come first applies.
* Important RUle has the highest priority than any other Selector and Inline CSS. It is the kind of specificity.
