=== BuddyForms Custom Login ===
Contributors: svenl77, themekraft, buddyforms, gfirem
Tags: custom login, login form, restrict content, private network, members only
Requires at least: 5.9
Tested up to: 7.1
Requires PHP: 7.4
Stable tag: 1.1.16
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Replace the WordPress login with any page, set where users go after login, and make your site members-only. An add-on for BuddyForms.

== Description ==

BuddyForms Custom Login replaces the default WordPress login with any page you choose, lets you set the registration link and where users go after they log in, and can make your whole site members-only. It is an add-on for BuddyForms.

This add-on needs the BuddyForms plugin. The free version of BuddyForms is enough.

= What it does =

* Replace the default WordPress login with any page, shown in place of the page content, above it or below it
* Set the registration link to any page
* Choose the page users go to after they log in
* Make your site or network members-only: send logged-out visitors to the login page or a custom URL, and choose which pages and post types stay public
* Use the login form anywhere with a block or a shortcode

= Shortcode =

Use [bf_login_form] anywhere. All options are optional:

* redirect_url: where to send users after a successful login
* title: the heading, Login by default
* label_username: Username or Email Address by default
* label_password: Password by default
* label_remember: Remember Me by default
* label_log_in: Log In by default

Example: [bf_login_form redirect_url="/welcome"]

== Frequently Asked Questions ==

= Do I need BuddyForms? =

Yes. This add-on needs the BuddyForms plugin. The free version of BuddyForms is enough.

= Can I customize the appearance of the login form? =

Yes. The login form is shown on a page of your site, so it follows your theme's design, and you can change its title and labels with the block or shortcode options.

= Can I restrict specific content to registered members only? =

Yes. Make the whole site members-only, then choose which pages and post types stay public.

= Is it possible to create a private network with this plugin? =

Yes. BuddyForms Custom Login lets you turn your WordPress site into a private network by limiting access to people who are not registered.

== Installation ==

1. Install and activate BuddyForms.
2. Install this add-on from Plugins > Add New, or upload its folder to /wp-content/plugins/, and activate it.
3. Go to BuddyForms > Settings > Custom Login.

== Documentation & Support ==

> #### Extensive Documentation and Support
> * All code is neat, clean and well documented (inline as well as in the documentation).
> * The BuddyForms Documentation with many how-to’s will help you on your way.
> * Find our Getting Started, How-to and Developer Docs on [docs.buddyforms.com](https://docs.buddyforms.com/)
> * If you still get stuck somewhere, our support gets you back on the right track. You can find all help buttons in your BuddyForms Settings Panel in your WP Dashboard and the Help Center!

== Screenshots ==

1. Settings page: BuddyForms > Settings > Custom Login
2. Choose which pages and post types stay public on a members-only site
3. Option to redirect logged-out visitors to the login page and make the site or network private
4. The login form on the front end


== Changelog ==
= 1.1.16 - 18 Nov 2026 =
* Fixed the login page when BuddyForms is inactive: it no longer redirects to the custom login page, which could not show the login form. The plugin shows a notice instead.
* BuddyForms is now declared as a required plugin.
* The plugin is now called BuddyForms Custom Login everywhere, and broken links in the admin notice and the readme are fixed.

= 1.1.15 - 03 Oct 2026 =
* Fixed a fatal error on every page with PHP 8 when the plugin settings had never been saved.
* Escaped the registration link URL.
* Fixed translations: every string now uses the plugin's own text domain.
* Requires WordPress 5.9 and PHP 7.4. Tested up to WordPress 7.1.

= 1.1.14 - 26 Dec 2023 =
* Updated Freemius SDK.
* Improved plugin description.
* Tested up to WordPress 6.4.2

= 1.1.13 - 18 May 2023 =
* Tested up to WordPress 6.2.1

= 1.1.12 - 08 Dec 2022 =
* Fixed issue with login page selector.
* Fixed issue with redirect after login selector.
* Tested up to WordPress 6.1.1

= 1.1.11 - 28 May 2022 =
* Fixed vulnerability issue.
* Tested up to WordPress 6.0

= 1.1.10 - 17 May 2022 =
* Updated readme.txt

= 1.1.9 - 24 Mar 2022 =
* Added new option to use external url as redirection page.
* Tested up to WordPress 5.9

= 1.1.8 - 23 Sep 2021 =
* Added new option to set "Remember Me" checkbox as checked by default.
* Fixed validation on Public Accesibles Pages.
* Tested up with WordPress 5.8

= 1.1.7 - 1 Apr 2021 =
* Improvements on the custom login page redirection to take into account the WordPress admin email confirmation.

= 1.1.6 - 8 Mar 2021 =
* Tested up with WordPress 5.7

= 1.1.5 - 11 Sep 2020 =
* Fixed to avoid form login custom page redirection, redirect to custom page only when the user is loggin from a custom login page or wordpress default login page.

= 1.1.4 - 06 Jan 2020 =
* Fixed the login redirection for the post and contact form.
* Improved the compatibility with the setting pages of the core plugin.
* Integrated with tk scripts.

= 1.1.3 06. Oct. 2019 =
* Added support for the switching user plugin. There was an issue stopping the plugin from switching the user.

= 1.1.2 04. May. 2019 =
* Added a filter to override the lost password link
* Added the git templates
* Update the readme.txt to point to the correct plugin url to open issues or features request
* Remove WordPress default from the select. Its not needed and just confuses.
* Update the git templates to submit issues or feature requests.

= 1.1.1 21. Nov. 2018 =
* Added one extra check to make sure also pages with child pages or endpoints are recognised

= 1.1 20. Nov. 2018 =
* Added 3 new options to enable a private site or network
** Redirect logged off users to a login and create a private site or network
** Select public Accessible Pages
** Select public Accessible Post Types

= 1.0.1 30. Mar. 2018 =
* Added freemius integration
* Add banner image and thumbnail to wordpress.org assets


= 1.0 21. Mar. 2018 =
first version
