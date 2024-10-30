=== MACME ===
Contributors: xdxdVSxdxd
Donate link: http://www.artisopensource.net/
Tags: cross media, qrcode, pdf, publishing
Requires at least: 3.0
Tested up to: 3.2.1
Stable tag: 1.2

is a Wordpress plugin that turns any wordpress blog into a cross-medial publishing system.

== Description ==

MACME
Multi Author Cross Media Ecosystem

is a Wordpress plugin that turns any wordpress blog into a cross-medial publishing system. It is a project by FakePress and Art is Open Source

http://www.fakepress.it
http://www.artisopensource.net

MACME is released under a GPL3 ( http://www.gnu.org/licenses/gpl-3.0.html ) license.

Major features of MACME are:

 * ability to add links, images, videos, video embeds, sounds, 3dobjects, google searches, flickr searches and geographical coordinates to any wordpress blog

 * ability to automatically render the contents of the blog into other forms, such as publishable PDFs, XHTMLs that can be easily imported into publishing platforms such as XPRESS and InDesign, and ePub publications that are easily publishable on most e-book readers

 * ability to automatically transform your contents into QRCodes and AR Fiducial markers, so that they can be usable through smartphones or directly to the objects, places and bodies onto which you place the generated QRCodes

 * ability to generate maps and other representations

 * open API to access MACME functionalities and to build new ones (not yet completed, but we're getting there :) )


a tutorial for MACME can be found here:

http://www.slideshare.net/xdxd/reff-04-macmeinstallationtutorial


and here is some documentation to the general project, prepared for workshops on MACME which we are conducting in universities all over Europe

http://www.artisopensource.net/2011/02/17/workshops-and-tutorials-slides-informations-and-software-downloads/

== Installation ==

1. Upload `plugin-name.php` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress

There is a basic tutorial here:

http://www.slideshare.net/xdxd/reff-04-macmeinstallationtutorial

Refer to the information found in the MACME configuration screen on your dashboard to learn about all the features in MACME



== Frequently Asked Questions ==

= is there any tutorial on how to use this plugin? =

There is a basic tutorial here:

http://www.slideshare.net/xdxd/reff-04-macmeinstallationtutorial

Refer to the information found in the MACME configuration screen on your dashboard to learn about all the features in MACME


== Changelog ==

= 1.2 =

removed heavy dependency on GeoIP: now you have to grab your users location by yourself, but you have a lighter, more useful plugin

- when book index is empty it is created automatically from categories
- fixed tag handling bug
- fixed parameters storage bug

= 1.1 =

mini major release.
fixed QRCode generation bugs. Multiple codes of any kind now correctly supported in all combinations

= 1.06 =

fixed problem: now cover image and css are added to PDF as well

= 1.05 =

fixed major bug that created infinite loop if you did not add any MACME content to posts

= 1.04 =

added epub default cover

= 1.031 =
* minor fix on epub format

= 1.03 =
* added epub support
* fixed UTP-8 problem in XHTML, PDF and epub generation
* added book configuration options (title, author, cover image...)

= 1.02 =
* fixed directory structure, now allows automatic install

= 1.01 =
* updated plugin, now generates InfoWindows on general map
* corrected error in show.php headers, removed references to localhost
* in show.php now viewport resizes according to device

= 1.0 =
* initiqal public version
