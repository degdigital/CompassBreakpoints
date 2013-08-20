CompassBreakpoints
==================

SASS Breakpoints with Compass

##Define the MediaQuery Variables
```
$mediaQuery1: "screen and (max-width: 19.938em)";
$mediaQuery2: "screen and (min-width: 20em)";
```

##Call Mixin
```
@include breakpoint($mediaQuery1) {
	style: value;
}
```

or

```
.selector {
	@include breakpoint($mediaQuery2) {
		style: value;
	}
}
```