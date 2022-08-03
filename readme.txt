=== Ingeni Custom Nav Menu Fields ===

Contributors: Bruce McKinnon and wp-qa.com
Tags: accessibility, navigation, aria
Requires at least: 6
Tested up to: 6.0.1
Stable tag: 2022.01



== Description ==

Provides custom attributes for Wordpress nav menu items, primarily for adding accessibility aria labels.




== Installation ==

1. Upload to the '/wp-content/plugins/' directory.

2. Activate the plugin through the 'Plugins' menu in WordPress.

3. Modify the menu items in the Wordpress Appearance > Menus section.




== Frequently Asked Questions ==


= Which aria attributes are supported? =

V2022.01 supports aria-label and aria-hidden


= How do I set the aria attributes? =

Modify the menu item properties in the Wordpress Appearance > Menus section.


= How are the aria attributes added to my theme's navigation menus? =

The plugin uses the wp_edit_nav_menu_walker() hook to bypass the standard menu walker, allowing the custom attributes to be added to the HTML of individual menu items.





== Changelog ==

2022.01 - Initial release.