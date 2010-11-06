=== CAC Featured Content ===
Contributors: michael@castironcoding.com
Tags: mu, featured, feature, feature content, wordpres mu, buddy press, buddypress
Requires at least: 2.9
Tested up to: 3.0.1
Stable tag: 1.0

The CAC Featured Content plugin provides a widget that allows you to select among five different content "types" to feature in a widget area. 

== Description ==

The CAC Featured Content plugin was developed for City University of New York's Academic Commons — an online community powered by WordPress MU and Buddy Press. It is assumed that the plugin will be installed alongside Buddy Press, although it could easily be modified to run without Buddy Press content. The widget provides the user with several useful tools for tailoring the content to work within many different themes. For example, the widget editor has the ability to specify a length (in characters) that will be used to crop text content. Whenever possible, the widget attempts to find an image to use along with a set of featured content. For groups the image is the group's avatar, for members the individual's avatar is used, for the blog the author's avatar is used, for posts the image used is either the first image within the post or the post author's avatar. The resource type allows the user to specify an image from an external source or to use the media browser, built in to the widget (much of the code used to implement this feature comes from Image Widget, by Shane & Peterm, Inc.). The incorporation of additional methods for including images are planned for future releases. 

Image cropping is possible by way of the excellent TimThumb: http://code.google.com/p/timthumb/

Text cropping comes by way of the TYPO3 project: http://typo3.org/ 

== Installation ==

1. Download and unzip cac-featured-content.zip to your plugin folder.
2. Activate the plugin from the Plugins section of your dashboard.
3. Place a "CAC Featured Content" widget in a widget area and edit some content. 
4. Edit the "views" in cac-featured-content.php to wrap your content in the appropriate markup. Using the markup shipped with the widget may or may not look broken within your template!

== Additional Notes ==

* You'll need to edit the views for each content type in cac-featured-content.php. The view methods are in the form renderType\_CONTENT_TYPE_IN_ALL_CAPS(). The included view methods start at about line 815.



== Frequently Asked Questions ==

There is not currently a FAQ available for this plugin. Please check back later. 