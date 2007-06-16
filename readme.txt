=== Ultimate Google Analytics ===
Contributors: wvanderdeijl
Donate link: http://www.oratransplant.nl/uga/
Tags: google analytics, google, statistics, stats
Requires at least: 1.5.1.3
Tested up to: 2.2
Stable tag: trunk

Adds Google Analytics JavaScript to each page on your weblog. Can also add tracking to outbound links, downloads from your site and mail links.

== Description ==

Plugin to add Google Analytics JavaScript to each page on your weblog. Can also add tracking to outbound links, downloads from your own site and mailto: links. Configurable to also track links in comments and comment author-links. Optionally ignore hits by administrative users to prevent skewing of your statistics. Will add the Google Analytics JavaScript to the body of your page and not the head as most other GA plugins. Adding it to the head can slow down your pages.
Highly configurable through the admin panel.

=== Features ===

== Installation ==

1. Upload `plugin-name.php` to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Place `<?php do_action('plugin_name_hook'); ?>` in your templates

== Frequently Asked Questions ==

= A question that someone might have =

An answer to that question.

= What about foo bar? =

Answer to foo bar dilemma.

== Screenshots ==

1. This screen shot description corresponds to screenshot-1.(png|jpg|jpeg|gif). Note that the screenshot is taken from
the directory of the stable readme.txt, so in this case, `/tags/4.3/screenshot-1.png` (or jpg, jpeg, gif)
2. This is the second screen shot

== Arbitrary section ==

You may provide arbitrary sections, in the same format as the ones above.  This may be of use for extremely complicated
plugins where more information needs to be conveyed that doesn't fit into the categories of "description" or
"installation."  Arbitrary sections will be shown below the built-in sections outlined above.

== A brief Markdown Example ==

Ordered list:

1. Some feature
1. Another feature
1. Something else about the plugin

Unordered list:

* something
* something else
* third thing

Here's a link to [WordPress](http://wordpress.org/ "Your favorite software") and one to [Markdown's Syntax Documentation][markdown syntax].
Titles are optional, naturally.

[markdown syntax]: http://daringfireball.net/projects/markdown/syntax
            "Markdown is what the parser uses to process much of the readme file"

Markdown uses email style notation for blockquotes and I've been told:
> Asterisks for *emphasis*. Double it up  for **strong**.

`<?php code(); // goes in backticks ?>`
