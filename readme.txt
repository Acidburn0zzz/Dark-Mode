=== Dark Mode ===
Contributors: danieltj, munyagu, travel_girl, melchoyce, afercia, hedgefield, megane9988, presskopp
Tags: accessibility, admin, dashboard, profile, style
Requires at least: 4.0
Tested up to: 4.9
Stable tag: 1.3
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Let's your users make the WordPress admin dashboard darker.

== Description ==

= About the Plugin =

Feature plugin with the hopes that it'll make it's way into Core one day! We highly recommend you don't use this on production websites.

Using technology at night time can have a negative effect on your eyesight. Dark Mode will darken the colours of your admin dashboard making it easier for you to work at night time.

For information on the progress of this plugin, [please refer to the Trac ticket](https://core.trac.wordpress.org/ticket/41928) or you can get involved on the [GitHub repository](https://github.com/danieltj27/Dark-Mode).

= Plugin Developers =

As some plugins make use of custom stylesheets, you can use the `doing_dark_mode` action hook to include a custom stylesheet that supports Dark Mode for your plugins interface. Alternatively you can use the `dark_mode_css` filter hook to change the Dark Mode stylesheet for your own. 

== Installation ==

1. Unzip and upload the plugin package into the plugins directory.
2. Login to the dashboard and activate the plugin.
3. Go to your profile and enable the Dark Mode setting.

== Frequently Asked Questions ==

= Why is there a plugin for this? =

The goal is to have this plugin merged into the WordPress Core. For more information, please see the GitHub repository or Trac ticket.

= What does this plugin do? =

It adds an option for users to enable a 'dark mode' which will turn the admin dashboard darker so it's nicer to use at night time.

= Can I contribute to this plugin? =

Yes! You can follow the Trac ticket for updates and get involved on GitHub with suggestions, feedback and code contributions!

= How can I remove the feedback link? =

The Feedback link will take a user to the GitHub repository and will only be shown when Dark Mode is currently on. To completely remove it for every user, put `define('DARK_MODE_FEEDBACK', true)` in your `wp-config.php` file.

== Screenshots ==

1. The dashboard with Dark Mode turned off.
2. The dashboard with Dark Mode turned on.
3. Dark Mode with an admin colour scheme.
4. The setting in a user's profile to turn Dark Mode on.

== Changelog ==

= 1.3.1 =

* Updated the stylesheet to now include the Customiser.
* Fixed a typo in the plugin readme relating to the feedback constant.
* Moved the feedback link from the left to the right of the toolbar.

= 1.3 =

* Added link to GitHub repository for people to provide feedback.
* Added the ability to schedule Dark Mode to come on between certain times.
* Improved the implementation of certain core functions for better control.
* Updated the styles to include more areas that were previously unstyled.

= 1.2 =

* Added CSS source maps to files making it easier to develop the stylesheet further.
* Updated a translation string for better clarity.
* Updated the documentation comments for a few functions.
* Fixed more issues with elements that are not styled. Thanks to all those who spotted them!
* Minor optimisations made to the stylesheet to help reduce the file size.

= 1.1.2 =

* Further updates to the colour palette used in the new design.
* More elements within the dashboard have been styled.

= 1.1.1 =

* Updated the readme.txt file information.
* Minor improvements to code documentation blocks.
* Restyled the new Try Gutenberg banner on the dashboard index.
* Updated the colour palette and swapped blue for purple!

= 1.1 =

* Redesigned (most of) the admin dashboard into a darker design.
* Added a filter hook to change the URL of the Dark Mode stylesheet.
* Minor improvements to the code.

= 1.0 =

* Initial version.
