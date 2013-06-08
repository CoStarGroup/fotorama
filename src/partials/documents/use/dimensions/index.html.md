Fotorama’s dimensions are the dimensions of the first image. Other pictures are scaled proportionally to fit.
To reserve the space on the page before the first image is loaded, use `data-width` and `data-height`:

	<div class="fotorama"
	     data-width="800"
	     data-height="600">
	  <img src="1.jpg">
	  <img src="2.jpg">
	  <img src="3.jpg">
	</div>

To make fotorama responsive, define width in percents and aspect ratio:

	<div class="fotorama"
	     data-width="100%"
	     data-ratio="800/600">
	     <!-- the same as data-ratio="4/3"
	          or data-ratio="1.3333333333" -->
	  <img src="1.jpg">
	  <img src="2.jpg">
	  <img src="3.jpg">
	</div>

<p class="after-pre">Example: [Responsive](/<>/responsive.html)</p>

Constrain fotorama’s size to a certain range with `data-min-width`, `data-max-width`, `data-min-height`, and `data-max-height`:

	<div class="fotorama"
	     data-width="100%"
	     data-ratio="800/600"
	     data-min-width="400"
	     data-max-width="1000"
	     data-min-height="300"
	     data-max-height="100%">
	  <img src="1.jpg">
	  <img src="2.jpg">
	  <img src="3.jpg">
	</div>

<p class="after-pre">Example: [Constrained](/<>/constrained.html)</p>

Relative height is calculated based on inner height of the window. A height of 100% covers the entire browser window:

	<body style="margin: 0;">

	  <div class="fotorama"
	       data-width="100%"
	       data-height="100%">
	    <img src="1.jpg">
	    <img src="2.jpg">
	    <img src="3.jpg">
	  </div>

	</body>

<p class="after-pre">Example: [Full window](/<>/full-window.html)</p>