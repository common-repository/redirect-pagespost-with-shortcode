Redirect With Shortcode
Contributors: ergauravmittal1989
Donate link: https://paypal.me/ProntoInfosystemLLP
Tags: redirect, thank you page redirct, page refresh
Requires at least: 5.1
Requires PHP: 5.2.4
Tested up to: 5.7.2
Stable tag: 4.5
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Now easily redirects from a page, post or any custom post to any link or page. It redirect the watcher to a pre-characterized URL that defined in shortocde. You have part of optios likewise like content to appear, seconds and so on.

== Description ==

Now easily redirects from a page, post or any custom post to any link or page. It redirect the user to the URL that defined in shortocde. You have part of optios likewise like content to appear, seconds and so on.

Its very usefull in Thank you / Order success pages, where website owner mostly required to return to home or other pages.

= Shortcode =

[pi_redirect url='http://example.com' sec='5' hide_text='yes']

1. url : Here you can add url where you want to redirect.
2. sec : After how many seconds you want to redirect. Add the time in seconds.
3. hide_text (optional): If you want to hide the text "Please wait while you are redirected ...". Use this option. 
This option in optional, if you don't want to hide text just don't use it.

= Donate =

<a href="https://paypal.me/ProntoInfosystemLLP">if you like our work please donate us </a>

= Our Heighlights =
* You can hide text if you don't want to show
* Very simple to use just add shortcode and you are done.
* This plugin does not limit to redirect to same website, you can use other website link also.
* Easily to add number of seconds to redirect.

= Upcoming Features =
* You can change the text "Please wait while you are redirected ..." , you can use your own text and many more.

== Installation ==

This section describes how to install the plugin and get it working.

e.g.

1. Upload plugin folder to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Place `[pi_redirect url='http://example.com' sec='5']` in page/posts OR `< ? php do_shortcode("[pi_redirect url='http://example.com' sec='5']"); ? >` in your templates

== Frequently Asked Questions ==

= Can i hide text "Please wait while you are redirected ..."=

Yes you can hide that by add option hide_text='yes' in shortocde.

= Can i use this in templates? =

Yes you can use in templates. e.g. <?php do_shortcode("[pi_redirect url='http://example.com' sec='5' hide_text='yes']"); ?>

== Screenshots ==

1. This is how we can add shortcode in page or post.
2. This is how we can add shortcode in page templates.
3. This is how it looks on front

== Changelog ==

= 1.0 =
* Initial Release.

== Upgrade Notice ==

= 1.0 =
Upgrade and added hide text option.

= 0.5 =
This version fixes a security related bug.  Upgrade immediately.

= 0.6 =
This version fixes a security related bug.  Upgrade immediately.

= 0.6 =
This version update according to new wordpress version

