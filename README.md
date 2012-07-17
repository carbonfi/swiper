Carbon Made jQuery Swiper Plugin
================================

Usage
-----

JavaScript:
```js
$('.swiper').swiper();
```

HTML:
```html
<div class="swiper">
	<div class="swiper-controls">
	  <a href="#" class="prev">Previous</a>
	  <a href="#" class="next">Next</a>
	</div>
	<div class="container">
	  <ul>
	    <li class="element">Slide 1</li>
	    <li class="element">Slide 2</li>
	    <li class="element">Slide 3</li>
	  </ul>
	</div>
	<div class="bullets">
	  <a class="bullet">1</a>
	  <a class="bullet">2</a>
	  <a class="bullet">3</a>
	</div>
</div>
```

CSS:
```css
/* SWIPER ELEMENT */
.swiper   				{ width: 100%; }
.swiper .container,
.swiper .element 		{ width: 960px; height: 580px; overflow: hidden; margin: 0 auto; } /* Define the size of the slide */
.swiper .container > ul	{ margin: 0; padding: 0; list-style: none; }
.swiper .element		{ float: left; margin: 0; padding: 0; }

/* BULLETS */
.swiper .bullets 		{ text-align: center; }
.swiper .bullet 		{ display: inline-block; width: 20px; margin: 0 5px 0 0; text-align: center; }
.swiper .bullet:hover 	{ cursor: pointer; }
.swiper .bullet.on		{ cursor: default; } /* Active bullet styles */

/* CONTROLLERS */
.swiper-controls a	 	{  }
.swiper-controls .prev	{  }
.swiper-controls .next	{  }
```