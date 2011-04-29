=== Plugin Name ===
Contributors: maxime.rainville
Donate link: http://maximerainville.com/password_rules
Tags: password, user
Requires at least: 3.0.0
Tested up to: 3.0.1
Stable tag: 0.3

This simple plugin allows the WordPress site administrator to enforce minimal password requirements on its user.

== Description ==

This simple plugin allows the WordPress site administrator to enforce minimal password requirements on its user.  You can specify a minimal password length.  You can also demand that users input uppercase characters, digits or special characters.  This only effects password changes.  Existing passwords will not be validated.

== Installation ==
1. Drop the 'password_rules' folder in your plugin directory.
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Set your desired password requirements in Settings/Password Rules

== Frequently Asked Questions ==

= What are the default password requirements impose by WordPress? =

Anything except an empty string can be use as a password in an out of the box WordPress installation.

= Why should I care about the password of my users? =

Short passwords using a small character set are vulnerable to brute force attacks.  Also, IT deparements in large organisations will often request minimal security requirements before deploying an app; this extension can help you cut throught the red tape. 

= What about existing users? =

WordPress hashes passwords before storing them in its database.  You can not determined the original password from its hashed.  So it's impossible to validate existing password to see if they meet your requirements.  This extension will only validates passwords when the user updates his profile.  

== Screenshots ==

1. Settings page.

== Changelog ==

= 0.1 =
* Initial release.

= 0.2 =
* Corrected bug that prevented translations from being displayed.

= 0.3 =
* Very minor correction to translation in French.

== Upgrade Notice ==

