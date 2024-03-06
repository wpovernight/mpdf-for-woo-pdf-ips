=== mPDF engine for PDF Invoices & Packing Slips for WooCommerce ===
Contributors: wpovernight
Donate link: https://wpovernight.com/
Tags: woocommerce, mpdf, pdf, rtl
Requires at least: 4.4
Tested up to: 6.4
Requires PHP: 7.2
Stable tag: 2.5.0c
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Add mPDF engine compatibility to WooCommerce's PDF Invoices & Packing Slips for flexible document creation.

== Description ==

Enhance your WooCommerce PDF Invoices & Packing Slips with mPDF engine integration, replacing the default engine for improved handling of specific languages, including Arabic and Hebrew. This alternative offers robust support for right-to-left orientation, ensuring seamless document creation for a wider range of linguistic needs.


== Frequently Asked Questions ==

= Something is not working correctly =

Please post a message to our [support forum](https://wordpress.org/support/plugin/woocommerce-pdf-ips-mpdf) and we'll do our best to help resolve your issue!

= How can I contribute to this project? =

This project is hosted on github: https://github.com/wpovernight/woocommerce-pdf-ips-mpdf
If you want to contribute to the code, feel free to submit a PR. You can also open issues on Github, although we encourage you to open a ticket in the support forum here on WordPress.org first if you're not absolutely sure something is a bug.

== Changelog ==

= 2.4.0 =
* New: Support for invoice notes & the display document notes setting
* New: RTL support setting in General tab
* New: Template wrapper class indicating mpdf & rtl usage
* Fix: Exclude from WooCommerce plugin compatibility checklist
* Fix: Removing p tags on item meta
* Fix: Add missing template action hooks

= 2.3.0 =
* New: Support for invoice notes & the display document notes setting
* New: RTL support setting in General tab
* New: Template wrapper class indicating mpdf & rtl usage
* Fix: Exclude from WooCommerce plugin compatibility checklist
* Fix: Removing p tags on item meta
* Fix: Add missing template action hooks

= 2.2.0 =
* Fix/feature: apply header logo height setting
* Fix/feature: apply new address visibility settings
* Fix: Thumbnail sizes
* Fix: premium template footer styles
* Fix: issues with meta and sku/weight display
* Tweak: suppress domdocument warnings by default

= 2.1.2 =
* Fixed PHP7.4 compatibility (Updated mpdf to 8.0.6)

= 2.1.1 =
* Fix: only enable substitutions if additional fonts included

= 2.1.0 =
* Feature: Added non-RTL replacement for Simple template.
* Feature: Enable character substitutions from backup fonts
* Updated RTL template

= 2.0.0 =
* Updated mpdf to 8.0
* Removed vendor library from repo
* Fix: logo height issue
* Fix: Previous errors caught erroneously by mpdf
* Tweak: filter for mpdf options (wpo_wcpdf_mpdf_options)

= 1.0.2 =
* Log exceptions

= 1.0.1 =
* Swapped table cell text alignment from left to right

= 1.0.0 =
* First public release