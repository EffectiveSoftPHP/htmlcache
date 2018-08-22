# HTML Cache plugin for Craft CMS 3.x

Cache pages to HTML and boost website performance.

This plugin generates static HTML files from your dynamic Craft CMS project. After a HTML file is generated, your webserver will serve that file instead of processing heavier and slower PHP scripts.

99% of your visitors will be served static HTML files. A cached file can be served thousands of times. That 1% could be a POST request (like AJAX forms) and btw:

* sections with a login won’t work
* the admin panel is also NOT cached


## Requirements

This plugin only requires Craft CMS 3 or later.


## HTML Cache Overview

Creates a HTML Cached page for any non-cp GET request for the duration of one hour (configurable) or until an entry has been updated. 
To work in DEV-mode: use the force option in the settings.


## Configuring HTML Cache

Use the plugin settings to configure it.


## Using HTML Cache

HTML Cache has a settings page where you can enable/disable and flush cache.


## Credits

Made with ❤️ by [Bolden](http://www.bolden.nl) – It's free to use, but if you insist 😄 donate [here](https://www.paypal.me/boldenamsterdam)

Based – but rewritten, on the HTML Cache by CraftAPI in 2016
