=== Plugin Name ===
Contributors: philsbury, muttznutz
Tags: NSFW, Not safe for work
Requires at least: 4.9
Tested up to: 4.9.1
Stable tag: 0.1.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Adds a checkbox to posts and media assets to flag them NSFW

== Description ==

From an Age Gate feature request from @muttznutz, it seemed easier for a new plugin.

This simply adds a checkbox to posts and media assets to flag them NSFW.

Then, from your theme you can then call:

`get_nsfw_ids();`

Which will return an array of IDs that can be queried against with `post__not_in` or your own method.

== Installation ==

1. Upload `not-safe-for-work` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress


