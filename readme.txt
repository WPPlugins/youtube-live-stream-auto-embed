=== Youtube Live Stream Auto Embed===
Contributors: sykemedia
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=7SCTYGSQ3R3ME
Author: Wordpress Youtube Live Stream
Link: http://www.wordpressyoutubelivestream.com/
Tags: YouTube, Videoplayer, Auto Embed, YouTube Live stream, google hangouts, hangouts, onair, Shortcode, live-streaming, API v3
Requires at least: 3.4
Tested up to: 4.7
Stable tag: 1.0.2
License: GPLv3 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Provides a shortcode to automatically embed the latest video or current live stream of a specified YouTube channel including Google Hangouts OnAir.

== Description ==

This Wordpress plugin provides a shortcode to automatically embed ANY live stream from a specified YouTube channel ID. [youtube-live]
It comes with an admin settings page to let you set the options for the embeded YouTube Player.

**Main Features:**

* <strong>Automatically</strong> Embeds a YouTube <strong>Live Stream</strong> from a Channel ID
* Options to set YouTube Player Width and Height
* Left, Center Align or Responsive Player Size

**Pro Version:**

* <strong>NEW FEATURE:</strong> Display text/image/html content with a message that changes when streaming live and when not streaming live using a new shortcode 
* <strong>Automatically</strong> Embeds a YouTube <strong>Live Stream</strong> from a Channel ID
* <strong>Automatically</strong> Embeds Latest Video OR Playlist when <strong>NOT</strong> Streaming Live   
* Options to set YouTube Player Width and Height
* Left, Center Align or Responsive Player Size
* Select Player Theme Color, Dark / Light
* Change Progress Bar Color, Red / White
* Hide / Autohide Player Controls
* Hide Player Title Bar
* Autoplay / Autoplay Muted
* Set different options for the Live Player and Latest Video Player

<strong>How it works..</strong> (<a href="http://www.wordpressyoutubelivestream.com/" target="_blank">View LIVE Demo</a>)

<strong>A.</strong> If you're currently live, automatically display the live video. (Free Version)

<strong>B.</strong> If you're not currently live, display the previous upload/live event or playlist. (<a href="http://www.wordpressyoutubelivestream.com/plugin/youtube-live-stream-auto-embed-wordpress-plugin-youtube-live-wp-plugin/" target="_blank">Pro Version</a>)

**Plugin Support**

We have made this plugin super simple to install and setup, however if you have any trouble or run into any problems <a href="http://www.wordpressyoutubelivestream.com/contact/" target="_blank">get in touch</a> and we will spend the time to help you get the plugin up and running correctly.

If you are upgrading to the Pro Version be sure to remove the free version before installation an enter your Channel ID instead of Username on the admin settings page. 

<strong>Works using the latest YouTube API V3</strong>

== Installation ==

1. Upload the complete `youtube-live-stream-auto-embed` folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Go to the plugins settings page located in in the settings tab of the Wordpress admin menu and setup your default settings
4. Paste the Youtube Live shortcode in a page or post [youtube-live]
5. ALL DONE!

**Make Any Shortcode Work in a Widget**

To make the shortcode work in a widget you need to add this line to your functions.php file

add_filter('widget_text', 'do_shortcode');

Your Functions file is located here...

http://www.yourwebsite.com/wp-content/themes/YOURTHEME/functions.php

**YouTube API Credentials**

Full detailed instructions with images can be found on the plugins admin settings page, making things nice and simple.

1. Go to the Google Developers Console <a href="https://console.developers.google.com/project" target="_blank">www.console.developers.google.com/project</a>
2. Select a project, or create a new one
3. In the sidebar on the left, expand APIs & auth. Next, click APIs. In the list of APIs, make sure the status is ON for the YouTube Data API v3 by creating a new Public API access key.

**YouTube Channel ID Code**

1. Find your YouTube Channel ID by visting <a href="https://www.youtube.com/account_advanced" target="_blank">www.youtube.com/account_advanced</a>

**YouTube Playlist ID**

1. To find a YouTube Playlist ID, simply go to any YouTube Playlist and copy the Playlist ID from the URL bar in your web browser.

example: https://www.youtube.com/playlist?list=PLAYLISTID

**Known Issues**

The embeded player can take a few minutes to dedect a live stream before it auto embeds the live player, working on improving this in future updates. 

== Frequently Asked Questions ==

= Auto embed the live stream, how long does it take to detect that I am streaming live? =

The embeded player can take a few minutes to dedect a live stream before it auto embeds the live player, working on improving this in future updates.

= Can't get the plugin to work? =

A common error is usally due to an extra Space at the end of your API or Channel ID.

Also make sure you have filled in ALL the fields on the plugins settings page.

You can also test the live stream with the following details: Sky News Live 24/7

Test Youtube Channel ID: UCoMdktPbSTixAyNGwb-UYkQ

Test API Key: AIzaSyDtfQfxROiBBM1AydfRlOwypunxPwFgAB0 

== Screenshots ==

1. Auto embed youtube live stream with a shortcode
2. Youtube Live Stream Auto Embed settings page

== Changelog ==

= 1.0.2 =
* Created August 11, 2015

= 1.0.1 =
* Created July 29, 2015

= 1.0.0 =
* Created June 29, 2015

== Upgrade Notice ==

= 1.0.2 =
Third version release.

= 1.0.2 =
Second version release.

= 1.0.0 =
First version release.

== Credits ==
* [sykemedia](https://sykemedia.net/creative) - for plugin development
