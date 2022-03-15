## animation
* shorthand property
* Syntax
	```
	Selector {
		animation: animation-name
				   animation-duration
				   animation-timing-function
				   animation-delay
				   animation-ietration-count
				   animation-direction
				   animation-fill-mode
				   animation-play-state;
	}
	```
* ordering is important, first duration value refers to animation duration and second duration value refers to animation delay

### animation-name
* this property points to a keyframe rule
* mandatory value for animation shorthand property
* it is used to select the keyfrmae ruke tp apply animation.
* the value of the property is a keyframe rule name.

### animation-duration
* refers to the duration for the animation to take place.
* accepts value in the form of `s` and `ms`.
* mandatory value of animation shorthand property.

### animation-timing-function
* used to control the speed of the animation.
* this peoperty accepts 6 pre-defined values, they are
	* ease
	* linear
	* ease-in
	* ease-out
	* ease-in-out
	* cubic-beizer

### animation-delay
* used to define the time that an element needs to wait before applying an animation.
* accepts value in the form of `s` and `ms`.

### animation-iteration-count
* used to control the number of times and animation should be iterated, i.e., the number of times an animation should execute a full keyframe cycle.
* it accepts two types of values
	* integer
		* should be a positive value
		* this number determines the number of times an animation should be played.
		* default value is 1.
	* pre-define keyword
		* infinte: animation is executed infinite times.

### animation-direction
* controls the direction of the animation.
* Syntax
	```
	Selector {
		animation-direction: pre-define-keyword;
	}
	```
* the values accepted by this property are:
	* normal: animation is played in the forward direction
	* reverse: animation is played in the backward direction
	* alternate: 
		* animation is alternatively exhibited in the forward and backward direction respectively.
		* animation-iteration-count > 1
	* alternate-reverse:
		* animation is alternatively exhibited in the backward and forward direction respectively.
		* animation-iteration-count > 1

### animation-fill-mode
* used to apply styles before and after an animation.
* Syntax
	```
	Selector {
		animation-fill-mode: pre-defined-keyword;
	}
	```
* The vlaues accepted by this property are:
	* none
		* default value
		* does not apply any style
	* forwards
		* applies the last keyframe styles after the end of the animation.
	* backwards
		* applies the first keyframe styles before the start of the animation
	* both
		* used to apply sty;es before and after an animation.

### animation-play-state
* used to pause or play an animation, i.e., this property controls the pause and play state of an animation.
* this property accepts two values, they are:
	* running
		* default value
		* used to activate or play an animation
	* paused
		*  used to stop an animation.

### summary
* the animation-name property is used to select a keyframe rule, to apply the animation present in the keyframe rule to a CSS property.
* the animation-duration property refers to the duration for the animation to take place.
* the animation-timing-function property is basically used to control the speed of the animation from start to end.
* the animation-delay property is used to define the time, that an element needs to wait before applying the animation.
* the animation-iteration-count property is used to control the nimber of times an animation should be played.
* the animation-direction property is used to control the direction of the animation.
* the animation-fill-mode property is used to apply some styles, before the start of the animation and after the end of the animation.
* the animation-play-state property is used to pause or play the animation.
* the animation shorthand property is used to combine all the eight animation prooperties.


