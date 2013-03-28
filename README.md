ttrss-flattr
============

Plugin for the RSS reader Tiny Tiny RSS to flattr articles.

Copy this directory into the plugins folder of your tt-rss instance. Then, you can activate it in the settings panel of tt-rss.

Currently, the plugin checks the Flattr catalogue and only displays the button if the article exists as a thing there (see more comments in the code). Two things to note about that:

* The plugin does this check for each article being displayed, so it can weigh a bit on the loading time of your article view (but for me, it works quite okay and I am on shared hosting).
* Flattr has just integrated with popular services (e.g. Twitter and Github), such that everyone there can be flattred [1], so this plugin should probably be adapted to match those new circumstances. Not sure how yet, though.

[1] http://blog.flattr.net/2013/03/when-you-flattr-somebody-that-isnt-a-flattr-user-unclaimed-flattrs 
