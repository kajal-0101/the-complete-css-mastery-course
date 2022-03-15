## @media
* media queries are used to build responsive web designs.
* responsive websites are webistes that work smoothly on all types of screens.
@media is a part of the rule.
* Syntax
	```
	@media media-type (media-feature) {
		media query block
	}
	```
* media-feature actas as a breakpoint to activate certain styles.
* two important values accepted by media-feature are:
	* min-width
		determines the minimum width of the screen.
	* max-width
		determines the maximum width of the screen.
* media query block refers to the css rules.
* it uses `and` operator to combine breakpoints.

* Example
	```
	index.html

	<body>
		<h1>MEDIA-QUERIES</h1>
		<div>
			<p> Hello, I am a paragraph
			</p>
			<img src="flower.jpg" alt="FLOWER">
		</div>
	</body>

	styles.css

	div {
		display: flex;
		flex-direction: row;
		justify-content: denter;
		align-items: center;
		padding: 50px;
	}

	h1 {
		color: purple;
		font-size: 3rem;
		font-family: sans-serif;
		text-align: center;
	}

	p {
		font-size: 2rem;
		color: #f8667e;
		font-family: cursive;
	}

	img {
		width: 400px;
		height: 400px;
		margin-left: 20px;
	}

	@media (max-width: 1000px) {
		div {
			flex-direction: column;
		}

		p {
			padding: 30px 100px;
			text-align: center;
		}
	}
	```
