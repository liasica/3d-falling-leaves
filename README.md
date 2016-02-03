3d-falling-leaves
=================

A jQuery plugin that drops leaves on the page.

* [View demonstration](http://daftspunk.github.io/3d-falling-leaves/)


```html
<!-- jQuery is required if you're not already using it -->
<script src="//ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>

<!-- Falling leaves provided by http://www.top-site-list.com -->
<script src="http://www.top-site-list.com/scripts/assets/falling-leaves/rotate3Di.min.js"></script>
<script src="http://www.top-site-list.com/scripts/assets/falling-leaves/3d-falling-leaves.min.js"></script>
<link rel="stylesheet" href="http://www.top-site-list.com/scripts/assets/falling-leaves/3d-falling-leaves.min.css" />
<script>
$(document).fallingLeaves({
	leafStyles: 3,			// Number of leaf styles in the sprite (leaves.png)
	speedC: 2,				// Speed of leaves
	rotation: 1,			// Define rotation of leaves
	rotationTrue: 1,		// Whether leaves rotate (1) or not (0)
	numberOfLeaves: 15,	// Number of leaves
	size: 40,				// General size of leaves, final size is calculated randomly (with this number as general parameter)
	cycleSpeed: 30			// Speed (see http://www.jqueryscript.net/animation) (Inverse frames per second) (10-100)
})
</script>
```
