## @keyframes rule
* used to create beautiful animations
* animation in CSS = change from one style to another.
* simaple animations are created using
	* transition
	* pseudo-class
* disadvantage of transition property for CSS animation:
	* requires action to activate the animation.
	* cannot control the steps that are present in-between the transition, i.e., creating breakpoints is impossible.
* keyframe is not a property but a CSS rule.
* Syntax
	```
	@keyframes animation-name {
		from {
			CSS Styles
		}
		to {
			CSS Styles
		}
	}
	```
	* from = strating point of the animation
	* end = ending point of the animation
* to apply the key-frmae rule, the animation-name property must be used.
* animation-duration: refers to the duration for the animation to take place.

* percentages are used as keyframe selectors, ranges between 0%(starting point) to 100% (ending point).
* percentages feature allows us to add intermediate styles.
* Example
	```
	keyframes move {
		0% {
			transform: translateX(0px);
		}
		50% {
			background-color: black;
		}
		100% {
			transform: translateX(1330px);
		}
	}
	```

### Summary
* the keyframe rule is used to add css styles in between the starting and ending point of an animation.
* @keyframe is a psrt of css rule.
* it is used to control the behaviour of the animations.
* the starting point of animation is defined using 0% or from keyword.
* the ending point of the animation is defined using 100% or to keyword.
* intermediate steps can be defined using the percentage keyframe selector and the percentage value must be in between 0% to 100%.
* the `animation-name` and `animation-duration` property needs to be used to activate the keyframe rule.
