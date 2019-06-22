# Development tasks

- Remove what is not needed
	- Do not import the whole bootstrap
	- Do we need the whole jquery?
	- Try to remove any animations which dont add value
	- Can we use less images?
	- Trim what is unneeded / unused from CSS files


- Loading order
	- Load above the fold css first, rest later
	- Load most or all js at end of body
	- No async or defer: scripts that affect the DOM above the fold
	- Async: scripts that don't affect the DOM
	- Defer: scripts that are not essential for initial page load / do something below the fold


- Optimize images
	- reduce size of any huge images
	- Match size of image to the size it will be displayed on screen
	- Display different image sizes for different device sizes
	- Use tools for image optimization
	- Remove any meta tags from images

- Optimize code
	- Minimize JS DOM manipulation
	- Use document.DOMCOntentLoaded and document.load event listenrs to do things after these events

- Minification
	- Can we reduce number of css files?
	- Combine scripts into one?
	- Use minified version of bootstrap DONE
	- Use the minified version of jQuery DONE
	- Uglify code

## Page load times

Slow 3G connection
- Initial (DOMContentLoaded / Load in ms): 5.89 / 34.93