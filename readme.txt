=== Futurama Quote Generator ===
Tags: futurama, leela, fry, bender, farnsworth
Contributors: uberjack
Requires at least: 2.0.2
Tested up to: 2.6.2
Stable tag: 1.0

This is a simple plugin that writes a random quote from TV's best short-lived show, Futurama.

== Description ==

Futurama Quote Generator writes a random quote from Futurama, including all the TV episodes and movies
(currently including Bender's Big Score and Beast with a Billion Backs). For an example, see <a href="http://0xff.akop.org/">0xff.akop.org</a>.

== Installation ==

1. Upload `futurama.php` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Place `<?php futurama_quote(); ?>` in your template
4. Modify the CSS, to make the quote appear how you'd like

== Appearance ==

You can use the following CSS if you're too lazy to define one yourself:

`
.futurama-contents { margin-top: 0.5em; }
.futurama-header { font-style: oblique; }
.futurama-contents p { border: solid 1px rgb(230, 219, 85); background-color: rgb(255, 255, 224); padding: 1em 2em 1em 2em; margin-bottom: 2em; margin-top: 0; }
.futurama-char { font-weight: bold;  }
`