# Owl Slider

##### include CSS into your HTML head:

```html
	<link rel="stylesheet" href="css/owl.carousel.css">
```

##### Include jQuery and owl.carousel.min.js into the footer.

```html
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
	<script src="js/owl.carousel.min.js"></script>
```

##### Create the element in your HTML:
```html
	<div class="owl-carousel">
		<div> Your Content </div>
		<div> Your Content </div>
		<div> Your Content </div>
		<div> Your Content </div>
		<div> Your Content </div>
		<div> Your Content </div>
		<div> Your Content </div>
	</div>
```

##### In the main.js:
```javascript
	$(".owl-carousel").owlCarousel();
```

##### More options:
```javascript
	$(".owl-carousel").owlCarousel({
		items: 3,
		loop: false,
		center: false,

		mouseDrag: true,
		touchDrag: true,
		pullDrag: true,
		freeDrag: false,

		margin: 0,
		stagePadding: 0,

		merge: false,
		mergeFit: true,
		autoWidth: false,

		startPosition: 0,
		rtl: false,

		smartSpeed: 250,
		fluidSpeed: false,
		dragEndSpeed: false,

		responsive: {},
		responsiveRefreshRate: 200,
		responsiveBaseElement: window,
		responsiveClass: false,

		fallbackEasing: 'swing',

		info: false,

		nestedItemSelector: false,
		itemElement: 'div',
		stageElement: 'div',

		// Classes and Names
		themeClass: 'owl-theme',
		baseClass: 'owl-carousel',
		itemClass: 'owl-item',
		centerClass: 'center',
		activeClass: 'active'
	});
```

http://www.owlcarousel.owlgraphic.com/docs/api-options.html