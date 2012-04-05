MarkupFacebookSDK for ProcessWire
=================================

This module is a simple helper to include the Facebook SDK as per the [asynchronous method]("https://developers.facebook.com/docs/reference/javascript/"). It will catch any calls to /channel.html, allowing easy setup optimised for cross domain issues on IE.

Usage
-----

Install the module and enter your [AppID]("https://developers.facebook.com/docs/guides/web/") in the module configuration.

In your template, you can include the JavaScript using the render() method.
	
	<?php
	if($modules->get("FacebookMarkupSDK")) {
		$fb = $modules->get("FacebookMarkupSDK");
		echo $fb->render();
	}
	?>
	
	</body>
	</html>

