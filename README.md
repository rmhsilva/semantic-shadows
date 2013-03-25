##semantic-shadows

Semantic Stylus for pure CSS drop shadows.

This is essentially a re-write of [Nicolas Gallagher's](http://nicolasgallagher.com/css-drop-shadows-without-images/) CSS drop shadows, but in Stylus, so that they can be added to elements cleanly.

Provides mixins:

    sh-raised()
	sh-rotated()
	sh-lifted()
	sh-curved-vt-1()
	sh-curved-vt-2()
	sh-curved-hz-1()
	sh-curved-hz-2()

The names of the mixins match the classes on Nicolas' demo page.

To add a drop shadow to an element, just include one of the mixins.  Note: some shadows (e.g. lifted) look better on wider elements.