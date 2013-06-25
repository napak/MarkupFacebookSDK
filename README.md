Facebook SDK inclusion for ProcessWire
======================================

MarkupFacebookSDK module is a simple markup module for [ProcessWire]("http://processwire.com") to include the Facebook SDK as per the [asynchronous method]("https://developers.facebook.com/docs/reference/javascript/"). It will catch any calls to /channel.html, allowing easy setup optimised for cross domain issues on IE.

Usage
-----

Install the module and enter your [AppID]("https://developers.facebook.com/docs/guides/web/") in the module configuration.

In your template, you can include the JavaScript using the render() method.
	
	<?php
	if($modules->get("FacebookMarkupSDK")) {
		echo $modules->FacebookMarkupSDK->render();
	}
	?>
	
	</body>
	</html>

