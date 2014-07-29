A Sticky Footer with no Wrapper
===============================

An example for making your footer stick to the bottom of the page without the extra markup.

The Important Stuff
-------------------

Make the markup whatever you want, just have the footer be a child of the body tag.

```
html {
	position: relative;
	min-height: 100%;
}

body {
	margin-bottom: 60px;/* make this equal to the height of the footer */
}

footer {
	position: absolute;
	bottom: 0;
	width: 100%;
	height: 60px;/* should be the same as the margin-bottom of the body */
}
```

View a live demo here: http://andyosuna.com/github/sticky-footer/
