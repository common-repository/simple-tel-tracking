=== Plugin Name ===
Contributors: harrymumf
Donate link: harrymumf
Tags: simple, tel, tracking, seo
Requires at least: 3.0.1
Tested up to: 3.7
Stable tag: 4.3
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Adds Google Analytic code to all tel links and mailto links.

== Description ==

Uses jQuery to add Google Analytics tracking code to all tel links and mailto links on all pages.

1. Add and enable plugin
2. It just works!

The plugin is open-source, the code is here: https://www.github.com/harrymt/simple-tel-tracking

The href=X of the mail and tel link will also be sent to Google Analytics.

e.g. for these two links

`<a href="mailto:someone@example.com">someone@example.com</a>`
`<a href="tel:+123456789">Bristol 123456789</a>`

Google will report:

`ga('send', 'event','Mailto Tracking: someone@example.com','Click/Touch');`
`ga('send', 'event','Phone Call Tracking: 123456789','Click/Touch');`


== Changelog ==

= 1.0 =
* Release
