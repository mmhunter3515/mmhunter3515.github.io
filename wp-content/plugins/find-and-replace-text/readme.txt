=== Find And Replace Text ===
Contributors: jesselau
Donate link: https://jesselau.com/en/
Tags: editor, find, replace, TinyMCE
Requires at least: 4.7
Tested up to: 4.9.8
Stable tag: 2.0
Requires PHP: 5.6
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

A simple plugin to install find and replace function button in WordPress editor on both visual TinyMCE and text mode.

== Description ==

[Find And Replace Text](https://jesselau.com/wordpress-plugin-find-and-replace-text/) plugin allows you to install a find & replace button to your Wordpress Editor.

It supports batch finding and replacing string when you edit your posts either in TinyMCE visual or text mode. 

Please note the plugin in TinyMCE visual mode also find and replace string in raw file. Which means that you should make sure there are not HTML tag to find and replace.

For example, if you find and replace "href" to "something else" in Visual mode. The plugin also change every "href" to  "something else" if the HTML codes have links with "href" even you can not see the "href" string on the visual mode screen.

So please make sure that you are not replacing HTML tags in Visual mode. Or you can start from Text mode.

Remember saving your post before your find and replace anything. So even you make something mess you can always get revisions back.



== Installation ==

1. Go to the Add New plugins screen in your WordPress Dashboard
1. Click the upload tab
1. Browse for the plugin file (find-and-replace-text.zip) on your computer
1. Click "Install Now" and then hit the activate button



== Screenshots ==

1. Find & Replace button above the Editor.
2. Find what.
3. Replace with.
4. Confirm to replace.

== Frequently Asked Questions ==
= Where can I get help? =
[Find And Replace Text](https://jesselau.com/wordpress-plugin-find-and-replace-text/) plugin is supported via [the wordpress.org support forum](https://wordpress.org/support/plugin/find-and-replace-text). Or you can go to [Find And Replace Text page](https://jesselau.com/wordpress-plugin-find-and-replace-text/).

= What if I replaced wrong strings for my whole post? =
Don't worry. You can always press Ctrl-Z in TinyMCE visual mode to undo your replacement.

== Upgrade Notice ==
none

== Changelog ==

= 2.0 =
* Support both visual and text mode. Rewrite code with JQuery. Add media button.

= 1.0 =
* Support text mode. add button to quick tag.
