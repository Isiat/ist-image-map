## IST-IMAGE-MAP
	Simple web component to create a static image of google maps

## Install

To install it on your local running

	bower install

## How to use

In your html , first added the js webcomponents.js

	<!-- 1. Load platform support before any code that touches the DOM. -->
    <script src="bower_components/webcomponentsjs/webcomponents.min.js"></script>

In your html , adds the custom component web

    <!-- 2. Load the component using an HTML Import -->
    <link rel="import" href="elements/ist-image-map.html">

with this you can already use the webcomponent

 	<ist-image-map></ist-image-map>

If you do not pass any parameter values ​​used are:

	 lat: 43.53120,
     lng: -5.655469999999999,
     zoom: 12,
     sensor: false,
     w: 100% the parent element up to 512px (limited by google) 
     h: 100% the parent element up to 512px (limited by google) 

Sample:

	<ist-image-map lat="43.4607733" lng="-3.800010" zoom="14" w="400" h="300" sensor="true"></ist-image-map>

View [demo](http://quelicoto.es/polymer/ist-image-map/index.html) 