=== Safe Redirect Manager ===
Contributors: tlovett1, tollmanz, taylorde, 10up, jakemgold, danielbachhuber, VentureBeat
Tags: http redirects, redirect manager, url redirection, safe http redirection
Requires at least: 3.1
Tested up to: 3.4.1
Stable tag: trunk

Safely and easily manage your websites HTTP redirects.

== Description ==

Safe Redirect Manager is a HTTP redirect manager for WordPress. An easy-to-use UI allows you to redirect locations to new URL's with the HTTP status codes of your chosing. The plugin uses the wp_safe_redirect function which only allows redirects to whitelisted hosts for security purposes. The plugin automatically handles whitelisting hosts for you.

[Fork the plugin on GitHub.](https://github.com/tlovett1/Safe-Redirect-Manager)

== Installation ==

Extract the zip file and just drop the contents in the wp-content/plugins/ directory of your WordPress installation and then activate the Plugin from Plugins page.

== Screenshots ==

1. This view shows all your redirects. You can filter them by date or even search through them.
2. This is the edit redirect page. Specify a "from" path, "to" path/URL, and a status code. You can schedule redirects for later dates just like posts.

== Changelog ==

= 1.3 =
* safe-redirect-manager.php - Globalize SRM class for use in themes/plugins/scripts. Added create_redirect method to make importing easier.

= 1.2 =
*   safe-redirect-manager.php - manage_options capabilitiy required to use redirect manager, remove checkbox column, hide view switcher, fix search feature, hide privacy stuff for bulk edit

= 1.1 =
*   safe-redirect-manager.php - plugin_url() used properly, is_plugin_page function

= 1.0 =
*   Plugin released
