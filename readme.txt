 === Plugin Name ===

Contributors: Qzzr
Plugin Name: Qzzr Shortcode
Plugin URI: http://qzzr.co
Tags: qzzr, quizzes, shortcode, quiz
Author URI: http://qzzr.co
Author: Qzzr
Requires at least: 2.6
Tested up to: 3.3.1
Stable tag: 1.00
Version: 1.00

 
== Description ==

Allows the use of a special short code [qzzr] for embedding Qzzr quizzes. 

**Example:** 
`[qzzr quiz=“123” height="517" width=“100%”]`

== Installation ==

For old school manual installation people: copy the folder “qzzr-shortcode" into the /wp-content/plugins/ folder. Then go to the Plugins area of the Admin and activate. Otherwise, search for “Qzzr Shortcode" from the admin area of your WordPress site in Plugins > Add New.

== Screenshots ==

1. Usage of shortcode example
2. Where to get shortcode

== Changelog ==

1.0 - Initial release.

== Frequently Asked Questions ==

**What is Qzzr?**

[Qzzr](http://www.qzzr.co) is a web app that helps anybody build beautiful engaging quizzes. It's great for driving social traffic, generating qualified leads, presenting targeted offers, tracking scores.

**Why is this useful?**

Shortcodes are cleaner and simpler! 
Only Editors and Admins can copy and paste the javascript embed code to embed a Qzzr quiz onto a WordPress page, authors cannot.

With embed codes you need to make sure to be in the "Text" tab of the writing area. If a user is in the "Visual" (default) tab, the embed code will not work. Short codes will work either way for all . 

**Parameters**

quiz: The id of your quiz. (Valid values are your quiz id "123" or "your-quiz-slug")  
width: The pixel or percentage width of your quiz container. ("500px" or "100%" - Default: "100%")
height: The pixel or percentage width of your quiz container. Setting this to auto will resize the quiz on each question to match the content. ("500px", "100%", "auto" - Default: "auto")
redirect: set this to true if you want shares to return to the page or post where you are embedding the quiz.
offset: You can set this to accomodate fixed headers. On desktop browsers, we scroll the window to the top of the quiz if the top is out of view. This will set a top margin to have the quiz to be offset from the top by the value you specify.


