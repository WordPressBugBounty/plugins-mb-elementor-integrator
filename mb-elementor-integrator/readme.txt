=== MB Elementor Integration ===
Contributors: elightup, metabox, rilwis
Donate link: https://metabox.io/pricing/
Tags: meta box, custom fields, elementor, dynamic tags
Requires at least: 5.9
Requires PHP: 7.0
Tested up to: 6.8
Stable tag: 2.2.4
License: GPLv2 or later

Integrates Meta Box's custom fields with Elementor page builder via dynamic tags.

== Description ==

Easily select and show custom fields created by [Meta Box](https://metabox.io) in the Elementor page builder via dynamic tags (Pro version).

> **Meta Box Lite**
> We recommend using [Meta Box Lite](https://metabox.io/lite/), a feature-rich free UI version of Meta Box that provides UI and all free features for managing custom fields and dynamic content on WordPress, including post types, taxonomies, custom fields, and relationships.

The plugin works for all field types. And you don't have to remember the field name or field ID to type. You just need to select it from the dropdown list.

**Video demo**:

https://www.youtube.com/watch?v=NzR9lii2S30&rel=0

### Plugin Links

- [Homepage](https://metabox.io/plugins/mb-elementor-integrator/)
- [Github repo](https://github.com/wpmetabox/mb-elementor-integrator/)
- [View other premium extensions](https://metabox.io/plugins/)

### You might also like

If you like this plugin, you might also like our other WordPress products:

- [Slim SEO](https://wpslimseo.com) - A fast, lightweight and full-featured SEO plugin for WordPress with minimal configuration.
- [Falcon](https://wordpress.org/plugins/falcon/) - WordPress optimizations & tweaks.
- [Auto Listings](https://wpautolistings.com) - A car sale and dealership plugin for WordPress.

== Installation ==

We recommend using [Meta Box Lite](https://metabox.io/lite/), a feature-rich free UI version of Meta Box that provides UI and all free features for managing custom fields and dynamic content on WordPress, including post types, taxonomies, custom fields, and relationships.

If you prefer installing individually, you need to install [Meta Box](https://metabox.io) first:

- Go to Plugins | Add New and search for "Meta Box"
- Click **Install Now** button to install the plugin
- After installing, click **Activate Plugin** to activate the plugin

Then install **MB Elementor Integration** extension

- Go to **Plugins | Add New** and search for **MB Elementor Integration**
- Click **Install Now** button to install the plugin
- After installing, click **Activate Plugin** to activate the plugin

== Frequently Asked Questions ==

== Screenshots ==
1. Meta Box field in the dynamic tags dropdown
2. Connect to a Meta Box Field

== Changelog ==

= 2.2.4 - 2025-04-23 =
Fix cloneable group issue with special characters

= 2.2.3 - 2025-02-04 =
Fix not render HTML tags in subfield WYSIWYG

= 2.2.2 - 2024-11-01 =
- Fix direct file access
- Escape values when outputting

= 2.2.1 - 2024-10-14 =
Fix Plugin Check

= 2.2.0 - 2024-09-26 =
- Add icon field type
- Support get term meta on the single post

= 2.1.13 - 2024-08-19 =
Fix running PHP Codesniffer when installing & autoload the plugin's main file via Composer

= 2.1.12 - 2024-07-24 =
- Fix image advanced and color fields not working

= 2.1.11 - 2024-01-22 =
- Fix Uncaught TypeError: `array_column()`

= 2.1.10 - 2023-07-18 =
- Fix not working with cloneable group

= 2.1.9 - 2023-06-27 =
- Display post title instead of post ID of post field in a group
- Fix error for groups

= 2.1.8 - 2023-06-08 =
- Fix PHP notice for missing check on `mine_type`

= 2.1.7 - 2023-04-03 =
- Fix container background image
- Fix not working with image advanced on the settings page
- Fix PHP warnings

= 2.1.6 - 2022-12-20 =
- Fix PHP errors showing image(s)

= 2.1.5 - 2022-12-05 =
- Fix showing single image

= 2.1.4 - 2022-11-11 =
- Fix advanced features (before, after and fallback content) not displaying when loading the skin in the post template
- Fix fatal error when Meta Box is not active

= 2.1.3 - 2022-09-20 =
- Fix error with count() function
- Fix displaying sub-field URL in a cloneable group
- Fix post title field duplicated

= 2.1.2 - 2022-08-11 =
- Fix count() error

= 2.1.1 - 2022-07-14 =
- Fix not working with settings page

= 2.1.0 - 2022-06-23 =
- Add support for cloneable groups

= 2.0.8 - 2022-03-10 =
- Fix color not working for style tab

= 2.0.7 - 2021-05-27 =
- Fix field not showing if it's the default selected field
- Update to be compatible with the latest version of Elementor

= 2.0.6 =
- Add support for number field

= 2.0.5 =
- Fix mising vendor directory

= 2.0.4 =
- Add support for output from `file_input` field

= 2.0.3 =
- Fix settings fields are not outputted.

= 2.0.2 =
- Remove empty lists.
- Returns full image size for background settings.

= 2.0.1 =
- Fixed output of `taxonomy` field.

= 2.0.0 =
- Rewrote the plugin to better showing field list in post, archive and site groups.
- Removed the fields of internal post types used by MB Custom Post Type extension.

= 1.1.1 - 2019-03-06 =
- Fixed undefined function to detect MB Settings Page that causes fatal error.

= 1.1.0 - 2019-02-26 =
- Added support for custom fields of terms and settings pages.

= 1.0.1 =
- Fixed output for cloneable field.

= 1.0.0 =
- First release.

== Upgrade Notice ==
